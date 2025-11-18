---
hide:
  - navigation
  - toc

---

**Notes:** A Borrower who cannot borrow certain Media Titles and a limited number of Media Copies.  


### Inherits from: 


[Borrower, ](borrower.md})  


### Inherited by: 


None  


## Properties


| Name | Type | Notes | Required |
| :--- | :--- | :--- | :---: |
| dob | [Date](../../core-types/primitives/date.md}) | The **dob** of this Junior Borrower (**Date**) <br>The Date of Birth (DOB) of this Junior Borrower | :material-check: |
| borrower | [Borrower](borrower.md}) | The abstract concept of a Borrower. Actual Borrowers must be either Adult or Junior. | :material-check: |
| wasVouchedForByAdultBorrower | [Adult Borrower](adult-borrower.md}) | The  **Adult Borrower** this **Junior Borrower** was vouched for by | :material-check: |
