
# Operation: county stats


Notes: Get the **Borrower Stats By County** filtered by the relevant parameters.
Gets the statistics for each County. For each Town and Borrower the total number of Loans is retrieved.


#### Parameters


| Name | Type | Notes | Required |
| :--- | :--- | :--- | :--- |
| borrowerType | [String](../../core-types/primitives/string.md) | The optional **borrower type** query parameter. |  |

#### Return Type


| Type | Notes |
| :---: | :--- |
| [BorrowerStatsByCounty](interface-types/county-stats/borrower-stats-by-county.md) | The **Borrower Stats By County** returned by this operation. |
