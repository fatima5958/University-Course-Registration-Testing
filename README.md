# University Course Registration — Manual Testing Project

A practical software QA project completed for CCS366 (Software Testing and Automation), focusing on the Software Testing Life Cycle (STLC), V-Model, program correctness, and reliability.

## Project overview

The local training application allows students to enter a name and email, select a course, and register. This project evaluates required fields, email validation, course selection, duplicate prevention, capacity boundaries, and confirmation messages.

## Test execution summary

| Metric | Result |
| --- | ---: |
| Tests executed | 8 |
| Passed | 7 |
| Failed | 1 |
| Open defects | 1 |

**Release recommendation: Do not release.** BUG-001 allows duplicate registrations for the same course.

## Project artifacts

- [Registration application](Registration.html) — original training source.
- [Requirements](Requirements/Requirements.csv) and [traceability matrix](Requirements/RTM.csv).
- [Test plan](Test%20Design/Test_Plan.md) and [executed test cases](Test%20Design/Test_Cases.csv).
- [Defect report](Execution/Defect_Report.md).
- [V-Model, correctness, and reliability notes](Test%20Design/V_Model_and_Reliability.md).
- [Test closure report](Closure/Test_Closure_Report.md).

The documentation is provided in browser-readable Markdown and CSV exports. Original Office files and screenshot evidence are not included in these text exports.

## How to run

1. Clone or download this repository.
2. Open Registration.html in Chrome or another browser.
3. Enter fictional test data and follow the test cases.
4. Refresh the page to reset the in-memory registrations.

## Known limitations

The training application intentionally contains a duplicate-registration defect. Web Development has a simulated capacity of two, including one seeded registration; the other courses have a capacity of 30. Passing the two-seat simulation does not establish full verification of the actual 30-student requirement. This is a local teaching application, not a production enrollment service.

## Skills demonstrated

Manual functional testing, positive and negative testing, boundary value testing, requirements traceability, defect documentation, test closure, V-Model concepts, and operational profile analysis.
