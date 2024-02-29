
"""
The psutil.cpu_count(logical=True) function provides information about the number of logical CPUs in the system.
The logical core count is determined by multiplying the number of physical cores by the number of threads that can run on each core.
If there is no logical core, it simply reports the number of physical cores.
"""

import psutil

print("Total number of cores in system: ", psutil.cpu_count())

print("Number of logical cores in system: ", psutil.cpu_count(logical=True))


# Get the number of physical cores
num_physical_cores = psutil.cpu_count(logical=False)

print(f"Number of physical CPU cores: {num_physical_cores}")
