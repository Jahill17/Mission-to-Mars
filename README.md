# Mission-to-Mars
HTML Web scraping activity on Mars data to create Flask web app using Python and MongoDB.

## Overview
The ultimate goal is to adjust the current web app to include all four of the hemisphere images. To do this requires the use of BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

## Software Used
- MongoDB
- PyMongo
- Python
- Jupyter Notebook
- VS Code
- Pandas
- Beatifulsoup
- Splinter
- ChromeDriverManager
- Flask
- Bootstrap 3

## Summary / Results
See the screenshots below in addition to the referenced scraping.py, app.py, and index.html files.

- Below is the mission to mars scraping page as a result of the final challenge code.  The final code resulted in a fully-functional web application that used Flask and included images, a table with information about Earth and Mars, a recent article title, and a description that is scraped from the NASA's website. Whenever the "Scrape New Data" button is clicked, new information will be updated on the website and within MongoDB. Within the terminal the scrape includes a news_title with a brief explanation (news_paragraph), a featured_image, a table HTML that is stored in facts, and four picture thumbnails of mars hemispheres (hemispheres) with their titles.

![This is an image](https://github.com/Jahill17/Mission-to-Mars/blob/main/Images/mission_to_mars_website.png)

- Below is the matching MongoDB screenshot the reflects the data shown after clicking "Scrape New Data".

![This is an image](https://github.com/Jahill17/Mission-to-Mars/blob/main/Images/mars_app_mongo_db.png)

- Below is the dataframe for findings:

![This is an image](https://github.com/Jahill17/Mission-to-Mars/blob/main/Images/dataframe_for_findings.png)


- Below is the dictionary list of each image url and title

![This is an image](https://github.com/Jahill17/Mission-to-Mars/blob/main/Images/dictionary_list_image_urls.png)


- Below is the Mars facts dataframe

![This is an image](https://github.com/Jahill17/Mission-to-Mars/blob/main/Images/mars_facts_dataframe.png)


## Code Used
- HTML script: [index.html](https://github.com/Jahill17/Mission-to-Mars/blob/main/templates/index.html)
- Scraping script located within templates: [scraping.py](https://github.com/Jahill17/Mission-to-Mars/blob/main/scraping.py)
- App script: [app.py](https://github.com/Jahill17/Mission-to-Mars/blob/main/app.py)
