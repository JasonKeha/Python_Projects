# Amsterdam Housing (Web Scraping Python Project)
This is a Python Web Scraping Project, parsing Data related to renting a house in Amsterdam. The data was pulled from pararius, a website about renting houses in The Netherlands.
- original website link: https://www.pararius.com/apartments/amsterdam

### In this project I showcase my ability in:
- The Python Programming Language
- The bs4 library (Beautiful Soup)
- The csv library (writer)
- The os library
- Taking input from the user in all cases
- Scraping Data
- Understanding Data
- Transforming Data
- Categorizing Data
- Packing Data 

### What this Project does:
* This project scrapes data related to Amsterdam renting. It first checks to see if the file already exists. 
* If it does, it asks the user for permission to delete the file. If the user agrees, the file gets deleted. 
* Then it takes an input where the user can type in how many rent listings they want to be processed by the program. 
* After it runs and and processes all the rent listings from the first webpage, it then moves to the second webpage and repeats this process, until all the rent listings that the user asked for are fully processed.
* All the processed data are appended to a csv file after the headers are appended when the posting is equal to 1.
* You can check the resulting file appropriately named "Amsterdam_Housing.csv" for the results of 200 rent listings.
