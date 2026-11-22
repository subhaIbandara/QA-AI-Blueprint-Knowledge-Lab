# ⭐ STAR Framework – Structured Communication

The STAR framework helps you organize information and communicate clearly, especially when answering interview questions or explaining work experiences.

This framework can be adapted to QA activities to communicate testing scenarios, issues, responsibilities, actions, and outcomes in a clear and structured way.

---

### S > Situation

**Purpose:** Explain the testing context or background.

What feature or functionality were you testing? What was the situation?

**Example:**

During regression testing of the application, I was validating the login functionality after a new release.

### T > Task

**Purpose:** Explain what you needed to verify or achieve.

What was your testing responsibility? What needed to be validated?

**Example:**

I was responsible for verifying that users could log in successfully using valid credentials and that the login functionality worked as expected.

### A > Action

**Purpose:** Describe the specific testing activities YOU performed.

What test cases did you execute? What test data did you use? What validation did you perform?

**Example:**

- Executed positive and negative login test cases.
- Entered valid and invalid credentials.
- Verified input validations and error messages.
- Checked the application response after clicking the Login button.
- Captured screenshots and documented the issue.

### R > Result

**Purpose:** Explain the testing outcome or findings.

What was the result of your testing? Did the functionality pass or fail? Were any defects identified?

**Example:**

The positive login test case failed because the application displayed an error message despite entering valid credentials. I documented the issue, attached screenshots, and reported the bug to the development team.

---

## Quick Reference

| Letter | QA Meaning | Key Question |
|---|---|---|
| S | Situation | What feature or functionality was being tested? |
| T | Task | What needed to be verified? |
| A | Action | What testing activities did I perform? |
| R | Result | What was the testing outcome? |

---

## Practical QA Communication Examples

### 1. Bug Reporting

**Structure:** Context → Steps → Expected Result → Actual Result → Evidence

### 2. Test Execution Report

**Structure:** Testing Scope → Test Execution → Pass/Fail Results → Defects → Conclusion

### 3. Daily QA Status Update

**Structure:** Completed Activities → In-progress Activities → Identified Bugs → Blockers → Next Steps

### 4. Sharing Test Results

**Structure:** Feature Tested → Testing Performed → Findings → Final Status

### 5. Explaining a Testing Issue to a Developer

**Structure:** Issue Description → Reproduction Steps → Expected Behaviour → Actual Behaviour → Supporting Evidence

---

## Key Takeaway

For QA communication, remember:

**Situation → Testing Responsibility → Testing Activities → Testing Outcome**

The objective is to communicate:

- What you tested.
- Why you tested it.
- How you tested it.
- What you discovered.
- What needs to happen next.

**Important:** STAR is a general communication framework, not a mandatory bug-reporting format. Adapt the structure depending on the QA activity and the information the recipient needs.

---

# 📌 Additional Section: Applying STAR to Real QA Tasks

The STAR framework can also help you understand and organize practical QA assignments before starting the actual work.

Below is an example of applying STAR to a functional test planning task.

## Example: Create a Functional Test Plan for the Login Module

**Task Description:**

Create a functional test plan for the login module using the provided template:

`Chapter_03_Prompt_Engineering_QA/Template.md`

### S > Situation – Understand the Context

**Purpose:** Understand the background and testing context.

**What is the situation?**

A functional test plan needs to be prepared for the application's login module.

The purpose is to verify that login functionality behaves according to the supplied requirements.

**What should you identify?**

- Which feature needs to be tested?
- What requirements are available?
- Is there an existing test plan template?
- What is the expected deliverable?

**Example:**

The login module is an important application functionality that allows users to authenticate and access the system. A functional test plan needs to be created to verify its expected behavior.

### T > Task – Understand Your Responsibility

**Purpose:** Identify what needs to be achieved and delivered.

**What needs to be achieved?**

Create a functional test plan using the supplied template.

**Required testing coverage:**

- Valid login credentials.
- Invalid credentials.
- Empty fields.
- Dashboard access after successful login.
- Positive, negative, and boundary scenarios where supported by the requirements.

**Additional responsibilities:**

- Define testing objectives.
- Identify in-scope and out-of-scope functionality.
- Define the testing approach.
- Identify test environment requirements.
- Identify test data requirements.
- Define entry and exit criteria.
- Identify test deliverables.
- Document risks and open questions.

**Important:** Do not invent unspecified application behavior.

