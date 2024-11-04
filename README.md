# Changing-PDF-File-Names-Automatically
This project aims to automatically change PDF file names in a folder based on the dates of each file.

News data collection process can require their classification based on their dates. However, when downloading these files, they generally contain only news titles. This project aims to lighten the workload of data collectors by automatically changing these file names based on the dates of each file. Thus, data collectors can save time by not having to manually change these file names by looking again at each news they have already collected.

News dates are usually located after the news titles. In this project, the format of the dates is as month-day-year (e.g., “April 20, 1931”). Firstly, I transferred all the text of these PDF files into a separate column in a CSV and specified the date pattern. Secondly, I extracted this date format in a separate column and then changed it to a desired format like “04-20-1931”. After that, I added these dates to the beginning of each file name, which had only news titles before, like “PeaceAtHomePeaceIntheWorld.pdf” now it is “04201931_ PeaceAtHomePeaceIntheWorld.pdf” Final and the most important step, after setting the working directory,  I changed all old file names in my folder automatically to the new ones having their dates at the beginning.

