## Background
This is a summative final group project (during 23/24 Academic Year) for the course [ST115 Managing and Visualizing Data](https://www.lse.ac.uk/resources/calendar2023-2024/courseGuides/ST/2023_ST115.htm), a Statistics department module that focuses on manipulation and visualization of data mainly using Python, at [LSE](https://www.lse.ac.uk).

The project finally obtained a First Class grade, which is the highest grade under the British Higher Education Grading Classification System. For those who may be interested in enrolling in  **ST115 Managing and Visualizing Data** or are already in the process of completing the project for the module, it can be a helpful reference.

## Project Introduction
The project aims to provide insights into LSE research productivity across departments and discover the potential causes of the productivity differences. From data acquisition, data cleaning & manipulation, data exploration & modeling, to final data visualization presenting the findings, our team follows a systematic lifecycle of a data analysis project.

#### FILES
Follow along [Analysis of Research Productivity at LSE.ipynb](docs/Analysis of Research Productivity at LSE.ipynb) as the main file; this a reproducible file. There are also two separate Data Acquisition reproducible `ipynb` files we created to obtain related data (note that the webpages and info can change overtime leading to potential problems when reproducing). The `Data` folder stores the data we obtained and used at that time. For project submission purposes, there is also the `html` file [(Final HTML Report) Analysis of Research Productivity at LSE.html](docs/(Final HTML Report) Analysis of Research Productivity at LSE.html) that can be viewed and downloaded in the local devices more conveniently.

#### Data Acquisition
The data acquisition section consists of two separate subsections, as there are two different data sources and formats. For the first part of the data acquisition `Data Acquisition - Departmental Staff Data via Webscraping.ipynb`, we webscraped the departmental sites to obtain the departmental staff information mainly using requests and BeautifulSoup and doing string manipulation. As for the other part of the data acquisition obtaining data on institution publications `Data Acquisition - Publications per Department via JSON.ipynb`, we used Python json library to obtain the necessary information.

#### Data Cleaning & Manipulation
After some basic cleaning of the data obtained using Python pandas, we stored the data into a database using sqlite3 library and sql magic. With the database created, we were able to retrieve, aggregate, and manipulate data more efficiently.

#### Data Exploration & Modeling
By simple preliminary data visualizations and exploration, we were able to gain some insights taking advantage of matplotlib, seaborn, and plotly.

#### Data Visualizations & Findings
Finally, our group presented the findings along with data visualizations. We also discussed certain limitations and further improvements assocaited with our report.

Lastly, hope you'll enjoy reading our project;)

