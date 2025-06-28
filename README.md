# PROJECT : Power BI Data Analysis Beginner class

## COURSE OUTLINE

### Introduction to Microsoft Power BI
### Power Query Editor for Data transformation (ETL) I
### Power Query Editor for Data Transformation (ETL) II
### Power Query Editor for Data Transformation (ETL) III
### Data Modelling and Relationships in Power BI
### Data Functions and Data Visualizations I
### Data Functions and Data Visualizations II

## DAY ONE (29 - 05 - 2025)

### Introduction to Microsoft Power BI 

Today, classes began on the use of Microsoft Power BI for analysis. One of the four power tools is Power BI. Others are : 

- Power Apps
- Power Automate
- Power Virtual agents

**Power BI (Business Intelligence)**

Power BI is a data visualization and business intelligence tool that converts data from different data sources to interactive dashboards and BI reports. It is a collection of software services, apps and connectors that work together to turn unrelated sources of data into coherent, virtually immersive and interactive insights. 

The collection of software services are :

- Power BI Desktop : a software application for building reports.
- Power Bi Service : a software as a service (SAAS) application, it requires an enterprise account that runs on subscription. It stores reports created on the desktop in the cloud and makes it public for interaction and collaboration.
- Power BI Mobile Apps : an application which can be accessed on mobile phones. Public users can view reports on the mobile app version of Power BI. It cannot be used for building reports.

Available data sources in Power BI

- Flat files.
- SQL database.
- OData feed.
- Blank query.
- Azure cloud platform.
- Online services.
- Other data sources such as Hadoop, Exchange, or ACtive directory.

Other Business intelligence are Tableau and SSRS.

**Power BI steps for Visualization**

- Step 1 : Define questions & goals.
- Step 2 : Collect data (Data ingestion)
- Step 3 : Data wrangling (Data cleaning and transformation).
- Step 4 : Determine analysis.
- Step 5 : interpret results.

**Power BI Desktop interface**

There are four views on the Power BI desktop interface. They are :

- Report view.
- Table view.
- Model view.
- Dax query view.

**ETL in Power BI**

E : Extract 

T : Transform

L : Load

Before loading any data into the Power BI environment, it must first be transformed and cleaned for easy analysis. Transformation in Power BI is done in the "Power Query Editor".

The ultimate goal of transformation is to remove unwanted data that may affect interpretation of data.

**Power Query Editor**

The power query editor can be accessed on the "home" tab under the "query" group. Every applied steps is seen on the query settings pane at the far right of the power query editor.

Data preview options on the "View" tab power query editor helps to ascertain certain properties about the Data. The data preview options are :

- Column quality : Helps to check valid data and percentage error.
- Column distribution : Shows the distinct data entities in our column. The distribution of the data based on the information given.
- Column profile : Shows the statistics of an entire column. 

**Note** : Tableau can connect much larger datasets as compared to Power BI which only has a limit of 1 Gb data in free version. You can use the preview features in the options and settings to edit the architecture of the Power BI interface. Reports are built on the "Canvas" in the report view.

## DAY TWO (02 - 06 - 2025)

### Power Query Editor for Data transformation (ETL) I

Today, we delved fully into transformation of data in the power query editor. 

We carried out the following operations;  

- Changing of Data Types.
- Transposing of tables.
- Use of filled down.
- Use of promoted headers.
- Renaming of columns.
- Use of Pivot and Unpivot columns.
- Replace values.

**How to manually create tables and enter data**

Power Bi can also be used to create tables instead of importing tables using the "Enter data" option in the home tab.

