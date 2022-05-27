<figure>
  <IMG SRC="https://raw.githubusercontent.com/mbakker7/exploratory_computing_with_python/master/tudelft_logo.png" WIDTH=250 ALIGN="right">
</figure>

# Assignment/Exam Result Analysis
This notebook has been for the TUDelft UTQ Assess course to analyze the results of the assignments/exams. The notebook covers some methods that have been considered within the course but can be a good first point to do the analysis of assignments/exams results. Of course, the notebook is not perfect and contains space for improvement, so all PRs are welcomed.


## Development
For the Python dependency management, I use [poetry](https://python-poetry.org/). That is why in the repository, you can find two files:
 - *pyproject.toml*, where the project properties are defined, including the list of the prod/dev packages and their versions;
 - *poetry.lock*, that fixates the exact versions used for the development

If you also use [poetry](https://python-poetry.org/), you can create a virtual environment and install all required dependencies by running the command `poetry install` in the project's root directory. 

For the analysis/development, I use VS Code editor. Therefore, there is one `dev` dependency - `ipykernel` that is required to use . You can read more about how I use poetry and VS Code for the data analysis activities in my blog post: [Switching Data Analytics Activities From Jupyter to Vscode](https://zhauniarovich.com/post/2022/2022-02-switching-data-analytics-activities-from-jupyter-to-vscode/).


## Data
The repository includes some test data in the `data` directory. The results of the analysis are stored in two subdirectories of the `results` directory:
- `csvs` directory contains the CSV files with the results of the analysis;
- `figs` directory contains the plots produced as the result of the analysis.


## Licence
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

If you use the code and the data from this project, please consider attributing your products with the following entities:
 - [TU Delft](https://www.tudelft.nl/)
 - [UTQ Program within TU Delft](https://www.tudelft.nl/teachingacademy/events-trainings/teacher-trainings/utq-bko)
 - [Yury Zhauniarovich](https://www.tudelft.nl/en/staff/y.zhauniarovich/?cHash=c0cdc054f8de0b9e769a417f14c1b716)