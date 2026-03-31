# CIVE202---Project-3

## Project Description
Understanding traffic behavior and travel patterns is essential for improving transportation systems and informing effective planning decisions. This project utilizes data from the Federal Highway Administration using tools in Python. The goal is to integrate data analysis, visualization, and simulation to gain meaningful insights into transportation systems. By combining real-world datasets with computational modeling, this study highlights relationships between driver behavior, traffic flow, and transportation planning outcomes. Data from the National Household Travel Survey (NHTS) and the Next Generation Simulation (NGSIM) program to examine travel characteristics and traffic dynamics. In addition to exploratory data analysis and visualization, this study incorporates simulation techniques to better understand traffic flow behavior. The Intelligent Driver Model (IDM) is applied to represent vehicle-following dynamics under varying conditions.  


---
## Repository Structure

- [Project 3 Code](CIVE202_Spring2026_Group7_Project3_Code.ipynb)
- [NHTS Data](NHTS.csv)
- [NGSIM Data](NGSIM.csv)
- [Boxplot](boxplot.png)
- [Histogram](histo.png)
- [Position-time](positiontime.png)
- [Simulation](sim.png)
- [Speed-Time](speedtime.png)

---
## User Guide

### 1. Program Overview
This system automates the generation of five specific transportation-related visualizations and a mathematical simulation of car following behavior. The code is designed to provide the transportation planning group with a quick analysis of US travel trends. 


### 2. Execution Sequence
- Data Loading: Ensure both [NHTS Data](NHTS.csv) and [NGSIM Data](NGSIM.csv) are in the same directory as the [Project 3 Code](CIVE202_Spring2026_Group7_Project3_Code.ipynb)
- Visualization Generation:  Run the cells to generate the bar chart, histogram, and box plot based on the selected NHTS.csv
- Time-Series Analysis: Execute the trajectory analysis cells to view driving behavior over positiontime.png
- IDM Simulation: When prompted, the program will select a leader-follower pair from the NGSIM data to simulate acceleration and position using the Intelligent Driver Model. 

### 3. Methods
- All coding was done in a Jupyter notebook, and all methods were executed by Python functions and coding.
- At least one plot uses advanced Matplotlib or Seaborn features, including custom color palettes, font adjustments, and labeled legends to meet FHWA reporting standards. 
- The Intelligent Driver Model (IDM) was used to calculate the simulated acceleration of a following vehicle based on the instantaneous gap and velocity difference with the leader. 

---
## Project Goals
This project aims to simulate and analyze a transportation system utilizing data from the Federal Highway Administration using tools in Python. Data will be organized and interpreted to produce results that highlight aspects of transportation, like driver behavior. Along with the graphical analysis, a simulation will be conducted using an Intelligent Driver Model (IDM) to simulate vehicle behavior. All analysis will be done within a Jupyter Notebook, an annotated code document, a GitHub repository, an engineering timesheet, and a detailed technical report. Our progress is documented in the following charts: 

-[Individual Gantt Chart](CIVE202_Spring2026_Group7_Project3_IndividualGanttChart.xlsx):Log of hours spent by each engineer

-[Engineering Timesheet](CIVE202_Spring2026_Group7_Project3_Engineering_Timesheet.xlsx):Timeline of project activities


---
## Project Documentation
Links:
- [Scope of Work](CIVE202_Spring2026_Group7_Project3_SOW.docx)
- [ACD](CIVE202_Spring2026_Group7_Project3_ACD.docx)
- [Written Report](CIVE202_Spring2026_Group7_Project3_Report.docx)