**File for the class** : [Download here](https://github.com/user-attachments/files/20961989/Columnar.Data.xlsx)

**Note** : All of these operations are done through the transform tab. 

## DAY THREE (04 - 06 -2025)

### Power Query Editor for Data Transformation (ETL) II

Today, the journey into transformation using power query editor continued. 

The following operations were carried out;

- Removal of unwanted columns.
- Trim and clean
  - Trim : removes unwanted spaces outside texts.
  - Clean : removes unneccessary spaces within texts.
- Replace multiple spaces with single space.
- Capitalize each words.
- Split columns by space delimiter.
- Add columns
    - Use of conditional columns (IF statement).
    - Use of custom columns.
    - Insert Date(Age).
    - Insert Duration(Total years)
    - Insert Round down.
- Reordering columns.

File for the class : [Download here](https://github.com/user-attachments/files/20962326/Trim.and.Clean.csv)

**Note** : There is no way to have a clean analysis without Data cleaning. The maximum number of data that can be allowed for transformation in the power query editor is 1000 rows.

## DAY FOUR (05 - 06 - 2025)

### Power Query Editor for Data Transformation (ETL) III

Today, we moved on with transformation of data using power query editor.

The following operations were carried out;

- Appending and merging of columns
    - Append : Increases the no of rows on a table (similar with union in SQL).
    - Merge : Increases the no of columns on a table (similar with join in SQL).
 - Grouping of data (Data summarization using "Group by").

Files for Appending and Grouping : 
- [Download Manchester data here](https://github.com/user-attachments/files/20962860/Manchester.csv)
- [Download Liverpool data here](https://github.com/user-attachments/files/20962866/Liverpool.csv)
- [Download Leeds data here](https://github.com/user-attachments/files/20962880/Leeds.csv)

Files for Merging :
- [Download Personal information data here](https://github.com/user-attachments/files/20962891/Personal.xlsx)
- [Download General Contacts data here](https://github.com/user-attachments/files/20962893/All.Patient.Data.xlsx)

**Note** : To use the appending function, the tables must have the same no of columns, column headers and data types. Also, to use the merging function, there must be a column on the two tables that contain the same information which can be seen as a primary key.  

## DAY FIVE (09 - 06 - 2025)

### Data Modelling and Relationships in Power BI

Today, we moved into Data modelling and relationships between data sets.

Primary key is a unique identifier used to define the data or information in every tables.

**Jireh_Academy_Demo_DB login details**

Server : 206.217.202.58,25000

User Name : Student

Password : JirehGoodTraining@1

Database Name : Jireh_Academy_Demo_DB

**Import the following data sets** 
- Actor.
- Country.
- Date table.
- Director.
- Film.
- Genre.
- Language.
- Role.
- Studio.

**Four Cardinality in Data modelling**
- One to Many
- Many to One.
- Many to Many.
- One to One.

**Fact tables and Dimension tables**

The Facts table shows the general information of the database, it shows the measure of the relationship that exists between the different table.

The Dimension table is a special table narrowed down to the information of emphasis.

**Note** : When you import data from database, you are bringing it into the power Bi environment whereas a direct query access to the database leaves the data in the cloud, however, no operations can be carried out on the table in the cloud. Do not overload yoyr model with unneccessary data that are not needed for analysis.

## DAY SIX (11 - 06 - 2025)

### Data Functions and Data Visualizations I

Today, we took a dive into visualizations and building dashboards using Power BI. 

**Dashboards**

Dashboards are pictorial representation and visualizations of insights gotten from data. Every visualization is done on the canvas in the report view. 

Different charts or illustrations can be used for visualization. A few of them are ; Barchart, Starked barchart, Column barchart, Funnel chart, Scatter chart, Piechart, Doenut chart, table, matrix, map, card, slicer and so on.

There are three panes that are pinned on the far right of the report view interface used to edit and manipulate visualizations on the canvas. They are;
- Data pane.
- Visualization pane.
- Format pane.

The map data in the file gives information about population census while the HR data talks about the attrition of an organization and the reason why employees leaves.

File for the class : [Download HR data here]

**Note** : To enable enable Map and filled Map visuals use the security settings in options and settings page. Any data point tagged with a summation sign contains a quantitative data. You can create a new measure on the data pane using the three dots icon at the far left of the data sets.

## DAY SEVEN (13 - 06 - 2025)

### Data Functions and Data Visualizations II

Finally, we concluded the dashboard creation today. Find attached the file for the data visualization.




