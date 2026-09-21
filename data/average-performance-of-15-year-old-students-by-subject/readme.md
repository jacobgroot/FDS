# Average performance of 15-year-old students by subject - Data package

This data package contains the data that powers the chart ["Average performance of 15-year-old students by subject"](https://ourworldindata.org/grapher/academic-performance?v=1&csvType=full&useColumnShortNames=false&subject=subject_side_by_side&sex=both) on the Our World in Data website.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV structure

Each row is an observation for an entity (usually a country or region) at a timepoint.

- "Entity" — the name of the entity, e.g. "United States".
- "Code" — our internal entity code. For most countries this is the [ISO alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code, e.g. "USA"; historical and other non-standard entities get a custom code.
- "Year" or "Day" — the timepoint. Annual data has a "Year" column holding an integer year; otherwise a "Day" column holds a date string in the form "YYYY-MM-DD".
- Every remaining column is a data column, each one a time series. Downloaded with the "full data" option each corresponds to one time series below; with "only selected data visible in the chart" they are transformed depending on the chart type, so the correspondence may be less direct.


## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc.

## How we process data at Our World in Data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stitch together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

Preparing this data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/).

## Detailed information about each time series


### PISA mathematics scores for all students
Assessed through the PISA mathematics scale, which measures how well someone can use math to solve everyday problems and understand the role of math in the real world.
Last updated: December 6, 2023  
Next expected update: October 2026  
Date range: 2003–2022  
Unit: score  
Source: OECD (2023) – with minor processing by Our World in Data  

#### How to cite this data

OECD (2023) – with minor processing by Our World in Data

#### What you should know about this data
- The Programme for International Student Assessment (PISA) is an international survey that assesses the skills and knowledge of 15-year-old students. It provides a snapshot of how well education systems around the world are preparing young people for adult life.
- PISA is run every three years and tests students in reading, mathematics, and science. It doesn't just assess what students know — it focuses on how well they can use this knowledge to solve problems they might encounter in the real world. For example, can they interpret a bus timetable, reason through a scientific scenario, or compare prices to make a budget?
- Each student sits a two-hour computer-based test. Results are summarized as average scores for each country, and are designed to be comparable over time.
- The scores are standardized to make comparisons easier: across OECD countries, the average score was set to 500 in the first year each subject was assessed (reading in 2000, mathematics in 2003, science in 2006). Most countries score somewhere between 300 and 600, although scores outside this range are possible.
- Higher scores indicate better performance — but comparing countries should be done carefully. Many factors affect student performance, including income, teacher quality, classroom time, and parental education. Cultural differences can also play a role in how students approach the test.
- PISA gives policymakers, researchers, and educators a way to evaluate their education systems and learn from others. But as with all such comparisons, it's important to consider the wider context behind the numbers.

#### How this data is described by its producers
Average score of 15-year-old students on the PISA mathematics scale. Initially, the average PISA score across subjects and all OECD countries was at 500 with a standard deviation of 100, so that most students scored between 400 and 600. Scores in later cycles were calibrated to remain comparable to this baseline.


### PISA science scores for all students
Assessed through the PISA science scale, which assesses how comfortable and knowledgeable someone is with science topics, focusing on their ability to discuss and think about scientific issues in everyday life.
Last updated: December 6, 2023  
Next expected update: October 2026  
Date range: 2006–2022  
Unit: score  
Source: OECD (2023) – with minor processing by Our World in Data  

#### How to cite this data

OECD (2023) – with minor processing by Our World in Data

#### What you should know about this data
- The Programme for International Student Assessment (PISA) is an international survey that assesses the skills and knowledge of 15-year-old students. It provides a snapshot of how well education systems around the world are preparing young people for adult life.
- PISA is run every three years and tests students in reading, mathematics, and science. It doesn't just assess what students know — it focuses on how well they can use this knowledge to solve problems they might encounter in the real world. For example, can they interpret a bus timetable, reason through a scientific scenario, or compare prices to make a budget?
- Each student sits a two-hour computer-based test. Results are summarized as average scores for each country, and are designed to be comparable over time.
- The scores are standardized to make comparisons easier: across OECD countries, the average score was set to 500 in the first year each subject was assessed (reading in 2000, mathematics in 2003, science in 2006). Most countries score somewhere between 300 and 600, although scores outside this range are possible.
- Higher scores indicate better performance — but comparing countries should be done carefully. Many factors affect student performance, including income, teacher quality, classroom time, and parental education. Cultural differences can also play a role in how students approach the test.
- PISA gives policymakers, researchers, and educators a way to evaluate their education systems and learn from others. But as with all such comparisons, it's important to consider the wider context behind the numbers.

#### How this data is described by its producers
Average score of 15-year-old students on the PISA science scale. Initially, the average PISA score across subjects and all OECD countries was at 500 with a standard deviation of 100, so that most students scored between 400 and 600. Scores in later cycles were calibrated to remain comparable to this baseline.


### PISA reading scores for all students
Assessed through the PISA reading scale, which measures how well someone can understand and use written information to learn new things and be a part of society.
Last updated: December 6, 2023  
Next expected update: October 2026  
Date range: 2000–2022  
Unit: score  
Source: OECD (2023) – with minor processing by Our World in Data  

#### How to cite this data

OECD (2023) – with minor processing by Our World in Data

#### What you should know about this data
- The Programme for International Student Assessment (PISA) is an international survey that assesses the skills and knowledge of 15-year-old students. It provides a snapshot of how well education systems around the world are preparing young people for adult life.
- PISA is run every three years and tests students in reading, mathematics, and science. It doesn't just assess what students know — it focuses on how well they can use this knowledge to solve problems they might encounter in the real world. For example, can they interpret a bus timetable, reason through a scientific scenario, or compare prices to make a budget?
- Each student sits a two-hour computer-based test. Results are summarized as average scores for each country, and are designed to be comparable over time.
- The scores are standardized to make comparisons easier: across OECD countries, the average score was set to 500 in the first year each subject was assessed (reading in 2000, mathematics in 2003, science in 2006). Most countries score somewhere between 300 and 600, although scores outside this range are possible.
- Higher scores indicate better performance — but comparing countries should be done carefully. Many factors affect student performance, including income, teacher quality, classroom time, and parental education. Cultural differences can also play a role in how students approach the test.
- PISA gives policymakers, researchers, and educators a way to evaluate their education systems and learn from others. But as with all such comparisons, it's important to consider the wider context behind the numbers.

#### How this data is described by its producers
Average score of 15-year-old students on the PISA reading scale. Initially, the average PISA score across subjects and all OECD countries was at 500 with a standard deviation of 100, so that most students scored between 400 and 600. Scores in later cycles were calibrated to remain comparable to this baseline.


## Sources

These are the sources behind the data in this package. Each time series above names the ones it draws on in its citation.

### OECD – PISA Database

The Programme for International Student Assessment (PISA) by OECD provides a comprehensive and rigorous international assessment of the knowledge and skills of 15-year-old students around the world. The assessment covers areas such as mathematics, science, and reading. PISA aims to provide comparable data that will enable countries to improve their education policies and outcomes. Data is collected every three years from a globally diverse cohort of students.

The dataset contains scores, demographic information, and various indicators related to education systems of participating countries.

Producer: OECD  
Published: 2023  
Retrieved on: 2023-12-06  
Retrieved from: https://www.oecd.org/pisa/data/  
License: CC BY 4.0 (https://www.oecd.org/termsandconditions)  

Citation: OECD Programme for International Student Assessment (PISA) (2023), https://www.oecd.org/pisa/data/, accessed on 6th December 2023.

    