# QA Process

## Before QA

Before the issue gets moved to QA, the person who addressed the issue should provide review instructions. The issue template can contain a section for this. By making it part of the main description, it's easier to reference and prevents from getting lost in the comment section.

The instructions should at least include:
- where to test the issue – relevant URLs
- any setup required to properly QA the item
  - record creation or seeding (if this cannot be done by the QA person, then the developer should have already completed this step)
- fill out any steps that the acceptance criteria does not cover
- any edge cases you can think of to test and how to test them

## Test Plan
This can be difficult to create if your team does not have a dedicated QA person. It is also possible to split up who creates the test plan and who executes it. It may make sense for your team to include it as part of the review instructions. Taking the acceptance criteria or the definition of done provided in the issue and the review instructions, a plan should be written up to follow as a guide in testing every possible iteration the person assigned to QA can think of.

As an example, let us imagine an issue that calls for the addition of a phone number field to a form and the field should be required. Iterations the QA person might go through are:
1. create a new record without phone number
2. create a new record with a phone number with an incorrect format
3. create a new record with a phone number in the correct format
4. edit and save a pre-existing record without a phone number
5. edit and save a record with a phone number in the incorrect format
6. edit and save a record with a phone number in the correct format
7. edit a record and remove the phone number
8. validate the phone number persisted after saving in the places that it should be

## Executing the Plan
At this point, the QA person should follow the test plan as written, keeping track of the items that passed and failed. If there are tests that failed, feedback can be provided in the form of:
- Expected Result
- Actual Result
- Steps to reproduce

## Triaging the failed items
It is now up to the team and primarily the PM, to decide how these items should be addressed. Should they be handled within the issue with sending it back through the workflow? Should a new bug be created outside or inside the sprint? If inside the current sprint, the bug should be sized and ideally replace another item in the sprint. However, if this is the case, consider why it should not be handled within the original issue.
