# wcwh-repo-template
This repository is used as the boilerplate for consistency across WCWH repositories related to
data analysis.

<img src="https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/images/1-colorOrange_FB.png" alt="WCWH" width="200"/>

## Instructions for creating a repository from this template

To use this template to create your own repository, follow the steps below
1. Click the green "Use this template" button above.
2. In the "Owner" drop down list, select whole-communities-whole-health so that the repository you create is visible to other people within WCWH. (You do not want your username here).
3. Choose a descriptive repository name.
4. Select "Public."
5. Click the green button "Create repository from template."

You have now created a copy of the template with the same files and folder structure. 

## Next Steps
Use this repository to upload sample calculations, scripts, data sets etc. that would be userful to a someone who needs to understand the work you do. Here are some things to keep in mind:
1. Delete the text in this file to and use README.md to describe what is in your repository and include relevant usage instructions.
2. The document GITFLOW.md will give you some tips for working with branches and pull requests in git.
3. If your research team has work elsewhere on Github, please use this template to create a repository in the WCWH organization. You can link to your team's repository as necessary.
4. A suggested repository organization structure is below. Adapt it as necessary for your
   purposes.

## Suggested Repository Organization

<pre>
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
|   ├── purgatory      <- Raw data with inconsistent formatting.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── images             <- Study-related images
│
├── notebooks          <- Jupyter notebooks for the majority of analysis
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features 
│   │   └── build_features.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── videos             <- Study-related videos
</pre>

## Resources

The file [GITFLOW.md](https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/GITFLOW.md) in this repository has some tips on working with branches and pull requests in git.
