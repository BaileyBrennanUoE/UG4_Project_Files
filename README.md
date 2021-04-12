# UG4_Project_Files
Download the zip and extract files. RABIT250 is the folder with all simulation relations and the Benchmark.jar tool.
It also includes the warmup folder and the test folders used to obtain the results in my dissertation.

Benchmark.jar takes in five arguments:
    la - this is the lookahead values to be used by the simulations
    folder directory - this is the test folder path, test files should have the naming format "testFilei.ba" where 0 <= i <= n
    n - the number of tests files within the above folder directory
    flag - corresponds to the type of benchmark wanted to be conducted
    cores - optional argument to change the amount of cores parallel versions uses
