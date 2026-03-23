# Visualizing Student Productivity and Distraction through Demographic and Academic Variables

### Description
This folder has the final report, information, and plots related to this python data visualization project. Throughout this report, skills used include python data cleaning, wrangling, manipulations, and visualizations. The packages used in this personal project were `pandas`, `matplotlib`, and `seaborn`. The dataset used, *Student Productivity & Digital Distraction Dataset*, was sourced from Kaggle and was created by Preet (2026). 

### Data Source and Information
- **Title**: *Student Productivity & Digital Distraction Dataset*
- **License**: CC0: Public Domain
- **Creator**: Mansehaj Preet (2026)
- **Citation**: Preet, M. 2026. *Student Productivity & Digital Distraction Dataset*. [Dataset]. Kaggle. https://www.kaggle.com/datasets/sehaj1104/student-productivity-and-digital-distraction-dataset/data.

### Project Files

### Python Packages
- `pandas`
- `matplotlib`
- `seaborn`

### Methods
- Load the packages above necessary for analysis
- Read in the dataset, *student_productivity_distraction_dataset_20000.csv*
- Identify the format of the data and the data types of the columns
- Clean the dataset to remove NA values and duplicates
- Derive summary statistics
- Identify trends by comparing variables through data manipulations
- Re-format the data frame to long format for visualizations
- Use python visualization packages to create several plots to present overall trends within the data

### Summary
*  On average, `productivity_score` has a negative association with increased `phone_usage_hours`
*  On average, `productivity_score` has a positive association with increased `study_hours_per_day`
*  On average, `productivity_score` has a positive associaton with `attendance_percentage`
*  Increased `stress_level` leads to decreased `productivity_score` among students.
*  Students spend the most time distracted by `social_media_hours` amongst `youtube_hours` and `gaming_hours`
*  On average, `sleep_hours` has a strong, positive association with `productivity_score`
