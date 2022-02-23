# USE CASE: 8 Delete an Employee's Details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to delete an employee's details* so that *the company is compliant with data retention legislation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

The employee's record exists in the database.

### Success End Condition

The employee's details do not exist in the database anymore.

### Failed End Condition

The employee's details remain in the database.

### Primary Actor

HR Advisor.

### Trigger

An employee's work contract is terminated.

## MAIN SUCCESS SCENARIO

1. Employee is no longer employed by the company.
2. HR advisor captures name of the employee who is not part of the company anymore.
3. HR advisor deletes existing records of the employee from the database.

## EXTENSIONS

3. **Employee does not exist in the database**:
    1. HR advisor informs finance no such employee exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0