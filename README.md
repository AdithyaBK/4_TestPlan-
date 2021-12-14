# Test Plan

---

## High Level Test Plan

---

| TestID | Description                                                                                                                                  | Exp O/P | Actual O/P                       |Type of Test      |
| ------ | --------------------------------------------------------------------------------------------------------------------------------------------| ----------------------------- | ----------------------------- | ----------------- |
| H_01   |  To Book Room Online                |   SUCCESS                        | SUCCESS                        | Requirement Based |
| H_02   |    Displaying of room information                                                                                             |  SUCCESS                       | SUCCESS                       | Scenario Based |
| H_03   |  If Check-IN/Check-OUT Date <= 2019                                                                                                  | "Invalid option" | "Invalid option" | Scenario based    |
| H_04   |  Customer ID should not be more than two digit                                                                                                         | Invalid     | Invalid     | Boundary based    |
| H_05   | Saving the generated invoice in file with cutomer name                                                                                        | SUCCESS                       | SUCCESS                       | Requirement Based |
| H_06   | Customers can select food items according to their choice    | SUCCESS                       | SUCCESS                       | Requirement Based |
|H_07    |   Total bill generated (menu card + room booking)                   |  SUCCESS           |SUCCESS| Requirement Based|
## Low Level Test Plan

---

| TestID | Description                                                                                     | Exp O/P                  | Actual O/P               | Type of Test      |
| ------ | ------------------------------------------------------------------------------------------- | ------------------------ | ------------------------ | ----------------- |
| L_01   | Modes of payment                   | SUCCESS                    | SUCCESS              | Requirement Based |
| L_02   | Displaying the customers records                             |SUCCESS                 | SUCCESS | Requirement Based |
| L_03   | Adding the items from menu card                                                                   | SUCCESS                 | SUCCESS            | Requirement Based |
| L_04   | Search Invoice, take customer name as input and return the invoice related to that customer | Customer Name | Customer Invoice                | Requirement Based |
