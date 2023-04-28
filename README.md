# ESEM-2023-Mindfulness-Labpack

This repository contains the lab pack of the article '*Cultivating mindfulness in a software company: impact on psycho-cognitive factors and performance*'. Specifically, this lab pack contains experimental materials, datasets, statistical analysis scripts, and raw results of script execution, including plots. Additionally, the lab pack includes a full report of the sphericity and homoscedasticity tests in the results, which are also available for studying the applicability of parametric tests.

For the statistical analyses carried out in his paper we have used 3 tools:
 * Python and jupyter notebooks: We used  python 3.10 and ANACONDA 2023.03-1 for the execution of the notebooks.

The labpack is structured as follows:
 * In the *root* folder of the repository you will find the python jupiter notebook files used to perform the main analyses carried out in this paper and to generate all the figures and tables shown in the paper. Specifically, you will find all two notebooks:
   * *DataAnalysis.ipynb*: This notebook extracts the demographics of the individuals ana analyzes all the plycho-cognitive factors.
   * *Performance Data Analysis Extended.ipynb*: This notebook transforms the log data about individual tasks, aggregates it into subect-wise metrics and analyzes the performance metric.
   * *requirements.txt*: PIP dependencies file that specifies the set of libraries used by the jupyter notebooks in this labpack. You can automate their installation using the following command *pip install -r requirements.txt*
 * In the la *data* folder you will find all the raw data used in this paper in CSV format, specifically, you will find the following:
   * *minfulness-inpro-demographics-with-dept.csv*: This file contains the demographic data of the whole sample, including the department column which determines the department of each experimental subject.
   * *minfulness-inpro-additional-questions.csv*: This file contains the data associated to the *techno-stress* questionnaire.
   * *minfulness-inpro-maas.csv*:  This file contains the data associated to the *maas* questionnaire, used to study the attention awarenes of the experimental subjects.
   * *minfulness-inpro-welfare.csv*: Thi file contains the data associated to the ad-hoc questionnaire created to study the welfare of the experimental subjects.
   * *subjectData*: In this folder you will find the files associated to the performance data:
     * *SupportTasks.csv*: Data about the tasks performed by the staff in the operations department extracted from the log of GLPI.
     * *DevelopmentTasks.csv*: Data about the tasks performed by the staff in the development department extracted from the log of REDMINE.
The remainder of the folders of this lab-pack, namely *latex* and *figures*  are output folders, whose content is genelated in an automated way by the analysis notebooks.
