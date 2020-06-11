# An ontology for leadership development in life-long learning

## v0.1: A work in progress!
A boil-the-ocean version of lots of thoughts (both correct, incorrect, illformed and poorly articulated) before socialisation and refinment.

 ```mermaid
erDiagram
 People ||--|| Individual : is
    Individual }|--|{ Diversities : has
        Diversities }|--|{ Invisible : are
            Invisible }|--|{ Gender : is
            Invisible }|--|{ Orientation : is
            Invisible }|--|{ Belief-system : is
            Invisible }|--|{ Ability : is
        Diversities }|--|{ Visible : are
            Visible }|--|{ Ethnicity : is
            Visible }|--|{ Sex : is
            Visible }|--|{ Age : is
            Visible }|--|{ Pregnant : is
            Visible }|--|{ Ability : is
        Diversities }|--o{ Content : interpret
    Individual ||--|| Relationships : has
        Relationships ||--|| Type : has
            Type ||--|| Parent : is
            Type ||--|| Adult : is
            Type ||--|| Child : is
        Relationships ||--|| Group : is
    People }|--|{ Group : "exist in"
        Group }|--|{ People : Contains
    People ||--|{ Role : has
        Role }|--|{ Group : "In a"
        Role |o--|{ Facilitator : is
        Role |o--|{ Designer : is
            Designer }|--|{ Content : creates
        Role |o--|{ Leader : is
        Role |o--|{ Team-member : is
    People }|--|{ Motivation : Has

Intervention }|--|{ Content : has
    Content }|--|{ Theme : has
    Content }|--|{ Assets : has



```
