
# Team Name: Team A
|Name             |Student ID| Email                    |
|------------------|----------|--------------------------|
|Anusha Mannepalli|	40053915|	Anushamannepalli09@gmail.com|
|Manjusha Karanam|	40056880|	karanammanjusha@gmail.com|
|Vinita Singh	|40050131	|Vinita.singh1319@gmail.com|
|Tanya Sharma|	40046751	|Tanyasharma16@gmail.com|

## Requirements for running the script:
We need following libraries:
- Apache Maven Library
- Jdk 1.8 and compatible jdks
- Eclipse luna
-	PITest Maven plugin
-	Jacoco Maven plugin
-	Junit 4 or higher
- Metrics plugin
-	EclEmma plugin

## File Structure:

- **Correlation**: 
   This folder contains excel files used for calculating correlation between different metrics for each project.
- **commands_used_to_run_tools**: 
   This folder contains commands used to run tools to find metrics for each project.
- **configuration_for_mutationtesting**:
   This folder contains changes made to pom.xml in order to collect mutation score for each project using PITest plugin.
- **configurationforcodecoverage**:
   This folder contains changes made to pom.xml in order to collect code coverage for each project and cyclomatic complexity.
- **mutation_data**:
   This folder contains csv files which have raw data of mutation score for each project.
- **statement&branchcoverage_data**:
   This folder contains csv files which have raw data of code coverage and raw data of cyclomatic complexity for each project.
- **processed_data**:
    This folder contains excel files which has aggregated information of the metrics to be analyzed.
