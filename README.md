# Stats_141XP
This project is for Dr. Rootman as part of UCLA's Stats 141XP.

The people who worked on this project are: <br/>
<a href="https://github.com/alee5719">Anna Lee</a> <br/>
<a href="https://github.com/sqliang99">Shiqi Liang</a> <br/>
Yongpeng Luo <br/>
<a href="https://github.com/mattesmaili">Matthew Mallory</a> <br/>
Sungho Moon <br/>
Daniel Wray <br/>

## File Descriptions

### Clean Data: Use this for future projects
<a href="https://github.com/sqliang99/Stats_141XP/blob/main/Joined7_NonsenseRemoved.csv">Joined7_NonsenseRemoved.csv</a> <br/>
CSV file for clean data where nonsense values are removed. See final report for details

<a href="https://github.com/sqliang99/Stats_141XP/blob/main/Joined7_NonsenseReplaced.csv">Joined7_NonsenseReplaced.csv</a> <br/>
CSV file for clean data where nonsense values are replaced. See final report for details

### Codebook
<a href="https://github.com/sqliang99/Stats_141XP/blob/main/codebook.csv">codebook.csv</a> <br/>
Codebook for final data set including descriptions of all variables

### Data Reading
<a href="https://github.com/sqliang99/Stats_141XP/blob/main/Data_Reading_2017.Rmd">Data_Reading_2017</a> <br/>
Used to process ASCII file into csv for year 2017. Returns 3 files: 2017 Core, 2017 Hospital and 2017 Severity <br/>

<a href="https://github.com/sqliang99/Stats_141XP/blob/main/Data_Reading_2018.Rmd">Data_Reading_2018</a> <br/>
Same as above but for year 2018.<br/>

<a href="https://github.com/sqliang99/Stats_141XP/blob/main/Data_Reading_2019.Rmd">Data_Reading_2017</a> <br/>
Same as above but for year 2019 <br/>

### Data Filtering
<a href="https://github.com/sqliang99/Stats_141XP/blob/main/finalproj1.Rmd">finalproj1.Rmd</a> <br/>
Filters the 3 core files to only keep patients of interest, outputs a single csv file <br/>

<a href="https://github.com/sqliang99/Stats_141XP/blob/main/filter.Rmd">filter.Rmd</a> <br/>
Uses the dataset that only includes patients of interest, filters to only include columns of interest fron the core files and joins them with columns of interest from hospital files <br/>

<a href="https://github.com/sqliang99/Stats_141XP/blob/main/filter2.Rmd">filter2.Rmd</a> <br/>
Uses the dataset that only includes patients of interest, includes all columns from core files and joins them with columns of interest from hospital files <br/>

### Data Cleaning & New Variables
<a href="https://github.com/sqliang99/Stats_141XP/blob/main/finalproj2.Rmd">finalproj2.Rmd</a> <br/>
Computes comorbidity scores from the comorbidity package

### EDA
<a href="https://github.com/sqliang99/Stats_141XP/blob/main/finalproj3.Rmd">finalproj3.Rmd</a> <br/>
Basic EDA <br/>

### Modeling
