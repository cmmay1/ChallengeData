## READ ME ##

The Challenge data for Catherine M. May is located on Github at:
https://github.com/cmmay1/ChallengeData

The folder includes my R Studio script and HMTL analysis file. 
The HMTL file includes embedded graphs and data output. 
The .RMD file contains all the R code. 

In addition to R, I used bash and perl scripts to annovate the variants from the Challenge_Data1(1).vcf file and these are located in the scripts.zip file. 

The results.zip file contains the .csv files for each type of variant annotation. 

The data.zip folder contains primary data, such as the annovar variant annotation file, myanno_data1.hg19_multianno.csv, which was used for much of the downstream analysis. 

As a side note, I did not have pre-existing code to work with .vcf files, as this was a novel assignment for me. Thus, much of the code is bloated and could certainly be streamlined for efficiency. I did, however, intentionally write less compact code to improve readability and to show my thought process a little more. Should I have the opportunity to improve the code in the future, there are many things on my list to fix. 

As a second side note, I also experienced issues with library versions and attempted many different work-arounds to install libraries for both R v3.6.3 and R v4.0, yet could not get the annovarR to work properly. For this reason, I ran annovar perl scripts in Linux instead to generate the databases and the myanno_data1.hg19_multianno.csv variant annotation file. 

Thank you for the challenge and I look forward to hearing from you. 

Catherine M. May