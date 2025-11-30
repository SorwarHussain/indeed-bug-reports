# indeed-bug-reports
Bug report documenting an issue in the Indeed job application form where the Continue button becomes disabled after switching the sponsorship question from “Yes” to “No.”

# Bug Report  
**Title:** Continue button becomes disabled after selecting “Yes” then switching to “No” on required sponsorship radio field

## Description
When applying for a job on Indeed, selecting **“Yes”** for the required question *“Will you now or in the future require sponsorship?”* reveals an additional input field. If the user then switches the selection back to **“No,”** the conditional field hides but the **Continue** button becomes non-functional, preventing the form from submitting.

---

## Steps to Reproduce
1. Go to any job application page on Indeed.
2. Choose a job that includes the question **“Will you now or in the future require sponsorship?”**
3. Click **“Apply now.”**
4. Add or update your resume.
5. Click **“Continue.”**
6. Answer all other required questions.
7. Locate the required radio field **“Will you now or in the future require sponsorship?”**  
   - Selecting **“Yes”** reveals a conditional input field.
8. Select **“Yes.”**
9. Without filling the additional field, switch the selection back to **“No.”**  
   The conditional field hides.
10. Complete any remaining fields.
11. Click **“Continue.”**

---

## Expected Behavior
The form should successfully proceed when **“No”** is selected, because the hidden conditional field should not be required.

---

## Actual Behavior
- The **Continue** button becomes disabled or does nothing.
- The form cannot proceed.
- The hidden conditional input is likely still being validated as required.

---

## Environment
- **Website:** Indeed  
- **Date Observed:** Today  (28 Nov, 2025)
- **Browser:** Chrome  
- **Operating System:** Linux  

---

## Additional Notes
- Refreshing the page resets the form, but the issue occurs again when repeating the **Yes → No** selection flow.
- This issue blocks applicants from completing job applications that include this question.
