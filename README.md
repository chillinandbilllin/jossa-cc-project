
# JOSAA Seat Allotment Portal

This project aims to create a portal to explore the seat allotment statistics of the Joint Seat Allocation Authority (JOSAA) until 2022. The portal allows users to analyze the data and provides insights and visualizations based on the JOSAA seat allotment data from 2016 to 2021 and 2022. The following are the key goals and technologies used in this project.
## Tech Stack/Frameworks
- Frontend: HTML, CSS, JavaScript
- Backend: Django, SQLite
- Data Scraping: Selenium
- Data Cleaning: NumPy, Pandas
- Visualization: Chart.js

## Usage
To run the JOSAA Seat Allotment Portal locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/josaa-portal.git`
2. Change to the project directory: `cd josaa-portal`
3. Install the required Python packages: `pip install -r requirements.txt`
4. Run database migrations: `python manage.py migrate`
5. Start the development server: `python manage.py runserver`
6. Access the portal in your web browser at `http://localhost:8000/`

## Data Extraction and Cleaning
 The data cleaning process involves using the NumPy and Pandas libraries to clean and transform the data as required for analysis.

## Data Analysis and Insights
The cleaned data is stored in a SQLite database. The website's "Insights" page presents various charts and tables generated using Chart.js, providing users with visualizations and insights based on the data.

## Final Output
When we run this project on our local servers we mainly get 4 sections to analyze the data based on various trends.
1) Analyse trends based on year :
2) Analyse trends based on Round :
3) Best institute for coursed :
4) Know your IIT : 




