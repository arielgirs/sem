# USE CASE: 3 Produce a report of salaries by department (department manager).

## CHARACTERISTIC INFORMATION

### Goal in Context

As a department manager I want to produce a report on the salary of employees in my department so that I can support financial reporting for my department.

### Scope

Department.

### Level

Primary task.

### Preconditions

We know the department.  Database contains current employee salary data.

### Success End Condition

A report is available to be provided to finance.

### Failed End Condition

No report is produced.

### Primary Actor

Department manager.

### Trigger

A request for finance information is sent to the department manager.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for a given department.
2. Department manager extracts current salary information of all employees of their department.
3. Department manager provides report to finance.

## EXTENSIONS

3. **Department does not exist**:
    1. Department manager informs finance no department exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0