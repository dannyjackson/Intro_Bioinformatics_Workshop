# Data Storage and Backup Strategies

## Goals of this module
1. Assess the effectiveness of our current data backup strategies.
2. Develop a plan to improve our data backup processes.
3. Utilize the FAIR Principles framework to create a structured approach for writing metadata files.

Whether we're working with data we've collected in the field, data we've collated from online sources, or large genomic datasets that we received through a sequencing company, backing up our data immediately and routinely is essential to secure the success of our projects. Inadvertent data degradation or loss can tank a project. We can avert data disasters by following the "3-2-1" rule for data backup. 

For all data generated in our lab, we need to maintain:
   - 3 copies
   - 2 media types
   - 1 offsite copy

## Data Storage
For my genomics projects, I store the data in three places: 2 in the cloud (the HPC and the Sequence Read Archive) and 1 local location (an SSD external hard drive). Work through the following question to evaluate the backup status of your own datafiles.

1.	Consider the project that you described in the Walk-In activity. Where is your data stored? Do your storage solutions meet the 3-2-1 rule? 

 - If not, write down which data products require additional backups and where you plan to back them up to. Then, schedule a time in your calendar to complete this task within the next week. 

 - Downloads of big data to external hard drives can take many hours, so prepare to either run it overnight or during an extended period where your computer can sit plugged in and connected to the SSD. If you require an SSD for your project, talk to your PI and make a plan.

*Note: these [tutorials](https://hpcdocs.hpc.arizona.edu/storage_and_transfers/transfers/overview/) for how to transfer data from the HPC to another storage device may be useful!*

## Metadata
Metadata files are a major component of every dataset, but they are often overlooked until we prepare our datasets for publication. Unpublished data quickly becomes unusable by others if the owner of that data never develops a metadata file, or even by the owner themself if they intend to return to the project in the future. Metadata files should be developed early and stored with our data alongside each backup.

When thinking about how to publish our datasets and write our metadata, we can keep the [FAIR principles](https://www.nature.com/articles/sdata201618) in mind. Our data should be:
   - Findable
   - Accessible
   - Interoperable 
   - Reusable

Metadata makes datasets accessible, interoperable, and reusable. Read through the [example metadata file](https://github/dannyjackson/BioinformaticsWorkshop/ExampleMetadataFile.md) for more information on what data can be included in a metadata file. Then, respond to the following check-in question.

2.	Is there a metadata file for your dataset? 
3. How do the FAIR principles apply to your dataset? Which of these principles does your dataset already meet, and which ones require more effort?
4. What improvements can you make based on the example metadata file?
5. Make a plan to either create or to revise your metadata file. Schedule a 30 minute block in the next week to complete this task. Where will you store it, and how will you ensure it is included in every backup?


Next: [2_HPCTutorial.md](https://github.com/dannyjackson/BioinformaticsWorkshop/blob/main/2_HPCTutorial.md).

**Relevant xkcd:**

![xkcd data trap](https://imgs.xkcd.com/comics/data_trap.png)

*Title text: It's important to make sure your analysis destroys as much data as it produces.*