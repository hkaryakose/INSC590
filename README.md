# INSC590
INSC590-OSF Project -
Reproducible README:
This README.md file was generated on 2020-04-09 by Hannah C. Gunderman (ORCID: orcid.org/0000-0002-7710-7055).

DOI

GENERAL INFORMATION
1. Title of Dataset: 2012_ComprehensiveGratefulDeadBusinesses.csv

2. Author Information

Name: Hannah Gunderman  
Institution: Carnegie Mellon University
Address: 4909 Frew Street, Pittsburgh, PA 15213
Email: hgunderm@andrew.cmu.edu
Phone Number: 865-973-9543
DATA & FILE OVERVIEW
Directory of Files:
Filename: 2012_ComprehensiveGratefulDeadBusinesses.csv

Short description: This dataset was collected by Hannah Gunderman in 2012 and lists all confirmed and suspected businesses named after the Grateful Dead in the United States.

Additional Notes on File Relationships, Context, or Content
(for example, if a user wants to reuse and/or cite your data, what information would you want them to know?):

The data was pulled from Whitepages.com using a pre-defined list of search terms related to the Grateful Dead. It must be noted this is not an exhaustive list of Grateful Dead-named businesses in the United States, and many of these businesses may have closed since 2012. Any reuse of this data should include this caveat in the analysis and write-up.

File Naming Convention: yearofdatacollection_datasettheme.csv

DATA DESCRIPTION FOR: [2012_ComprehensiveGratefulDeadBusinesses.csv]
1. Number of variables: 10

2. Number of cases/rows: 254 rows (unique business names)

3. Missing data codes: In this dataset, there are technically no missing data. Blank cells in the CSV signify that the address for that business does not contain a certain element, such as a prefix (North, South, etc.).

4. Variable List

A. Name: Business Name
   Description: The exact name of the business that is named after the Grateful Dead (confirmed or presumed) as shown on  	     whitepages.com. Field accepts text and numeric characters. 

B. Name: Street Number
   Description: The street number of the business. Field accepts text and numeric characters (in the case of basement 	 businesses with values such as "110A."

C. Name: Prefix
   Description: Directional prefixes for the business address location. Field accepts text and numeric characters (in the     	 case of prefixes that are additional numbers, common in more urban areas). 

D. Name: Street Name
   Description: The name of the street that the business is located on. Field accepts text and numeric characters.

E. Name: Street Suffix
   Description: Additional suffix for the business location. Field accepts text and numeric characters. 

F. Name: Suite Number
   Description: If applicable, a suite number for the business location. Field accepts text and numeric characters. 

G. Name: City
   Description: The city that the business is located in. Field accepts text characters only. 

H. Name: State
   Description: The state that the business is located in. Field accepts text characters only, and must be written in the 	     postal code format. 

I. Name: Zip Code
   Description: The zip code corresponding to the business location. Field accepts 5-digit numeric characters only. 

J. Name: Term
   Description: The search term used to locate the business. Field accepts text characters only, and values must come 	 from the following list: The Grateful Dead, Steal Your Face, Terrapin Station, Shakedown Street, Uncle John’s Band, 	    Jerry Garcia, Dancing Bears, Mexicali Blues, Stella Blue, Touch of Grey, St. Stephen, Friend of the Devil, Dark Star,   	   and China Cat Sunflower.
METHODOLOGICAL INFORMATION
1. Software-specific information:

Name: Microsoft Office - Excel
Version: Windows 7
System Requirements: Windows or Apple computer
Open Source? (Y/N): N

Additional Notes:

Although the dataset was generated in Excel, I have uploaded a CSV version of this file which can be viewed and analyzed on any operating system, including Linux.

2. Equipment-specific information (on what system were the data collected?):

Manufacturer: Dell
Model: E6420

3. Date of data collection: 20120101 - 20120130

4. Reproducibility Notes: To recreate this dataset, you must use whitepages.com and enter each of the search terms from the above list of search terms in "4. Variable List" for all 50 states to determine if a business was named after the reference to the band. For all of the search terms, you must enter three variations of the term: (1) the full search term (ex. “The Grateful Dead”), (2) the beginning of the search term (ex. “The Grateful”), and (3) the end of the search term (ex. “Dead”). This is necessary because few businesses had names that were verbatim parallels of the search terms, and many were “play on word” variations of the search terms. For example, a business called “The Grateful Bread” would not show up in the results if I had entered “The Grateful Dead” into the search function, but it would show up if “The Grateful” was entered. It must be noted that this dataset may not be able to be 100% recreated, due to certain businesses closing and changes in the whitepages.com interface and search algorithms. The accuracy of this data can only be ensured as of January 2012.
