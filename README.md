# reproducible-ds
Reproducible Data Science Lunch and Learn

Perhaps the most painful part of being a data scientist is having to pick up or modify an existing project. If someone else started the project, you spend hours recreating the errors they made before you begin making progress. If you started the project, you spend hours trying to remember what you were thinking when you started, and then a few hours recreating the errors you made before you begin making progress.
 
There is a better way.
 
By combining multiple tools at your disposal, you can both make your work reproducible, and reduce the time you need to spin up a project.
 
## For the Lunch and Learn

### Literate Programming and Best Practices

### Versioning Code

### Versioning Data

### Versioning Models

### "Versioning" Environments



## For the Workshop

Bring a project, or a project idea, that you would like to make reproducible as we cover tools and tricks to make your work more enjoyable (for you and your collaborators).
 
Please be sure to install git on your machine if you have not yet done so (https://happygitwithr.com/install-git.html), and know your login to GitHub, and configure your git on your machine (https://happygitwithr.com/hello-git.html). If you use RStudio, be sure to test out your installation (https://happygitwithr.com/rstudio-git-github.html). We’ll have a software install clinic at 9am if you run into trouble.

Links from workshop:

### Setup

HappyGitWithR: https://happygitwithr.com/

### 10_data_load

*NB Set config to NOT load data*

import data
- haven: https://github.com/tidyverse/haven
- vroom: https://github.com/r-lib/vroom
- boxr/google drive/dropbox: https://github.com/r-box/boxr

clean data
- janitor: https://github.com/sfirke/janitor

test data
- assertr statements: https://github.com/ropensci/assertr (for Python, https://github.com/great-expectations/great_expectations)
- joins, count row/columns, anti-joins: https://cran.r-project.org/web/packages/dplyr/vignettes/two-table.html

store data
- storing data: https://git-lfs.github.com/

### 20_data_exploration

- Hmisc: https://github.com/harrelfe/Hmisc
- DataExplorer: https://cran.r-project.org/web/packages/DataExplorer/vignettes/dataexplorer-intro.html

### 30_feature_engineering

- use assertions here as well

### 40_modeling

- tidymodels: https://github.com/tidymodels
- large-scale modeling: https://www.h2o.ai/
- versioning model fits: https://mlflow.org/

### 50_reporting
- knitting
- post report in github 

### Issues

Close with commits, mention in notebooks

## Further Resources

- https://ropensci.org/packages/
- https://www.tidyverse.org/
