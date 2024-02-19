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
![business_case_a](https://github.com/axeltanjung/spark-laptop-pricing/assets/87402782/0f31c4fb-765a-4fb5-bed1-9c35b9e7eaf3)

b. Please calculate the average screen size per Screen Type, and order it by average from higher to lowest.
![business_case_b](https://github.com/axeltanjung/spark-laptop-pricing/assets/87402782/2457f552-f059-4d68-a388-40ca4e9d9051)

c. Please do profiling by manufacturer and screen type, which manufacturer has more IPS Panel product, Full HD product, and so on by counting the record by those two columns.
![business_case_c](https://github.com/axeltanjung/spark-laptop-pricing/assets/87402782/570da860-b581-4a74-bd5d-2592e09e1ad9)

Assignment result: Please push code to Github repository and screen shoot the result of those 3 business questions.
