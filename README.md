# Amazon Prime Video Data Analysis Dashboard
This repository contains an interactive Power BI dashboard for analyzing and visualizing content distribution, genre popularity, and user ratings on Amazon Prime Video.

## Project Overview
This project centers around an interactive Power BI dashboard designed to analyze and visualize various facets of content available on Amazon Prime Video. Utilizing a dataset sourced from Kaggle, the dashboard provides insights into content distribution across countries, genre popularity, user ratings, and more. Key visualizations include maps illustrating title distribution by country, charts depicting trends in movie and TV show releases over years, and detailed breakdowns of genres and ratings. By leveraging Power BI's capabilities, this dashboard not only enhances understanding of Amazon Prime Video's content landscape but also offers a user-friendly interface for exploring and interpreting data trends effectively.

## Steps Involved

### 1. Downloading the Dataset
- Visit Kaggle and search for the latest Amazon Prime Video dataset.
- Alternatively, you can download the dataset directly from this link: [Amazon Prime Movies and TV Shows Dataset.](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)
- Download the dataset to your local machine.

### 2. Importing Data into Power BI
- Open Power BI Desktop.
- Click on **Get Data** and select **CSV** to import the downloaded dataset.
- Load the dataset into Power BI.

### 3. Data Transformation
- Clean and preprocess the data as necessary:
  - Remove duplicates.
  - Handle missing values.
  - Format data types (e.g., dates, text).

### 4. Creating Visualizations

#### Horizontal Bar Chart for Ratings by Total Shows
- Go to the **Report** view.
- Select the **Stacked Bar Chart** visual from the Visualizations pane.
- Drag **Ratings** to the **Y-Axis** field.
- Drag **Show_ID** to the **X-Axis** field and set it to **Count**.

#### Bar Chart for Genres by Total Shows
- Go to the **Report** view.
- Select the **Stacked Bar Chart** visual from the Visualizations pane.
- Drag **Listed_In (Genres)** to the **Y-Axis** field.
- Drag **Show_ID** to the **X-Axis** field and set it to **Count**.

#### Filled Map for Total Shows by Country
- Go to the **Report** view.
- Select the **Filled Map** visual from the Visualizations pane.
- Drag **Country** to the **Location** field.
- Drag **Show_ID** to the **Tooltips** field and set it to **Count**.

#### Donut Chart for Movies and TV Shows
- Go to the **Report** view.
- Select the **Donut Chart** visual from the Visualizations pane.
- Drag **Type (Movies/TV Shows)** to the **Legend** field.
- Drag **Title** to the **Values** field and set it to **Count**.

#### Area Chart for Total Movies and TV Shows by Release Year
- Go to the **Report** view.
- Select the **Area Chart** visual from the Visualizations pane.
- Drag **Release Year** to the **Axis** field.
- Drag **Title** to the **Values** field and set it to **Count**.
- Drag **Type (Movies/TV Shows)** to the **Legend** field.

### Additional Visualizations
- **Total Count of Titles**: Display the total count of titles in a card visual.
- **Total Count of Genres**: Display the total count of genres in a card visual.
- **Total Count of Ratings**: Display the total count of ratings in a card visual.
- **Total Count of Directors**: Display the total count of directors in a card visual.
- **Start Date and End Date**: Display the range of dates covered by the dataset in card visuals.

### 5. Finalizing the Dashboard
- Arrange the visuals on the report canvas to create a cohesive and interactive dashboard.
- Add filters and slicers as needed to enhance interactivity.
- Format the visuals for better readability and presentation.
- Add the [Amazon Prime Video logo](https://github.com/Chandana-sree-moparthi/Amazon-Prime-Video-Data-Analysis-Dashboard/blob/main/Amazon_Prime_Power%20BI%20dashboard/Prime%20video%20logo.png) for branding.

### 6. Publishing the Dashboard
- Save your Power BI report.
- Publish the dashboard to the Power BI service for sharing and collaboration.

## Screenshot
![Dashboard Screenshot](Screenshots/dashboard-screenshot.png)

Above is a snapshot of the Power BI dashboard showcasing insights into content distribution, genre popularity, and user ratings on Amazon Prime Video. Explore interactive visualizations and trends to gain deeper understanding of the dataset.

## Conclusion
This dashboard provides insights into the content distribution, genre popularity, user ratings, and more for Amazon Prime Video's offerings. By following these steps, you can recreate this analysis and gain valuable insights from the dataset.


