# Wuxiaworld-Scrapper
A Wuxiaworld Scrapper I created using Requests and BeautifulSoup to create .txt files of each chapter for the use in text to speech programs. This Scrapper is able to scrape any book on wuxiaworld.com and allows or chapter updates on series you already have downloaded. This program is inteded to be used in conjunction with my NovelMerger program which sorts and creates 1 text file for a given series. 

Notes:
  There is a 1 second delay on this scrapper.
  Do not redistribute the files created by this program.
  
Tutorial:
When using this script you will be given the options to 1) Update chapters or 2) Add a new book to index.

In option 1 (recomended) The script will check the WuxiaIndex.txt file for the books you want to scrape. 
    Be sure to have the WuxiaIndex.txt file in your working directory along with the WuxiaScrapper.py file. 
    The WuxiaIndex.txt file should contain your selected stories table of contents in each line (see provided file for examples)
    The default output creates a new folder called Novels in the Users OneDrive/Documents, This can be changed manually on line 47.

In option 2: The script will request that you link the table of contents of your choice story. This option is mainly used for debuging individual stories.


BUGS:
- While Scrapping Archfiend on Wuxiaworld program crashes.
(contact me if any is found)


FUTURE WORK:
-scrape other websites
-create a unifide hub for all web scrappers I create

