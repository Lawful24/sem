# USE CASE: 7 Update an Employee's Details in the Database

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to update an employee's details* so that *employee's details are kept up-to-date.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the details of the employee. The employee's record exists in the database.

### Success End Condition

The employee's details are modified.

### Failed End Condition

The employee's details remain untouched. The employee's record is wrongly overwritten.

### Primary Actor

HR Advisor.

### Trigger

An employee's details change.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for a given role.
2. HR advisor captures name of the role to get salary information for.
3. HR advisor extracts current salary information of all employees of the given role.
4. HR advisor provides report to finance.

## EXTENSIONS

3. **Role does not exist**:
    1. HR advisor informs finance no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0