Examples:

- Password complexity rules – Requires clarification.
- Exact error messages – Requires clarification.
- Session timeout duration – Requires clarification.

### A > Action – Perform the QA Activities

**Purpose:** Describe the steps and activities performed to complete the task.

**How will you complete the task?**

Follow a structured approach.

**Step 1: Review the Requirements and Template**

- Review the supplied login requirements.
- Read `03_Prompt_Engineering_QA/Template.md`.
- Understand the expected test plan structure.
- Identify missing or unclear requirements.

**Step 2: Define Testing Objectives**

Establish what the testing should achieve.

- Verify successful login with valid credentials.
- Verify handling of invalid credentials.
- Verify empty-field validation.
- Verify dashboard access after successful login.

**Step 3: Define Testing Scope**

Identify what is included and excluded.

| In Scope | Out of Scope |
|---|---|
| Valid login | Unrelated application features |
| Invalid credentials | Password reset, unless specified |
| Empty fields | Unspecified authentication mechanisms |
| Dashboard access after login | Features outside the supplied requirements |

**Step 4: Define Test Scenarios**

Include positive, negative, and boundary scenarios where supported by requirements.

| Scenario Type | Example |
|---|---|
| Positive | Login using valid credentials |
| Negative | Login using invalid credentials |
| Negative | Submit the login form with empty fields |
| Boundary | Test input length boundaries if defined in requirements |
| Functional | Verify dashboard access after successful login |

**Step 5: Define Environment and Test Data**

Identify the required resources.

**Environment:**

- Application test environment.
- Supported browsers, if specified.
- Network connectivity.
- Access to the login module.

**Test Data:**

- Valid username and password.
- Invalid credentials.
- Empty input values.

**Step 6: Define Entry and Exit Criteria**

**Entry Criteria:**

- Login functionality is available for testing.
- Relevant requirements are available.
- Test environment is accessible.
- Required test data is prepared.

**Exit Criteria:**

- Planned test scenarios have been executed.
- Test results have been documented.
- Identified defects have been reported.
- Outstanding issues have been communicated.

**Note:** These are proposed recommendations and should be aligned with project requirements.

**Step 7: Identify Risks and Open Questions**

Document uncertainties instead of making assumptions.

Examples:

- Password complexity requirements – Requires clarification.
- Exact validation messages – Requires clarification.
- Session timeout behavior – Requires clarification.
- Browser compatibility requirements – Requires clarification.

**Step 8: Prepare and Review the Test Plan**

Use the supplied template and check:

- Completeness.
- Accuracy.
- Requirement alignment.
- Clear language.
- Consistent formatting.
- Proper documentation of assumptions and open questions.

### R > Result – Deliver the Final Output

**Purpose:** Explain the final deliverable and expected outcome.

**What should be produced?**

A functional test plan containing the following sections:

| No. | Required Section |
|---|---|
| 1 | Test Plan ID and Title |
| 2 | Objective |
| 3 | In Scope and Out of Scope |
| 4 | Test Approach |
| 5 | Test Scenarios |
| 6 | Environment and Test Data |
| 7 | Entry and Exit Criteria |
| 8 | Deliverables |
| 9 | Risks and Open Questions |

**Expected outcome:**

- A structured functional test plan is prepared.
- Positive, negative, and supported boundary scenarios are documented.
- Test environment and test data requirements are identified.
- Entry and exit criteria are defined.
- Risks and unclear requirements are documented.
- The supplied template is followed.
- No unsupported application behavior is assumed.

---

## Final QA Learning Reference

| STAR | General Meaning | Practical QA Application |
|---|---|---|
| S – Situation | Understand the context | Understand the feature and requirements |
| T – Task | Identify the responsibility | Identify what needs to be tested or delivered |
| A – Action | Perform the activities | Review, analyze, design, execute, and document |
| R – Result | Explain the outcome | Deliver test plans, test cases, bug reports, or test results |

### Remember

**STAR is not just for interviews. It can also help you structure your thinking and communicate your QA work.**

Whenever you receive a QA assignment, think:

1. **Situation:** What is the context?
2. **Task:** What am I expected to deliver?
3. **Action:** What steps should I perform?
4. **Result:** What should the final output contain?

**Understand → Plan → Perform → Document → Deliver**

* Use STAR to organize your approach, then use the appropriate QA template to produce the actual deliverable.
