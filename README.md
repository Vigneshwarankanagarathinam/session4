How to solve Big Data Problem
1.Describe the characteristics of Big Data in detail.
The following are the characteristics of Big Data:
•	Volume
•	Variety
•	Velocity
•	Variability
(i)Volume – The name 'Big Data' itself is related to a size which is enormous. Size of data plays very crucial role in determining value out of data. Also, whether a particular data can actually be considered as a Big Data or not, is dependent upon volume of data. Hence, 'Volume' is one characteristic which needs to be considered while dealing with 'Big Data'.
(ii)Variety – The next aspect of 'Big Data' is its variety.
Variety refers to heterogeneous sources and the nature of data, both structured and unstructured. During earlier days, spreadsheets and databases were the only sources of data considered by most of the applications. Now days, data in the form of emails, photos, videos, monitoring devices, PDFs, audio, etc. is also being considered in the analysis applications. This variety of unstructured data poses certain issues for storage, mining and analyzing data.
(iii)Velocity – The term 'velocity' refers to the speed of generation of data. How fast the data is generated and processed to meet the demands, determines real potential in the data.
Big Data Velocity deals with the speed at which data flows in from sources like business processes, application logs, networks and social media sites, sensors, mobile devices, etc. The flow of data is massive and continuous.
(iv)Variability – This refers to the inconsistency which can be shown by the data at times, thus hampering the process of being able to handle and manage the data effectively.
(v) Veracity - The quality of captured data can vary greatly, affecting accurate analysis.

2. Explain the possible solutions to handle Big Data.
•	Scale Up: Increase the configuration of a single system, like disk capacity, RAM, data transfer speed, etc. Complex, costly, and a time consuming process.

•	Scale Out: Use multiple commodity (economical) machines and distribute load of storage/processing among them. Economical and quick to implement as it focuses on distribution of load. Instead of having a single system with 10 TB of storage and 80 GB of RAM, use 40 machines with 256 GB of storage and 2 GB of RAM.

3. Explain the differences between scaling up and scaling out.
(i)Scaling up: It refers to architecture that uses a fixed controller resource for all processing. Scaling capacity happens by adding storage shelves up to the maximum number permitted for that controller. In order to maintain high availability, such architectures typically use dual controllers. However, the majority of them act as “active-passive” which creates a situation whereby the array’s performance is limited by the performance of a single controller. It leads to waste of 50 percent resources under normal operations and the industry has really moved away from it.
          
(ii) Scaling out: It refers to architecture that doesn’t rely on a single controller and scales by adding processing power coupled with additional storage. It’s also important to remember that with scale-out, all architectures are not created equal. (Some vendors build a unified management that utilizes multiple, independent arrays and call it scale-out, which is, technically speaking, false.) In true scale-out architecture, the data and the metadata are distributed across all nodes and all SSDs in the system. Modern scale-out architectures also implement global deduplication across the entire data set.
