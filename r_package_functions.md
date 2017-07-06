#### Functions in `R` package

`roctoNew` - Create a job skeleton.

`roctoCheck` - Check whether your job can be run

`roctoProfile` - Check particularities of the job in a new environment, e.g., which packages are used, profile testParams using `roctoRun` (ram, proc, space, time), generate metadata

`roctoPack` - Run check, profile, and then pack into .rocto file

`roctoRun` - Run a task from a rocto job


#### Workflow
1. Create job skeleton, setwd, open files
2. Program functions & add data
3. Check job
4. If error: go to 2, else: go to 5
5. Profile job
6. If job profile gives error: go to 2, else: go to 7
7. Package job in a `.rocto` file and open containing folder
