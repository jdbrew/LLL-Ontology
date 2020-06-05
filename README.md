# LLL-Ontology

An ontology for life-long leadership development

This repository is licensed under [CC BY 4.0][licence-cc-by] ![cc](/assets/cc_icon-22px.svg) ![by](/assets/cc-by_icon-22px.svg)

## Entity Relationship Diagram syntax

Using [Mermaid syntax][mermaid] in [GF Markdown][markdown]

Each definition statement is represented by the following elements

```html
 <first-entity> <relationship> <second-entity> : <relationship-label>
 ```

- [ ] TODO : `<first-entity>`
- [ ] TODO : `<second-entity>`
- [ ] TODO : `<relationship>`

The **`<relationship>`** show how two entities inter-relate. Common keyboard characters are used to create a diagram:

 Value (left)  | Value (right)    | Meaning
:------------: | :--------------: | -------------------------------
\|o-           | -o\|             | Zero or one
\|\|-          | -\|\|            | Exactly one
}o-            | -o{              | Zero or more (no upper limit)
}\|-           | -\|{             | One or more (no upper limit)

- [ ] TODO : `<relationship-label>`
- [ ] TODO : **An example**

 ```mermaid
erDiagram

```

[licence-cc-by]: https://creativecommons.org/licenses/by/4.0
[mermaid]: https://mermaid-js.github.io/mermaid/
[markdown]: https://github.github.com/gfm/
