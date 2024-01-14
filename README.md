## Introduction

The objective of this project is to identify the key determinants of student success in the Massive Open Online Course (MOOC) titled "Cyber Security: Safety At Home, Online, and in Life," offered by Newcastle University through the FutureLearn platform. This study leverages raw data collected from seven different runs of the course, utilizing learning analytics techniques to uncover effective measures of student engagement. The insights derived from this analysis hold the potential to inform the course's learning design and facilitate intervention processes for at-risk students. These findings will benefit Newcastle University's course instructors and individuals running similar online courses, as they seek to enhance student engagement rates and improve student performance. Employing the CRISP-DM framework, this report presents the results of two iterative cycles of data mining, which will serve as a valuable resource for improving the course's effectiveness and promoting it in a manner that aligns with the needs of the target audience.

## Objective 

1. To find the patterns of student engagement with the course content. The goal is to identify hidden patterns or trends within the data that are not immediately apparent. The detailed examination aims to uncover patterns and trends in student learning, enabling the identification of successful teaching strategies and potential areas for improvement. By leveraging data-driven insights, the course analytics not only enhance the overall learning experience for students but also empower course designers and instructors to refine content, assessments, and interventions. The success is defined by the ability to unearth actionable knowledge and insights that can be translated into meaningful business strategies, improvements, or innovations.

2. To investigate the correlation between student interactions with course videos and their progression through steps. Additionally, aim is to explore how question performance contributes to overall engagement and identify patterns in specific content types (videos, questions) that significantly impact student dropout rates or sustained engagement. This refined focus aims to uncover nuanced insights into the influence of various learning materials on student engagement, guiding efforts to optimize course content and enhance the overall learning experience.

## Project Execution Steps

1. **Download/Fork/Clone the Project:**
   - Click (link_to_project) to download/fork/clone the project repository.
   - Ensure all data files are placed in the `./data/` directory within the project folder. If not, unzip the provided project folder containing all the necessary data.

2. **Open RStudio:**
   - Launch RStudio on your local machine.

3. **Set Working Directory:**
   - Use the `setwd()` command in RStudio's console to set the working directory to the project's location:
     ```R
     setwd("path/where/you/downloaded/the/project/file")
     ```
   - Alternatively, in RStudio's top menu bar:
     - Go to `Session`.
     - Select `Set Working Directory`.
     - Choose `Choose Directory` and navigate to the project folder.

4. **Open Project and Navigate to Report File:**
   - Open the project folder in RStudio.

5. **Access Report File:**
   - Navigate to `./reports/230595217_Analysis_Report.Rmd` within the project directory.

6. **Install the following libraries:**
   - ProjectTemplate, ggplot2, tidyverse, ggpubr, RColorBrewer, GGally.
   
7. **Generate Report:**
   - Click on `Knit` in RStudio, located within the report file.
   - This action will execute all data munging and analysis processes defined in the report script and generate the output report in PDF format.
   
   
## Project Structure

1. **Data Files:**
   - Raw Data files for the project can be found in the `./data/`
   
2. **Preprocessing Files:**
   - File where data is cleaned, formatted and created is `./munge/01-A.R`
   
3. **Reports:**
   - `./reports/`folder contains the Analysis report in pdf and Rmd format. Project can be loaded from this file.
   - Reflective summary can be accessed from this folder
   
4. **Cache:**
   - `./cache/`folder contains the cached preprocessed data.
   
5. **Git Log:**
   - `./logs/`folder contains the GitLog.txt file.
   


