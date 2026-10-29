# **Gherkin & BDD** 

# **1\. Feature File Example**

```
Feature: User Login and Dashboard Access
  Scenario: Successful login with valid credentials
    Given the user is on the login page
    When the user enters valid username and password
    And clicks the login button
    Then the user should be redirected to the dashboard page
```

# **2\. Quick Gherkin Keywords Guide**

* **Feature:** Defines the high-level software module or functionality under test.

* **Scenario:** Describes a specific business workflow or test case.  
* **Given:** Establishes the initial context or preconditions.  
* **When:** Specifies the user action or trigger event.  
* **And:** Connects additional steps seamlessly within Given, When, or Then clauses.  
* **Then:** Asserts the expected outcome or postcondition.

# **3\. Purpose in BDD & Automated Testing**

Gherkin bridges the gap between technical and non-technical team members by translating human-readable specifications into automated test scripts using frameworks like CucumberJS or Protractor. Through step definitions, plain language statements bind directly to test execution code, creating living documentation that continuously reflects system requirements and automated verification status.  
