---
hide:
  - navigation
  - toc

---

**Notes:** The abstract concept of a Borrower. Actual Borrowers must be either Adult or Junior.  


### Inherits from: 


[Person, ](../../personal-details/person.md})  


### Inherited by: 


[JuniorBorrower, ](junior-borrower.md})[AdultBorrower, ](adult-borrower.md})  


## Properties


| Name | Type | Notes | Required |
| :--- | :--- | :--- | :---: |
| person | [Person](../../personal-details/person.md}) |  | :material-check: |
| reservedMediaTitles | [[Media Title]](media-title.md}) | The set of **Media Title** this **Borrower** reserved |  |
| mediaTitles | [[Media Title]](media-title.md}) | The set of **Media Title** for this **Borrower** |  |
| borrowedMediaCopies | [[Media Copy]](media-copy.md}) | The set of **Media Copy** this **Borrower** borrowed |  |
| mediaCopies | [[Media Copy]](media-copy.md}) | The set of **Media Copy** for this **Borrower** |  |
| previouslyLivedAtAddresses | [[Address]](../../personal-details/address.md}) | The set of **Address** this **Borrower** previously lived at |  |

## Operations


| Name | Return Type | Notes |
| :--- | :--- | :--- |
| [profile](op-profile.md}) | [BorrowerProfile](../interfaces/interface-types/borrower-profile/borrower-profile.md}) |  |
