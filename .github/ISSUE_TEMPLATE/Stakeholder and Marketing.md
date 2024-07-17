---
name: A unique identifier for the issue
about: A brief summary of the stakeholder's role
title: A clear and concise title for the requirement
labels: Tags to categorize the requirement
assignees: Username of the person responsible for implementing

---

**As a** Stakeholder Role  
**I need** Functionality desired  
**So that** Benefit of fulfilling the requirement
   
 ### Details and Assumptions
 * Any specific details or assumptions documented
   
 ### Acceptance Criteria  
 * (Define how to determine successful implementation)
   
 ```gherkin
 Given [Context for testing]
 When  [Action taken to test]
 Then  [Expected outcome]
 ```

---

|    name            |          about          |           title             |      labels      |      assignees      |
|--------------------|-------------------------|-----------------------------|------------------|---------------------|
| Davide Mastroianni |    Store Administrator  | Create a Product in Catalog | Administrator IT |     Carlo Verdone   |

---

**As a** Store Administrator 
**I need** to create a new product in the catalog  
**So that** I can add items for sale on the website

### Details and Assumptions
* As a store administrator, you want to create a new product in the catalog
* This allows you to add items for sale on the website

### Acceptance Criteria  
* When you submit a new product with details, the product should be successfully created in the catalog
* The product details should be retrievable using its unique identifier
  
```gherkin
Given I am a logged-in store administrator
When I submit a new product with details 
Then the product should be successfully created in the catalog
And the product details should be retrievable by its unique identifier
 ```

---
