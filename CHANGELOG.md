# 1.27.0
## New
## Fixed

# 1.26.0
## New
- Moved several methods from `ConditionReportMainPresenter` to `BaseQuestion`, and removed many compiler warnings
- Refactored DCPQuestionButtons into DcpQuestionButtons with MVP
- Condition report main presenter initial MVP
## Fixed
- Moved several methods from `ConditionReportMainPresenter` to `BaseQuestion`, and removed many compiler warnings

# 1.25.1
## Fixed
- It is not possible to finish a submission with additional notes

# 1.25.0
## New
- Moved several methods from `ConditionReportMainPresenter` to `BaseQuestion`, and removed many compiler warnings
- Refactored DCPQuestionButtons into DcpQuestionButtons with MVP
- Condition report main presenter initial MVP
## Fixed
- Options were not being displayed for SelectionQuestions in CR
- Reduce options `loadFromHash` function's complexity order from n^2 to n
- Prevent `IndexOutOfBoundsException`
- Prevent crash while vin sanitize fails
- Navigation footer not being displayed on the first time after pressing IME button
- Added defensive programming
