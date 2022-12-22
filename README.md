# GSoC-2022-WebScraping_Analysis
## The code is used to get data from the [GSOC website](https://summerofcode.withgoogle.com/programs/2022/organizations) and decide our organisations using the most important features of 
* ### **tech stack**
* ### **tech topics**
* ### **number of people accepted**


### The main motivation behind this project was to sort data based on number of people accepted as there was no option to sort the organisations based on this parameter.
### The [organizations.csv](https://github.com/JebronLames32/GSoC-2022-WebScraping_Analysis/blob/main/organizations.csv) file contains all the data and can be downloaded and sorted according to one's needs

## Tools used
* ### BeautifulSoup to parse the html file and get the links of the organization GSoC pages. The [body.html](https://github.com/JebronLames32/GSoC-2022-WebScraping_Analysis/blob/main/body.html) file was manually added copying the body element of the html file by inspecting the page elements.(found this easier than getting content from the API request as done for individual organisation pages)
* ### https://curlconverter.com to generate the python code for one organisation using the cURL for the API request that was rendering the data.
* ### *"requests"* python library to get JSON format of the data.

selenium and urllib were unsuccessful to get the data inside the body tag as it has been rendered with Javascript and through new AJAX requests.

## Reading material that helped me in this project:
* ### [advanced-web-scraping-concepts](https://aris-pattakos.medium.com/advanced-web-scraping-concepts-to-help-you-get-unstuck-17c0203de7ab)
