---
hide:
  - navigation
  - toc

---

**Notes:** Details of a Media Title, such as a Book or Movie. This is distinct from a Media Copy which is a particular   


### Inherits from: 


None  


### Inherited by: 


None  


## Properties


| Name | Type | Notes | Required |
| :--- | :--- | :--- | :---: |
| title | [String](../../core-types/primitives/string.md}) | The **title** of this Media Title (**String**)  | :material-check: |
| isbn | [String](../../core-types/primitives/string.md}) | The **isbn** of this Media Title (**String**)  | :material-check: |
| author | [String](../../core-types/primitives/string.md}) | The **author** of this Media Title (**String**)  | :material-check: |
| mediaType | [Media Type](media-type.md}) | The **media type** of this Media Title (**Media Type**)  | :material-check: |
| rating | [Float](../../core-types/primitives/float.md}) | The **rating** of this Media Title (**Float**)  | :material-check: |
| price | [Float](../../core-types/primitives/float.md}) | The **price** of this Media Title (**Float**)  | :material-check: |
| description | [String](../../core-types/primitives/string.md}) | The **description** of this Media Title (**String**)  | :material-check: |
| wasReservedByBorrowers | [[Borrower]](borrower.md}) | The set of **Borrower** this **Media Title** was reserved by |  |
| borrowers | [[Borrower]](borrower.md}) | The set of **Borrower** for this **Media Title** |  |
| isHeldAsMediaCopies | [[Media Copy]](media-copy.md}) | The set of **Media Copy** this **Media Title** is held as | :material-check: |
