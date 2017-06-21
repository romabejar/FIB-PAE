# Thing-Sourcing system

## Requirements

- The system should be able to receive and deal with "jobs".
  - "jobs": any kind of thing that could be asked and done.
    - Should contain expected result, and conditions.
- The system should contain a set of job solvers.
- The set of job solvers, should be able to be expanded at run-time.
- The system should decide by itself to which and to how many job solver tries to arrange a job solution.
- There would be job solvers that would expand the system functionality, and jobs solvers that just solve specific problems.
  - Examples of system functionality job solver:
    - job breaker: A job solver that can break a job into smaller jobs, collect the results and unify the solution of the job.
    - job solution validator: A job solver that can validate a job solution.
  - Examples of specific problem job solver:
    - amazon turker: A job solver that has a comunity of humans behind that solve problems, by their will, expecting a retribution.
    - certificate traduction obtainer: A job solver that gets a certificated traduction of a text.

- job solvers can interactuate with things or people to solve their problems, but thats part of each job solver specification.
