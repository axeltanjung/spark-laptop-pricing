## Business Cases

Supposed you working on Laptop Store, and you work as Data Engineer that should prepare data to the data warehouse. The Laptop Store has list of various laptop consists of:

1. Category.
The category to which the laptop belongs: This parameter is mapped to numerical
values in the following way:

Category - Assigned Value
Gaming - 1
Netbook - 2
Notebook - 3
Ultrabook - 4
Workstation - 5

2. GPU.
   
The manufacturer of the GPU. This parameter is mapped to numerical values in thefollowing way:

GPU - Assigned Value
AMD - 1
Intel - 2
NVidia - 3

3. OS.

The operating system type (Windows or Linux): This parameter is mapped to numerical values in the following way:

OS - Assigned Value
Windows - 1
Linux - 2

4. CPU_core.
The type of processor used in the laptop: This parameter is mapped to numerical
values in the following way:
CPU_core - Assigned Value
Intel Pentium i3 - 3
Intel Pentium i5 - 5
Intel Pentium i7 - 7

5. Screen_Size_cm.
The size of the laptop screen is recorded in cm.

6. CPU_frequency.
The frequency at which the CPU operates, in GHz.

7. RAM_GB.
The size of the RAM of the system in GB.

8. Storage_GB_SSD.
The size of the SSD storage in GB is installed in the laptop.

10. Weight_kg.
The weight of the laptop is in kgs.

12. Price.
The price of the laptop is in USD.

The jobs are:
1. You should download it manually from this source as csv file:
https://www.kaggle.com/datasets/huzdaria/laptop-pricing

4. Import and read it as Spark Native Dataframe
   
5. And answer this business questions:
   
a. How the average RAM GB per manufacturer ? which manufacturer has higher average RAM ?

b. Please calculate the average screen size per Screen Type, and order it by average from higher to lowest.

c. Please do profiling by manufacturer and screen type, which manufacturer has more IPS Panel product, Full HD product, and so on by counting the record by those two columns.

Assignment result: Please push code to Github repository and screen shoot the result of those 3 business questions.
