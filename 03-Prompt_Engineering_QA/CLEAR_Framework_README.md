# ⭐ CLEAR Framework – Structured Prompting and Communication

The CLEAR framework helps you create clear, structured, and effective instructions when communicating with AI tools, developers, QA team members, or other stakeholders.

It helps reduce ambiguity, define expectations, and ensure that the requested output meets the intended requirements.

---

### C > Context

**Purpose:** Provide background information and explain the situation.

What is the task about? What feature, application, or problem are you working on?

**Example:**

I am working on a web application that contains a login module. I need to create a functional test plan to verify the login functionality.

**Key takeaway:** Provide enough background information so the recipient understands the task.

---

### L > Limitations

**Purpose:** Define restrictions, boundaries, and things that should be avoided.

What should not be included? Are there any constraints or limitations?

**Example:**

- Use only the supplied requirements.
- Do not invent password complexity rules.
- Do not assume exact error messages.
- Do not assume session timeout behavior.
- Mark unspecified behavior as "Requires clarification".

**Key takeaway:** Clearly communicate what should and should not be assumed.

---

### E > Expectations

**Purpose:** Explain what you expect to achieve or receive.

What should the final output look like? What information should it contain?

**Example:**

The functional test plan should include:

- Test Plan ID and Title.
- Testing Objectives.
- In Scope and Out of Scope.
- Test Approach.
- Test Scenarios.
- Environment and Test Data.
- Entry and Exit Criteria.
- Deliverables.
- Risks and Open Questions.

**Key takeaway:** Define the expected output before starting the task.

---

### A > Actions

**Purpose:** Explain the activities or steps that need to be performed.

What should the recipient do to complete the task?

**Example:**

- Review the supplied login requirements.
- Analyze the login functionality.
- Identify positive, negative, and supported boundary scenarios.
- Define the testing approach.
- Identify test environment and test data requirements.
- Document risks and open questions.
- Prepare the test plan using the supplied template.

**Key takeaway:** Provide clear and actionable instructions.

---

### R > Requirements

**Purpose:** Define the specific rules, conditions, and standards that must be followed.

What rules must the final output satisfy?

**Example:**

- Use the provided template.
- Cover valid login, invalid credentials, and empty fields.
- Include dashboard access after successful login.
- Include positive, negative, and boundary scenarios where supported.
- Use clear and professional language.
- Use tables where appropriate.
- Mark unspecified behavior as "Requires clarification".

**Key takeaway:** Specify the conditions that determine whether the task has been completed correctly.

---

## Quick Reference

| Letter | Meaning | Key Question |
|---|---|---|
| C | Context | What is the background? |
| L | Limitations | What restrictions should be followed? |
| E | Expectations | What should the final output contain? |
| A | Actions | What steps should be performed? |
| R | Requirements | What rules must be satisfied? |

---

## Practical QA Applications

The CLEAR framework can be used in different QA activities.

### 1. Creating Test Plans

**Structure:** Context → Limitations → Expectations → Actions → Requirements

### 2. Writing Test Cases

- **Context:** Identify the feature being tested.
- **Limitations:** Define testing boundaries.
- **Expectations:** Define the expected test case structure.
- **Actions:** Describe test design activities.
- **Requirements:** Specify coverage and formatting rules.

### 3. Bug Reporting

- **Context:** Explain where the issue occurred.
- **Limitations:** Include relevant environment and reproduction conditions.
- **Expectations:** Explain the expected bug report information.
- **Actions:** Describe the steps to reproduce the issue.
- **Requirements:** Include actual results, expected results, and supporting evidence.

### 4. Test Execution Reports

- **Context:** Identify the testing activity.
- **Limitations:** Define the testing scope.
- **Expectations:** Specify the report structure.
- **Actions:** Document executed test cases.
- **Requirements:** Include pass/fail results, defects, and conclusions.

### 5. Communicating with Developers

- **Context:** Explain the technical issue.
- **Limitations:** Identify relevant conditions and constraints.
- **Expectations:** Explain the required clarification or resolution.
- **Actions:** Describe the reproduction steps.
- **Requirements:** Provide expected behavior and supporting evidence.

---

## Example: Applying CLEAR to a Real QA Task

### Task: Create a Functional Test Plan for the Login Module

### C – Context

I am testing a web application's login module and need to prepare a functional test plan using the supplied template.

### L – Limitations

- Use only the supplied requirements.
- Do not invent password rules.
- Do not assume exact error messages.
- Do not assume session timeout values.
- Mark unspecified behavior as "Requires clarification".

### E – Expectations

The final test plan should contain:

- Test Plan ID and Title.
- Objective.
- In Scope and Out of Scope.
- Test Approach.
- Test Scenarios.
- Environment and Test Data.
- Entry and Exit Criteria.
- Deliverables.
- Risks and Open Questions.

### A – Actions

- Review the supplied requirements.
- Analyze the login functionality.
- Identify positive, negative, and supported boundary scenarios.
- Define the test approach.
- Identify environment and test data requirements.
- Define entry and exit criteria.
- Document risks and open questions.
- Prepare the test plan.

### R > Review

**Purpose:** Review the final output to ensure it meets the expected objectives, follows the given instructions, and does not contain missing information or unsupported assumptions.

**What should be checked?**

- Does the output meet the expected objectives?
- Have all requested items been covered?
- Were the limitations and constraints followed?
- Is there any missing, incorrect, or unsupported information?
- Does the output follow the requested structure and format?
- Are there any unclear areas that need further clarification?

**Example:**

After generating a functional test plan:

- Review the test plan against the supplied requirements.
- Verify that all expected sections are included.
- Check positive, negative, and boundary scenario coverage.
- Ensure no unsupported assumptions were introduced.
- Verify that unspecified behavior is marked as "Requires clarification".
- Check the overall clarity, accuracy, and completeness.
- Identify any gaps and update the test plan if necessary.

**Key takeaway:** Review the final output to ensure it is accurate, complete, and aligned with the original instructions before considering the task complete.

---

## CLEAR vs STAR Framework

| Framework | Main Purpose | When to Use |
|---|---|---|
| STAR | Structure experiences and explain outcomes | Interviews, QA updates, explaining completed work |
| CLEAR | Structure instructions and define expectations | Prompt engineering, QA assignments, task instructions |

---

## Key Takeaway

**STAR helps you explain your work.**

**CLEAR helps you communicate what needs to be done.**

### Remember

- **C:** What is the context?
- **L:** What are the limitations?
- **E:** What are the expectations?
- **A:** What actions should be performed?
- **R:** What requirements must be satisfied?

**Understand → Define → Instruct → Perform → Validate**

Use CLEAR when preparing prompts, assigning QA tasks, or communicating detailed instructions. Use STAR when explaining your responsibilities, activities, and results.

**Important:** CLEAR has multiple interpretations in different fields. The version above is a practical QA and prompt-engineering adaptation, not a universally standardized definition.
