# Entity Relationship Diagram syntax

## What is an Entity Relationship Diagram?

An Entity Relationship Diagram defines the relationship between 

## How do you write an ERD?

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

## [MarkDdwn][markdown] Version

 ```mermaid
erDiagram

 first-entity ||--|{ second-entity : has

```

## [Live editor][mermaid live editor] version

[![](https://mermaid.ink/svg/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgICAgIENVU1RPTUVSIH18Li58eyBERUxJVkVSWS1BRERSRVNTIDogaGFzXG4gICAgICAgIENVU1RPTUVSIHx8LS1veyBPUkRFUiA6IHBsYWNlc1xuICAgICAgICBDVVNUT01FUiB8fC0tb3sgSU5WT0lDRSA6IFwibGlhYmxlIGZvclwiXG4gICAgICAgIERFTElWRVJZLUFERFJFU1MgfHwtLW97IE9SREVSIDogcmVjZWl2ZXNcbiAgICAgICAgSU5WT0lDRSB8fC0tfHsgT1JERVIgOiBjb3ZlcnNcbiAgICAgICAgT1JERVIgfHwtLXx7IE9SREVSLUlURU0gOiBpbmNsdWRlc1xuICAgICAgICBQUk9EVUNULUNBVEVHT1JZIHx8LS18eyBQUk9EVUNUIDogY29udGFpbnNcbiAgICAgICAgUFJPRFVDVCB8fC0tb3sgT1JERVItSVRFTSA6IFwib3JkZXJlZCBpblwiXG5cdFx0XHRcdFx0IiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgICAgIENVU1RPTUVSIH18Li58eyBERUxJVkVSWS1BRERSRVNTIDogaGFzXG4gICAgICAgIENVU1RPTUVSIHx8LS1veyBPUkRFUiA6IHBsYWNlc1xuICAgICAgICBDVVNUT01FUiB8fC0tb3sgSU5WT0lDRSA6IFwibGlhYmxlIGZvclwiXG4gICAgICAgIERFTElWRVJZLUFERFJFU1MgfHwtLW97IE9SREVSIDogcmVjZWl2ZXNcbiAgICAgICAgSU5WT0lDRSB8fC0tfHsgT1JERVIgOiBjb3ZlcnNcbiAgICAgICAgT1JERVIgfHwtLXx7IE9SREVSLUlURU0gOiBpbmNsdWRlc1xuICAgICAgICBQUk9EVUNULUNBVEVHT1JZIHx8LS18eyBQUk9EVUNUIDogY29udGFpbnNcbiAgICAgICAgUFJPRFVDVCB8fC0tb3sgT1JERVItSVRFTSA6IFwib3JkZXJlZCBpblwiXG5cdFx0XHRcdFx0IiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)

## JS HTML version

```html
    <script src="mermaid.min.js"></script>
    <script>mermaid.initialize({startOnLoad:true});</script>
    <div class="mermaid">
        erDiagram

        first-entity ||--|{ second-entity : has
    </div>
```

<script src="mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>
<div class="mermaid">
    erDiagram
    first-entity ||--|{ second-entity : has
</div>



[mermaid]: https://mermaid-js.github.io/mermaid/
[mermaid live editor]: https://mermaid-js.github.io/mermaid-live-editor/
[markdown]: https://github.github.com/gfm/

