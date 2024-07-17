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

|    name            |          about          |                  title                   |          labels         |         assignees            |
|--------------------|-------------------------|------------------------------------------|-------------------------|------------------------------|
| Davide Mastroianni |    Marketing Manager    | Integrate social media data into reports | Social Media, Reporting | Carlo Verdone (Data Analyst) |

---

**As a** Marketing Manager  
**I need** to integrate social media data  
**So that** I can analyze social media performance alongside other marketing data

### Details and Assumptions
* Data will be available via API. Requires integration development.

### Acceptance Criteria  
* (Reports will display social media metrics like follower growth and engagement alongside website traffic data)
  
```gherkin
Given The social media data integration is complete.
When A marketing report is generated.
Then The report displays social media data alongside website traffic data.
