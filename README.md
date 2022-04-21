## Instructions for creating a repository from this template

To use this template to create your own repository, follow the steps below.
1. Click the green "Use this template" button at the top of this page.
2. In the "Owner" drop down list, select whole-communities-whole-health so that the repository you create is visible to other people within WCWH. (You do not want your username here).
3. Choose a descriptive repository name.
4. Select "Private" to keep your repository to be visible to people in the WCWH Github organization only, and "Public" if you want it to be publicly available.
5. Verify that your screen matches the picture below. Click the green button "Create repository from template."

<p style="text-align:center;" align="center">
  <img align="center" src="https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/images/template-demo.png" width="75%" /></p>

You have now created a copy of this template that the same files and folder structure. 

## Next Steps
Use this repository to upload sample calculations, scripts, data sets etc. that would be userful to a someone who needs to understand the work you do (i.e. a new grad student). Here are some things to keep in mind:
1. Delete the text in this file and use README.md to describe what is in the repository you created. Include relevant usage instructions for future researchers.
2. The document [GITFLOW.md](GITFLOW.md) will give you some tips for working with branches and pull requests in git.
3. If your research team has work elsewhere on Github, please use this template to create a repository in the WCWH organization. You can link to your team's repositories in the top level README document (this file).
4. A suggested repository organization structure is below. Adapt it as necessary for your
   purposes. Include a README file in each sub directory to describe its purpose. If you have materials stored in another place (i.e. another Github repo, UT Box) please include a link to those places. You do not need to move or copy the data here.

## Suggested Repository Organization

<pre>
├── LICENSE
├── README.md          <- The top-level README for users of this repository
├── data
│   ├── README.md      <- README for data contained in this directory or an explanation of where to find data (i.e. Box)
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── images             <- Study-related images
│   └── README.md      <- README for this directory
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials
│   └── README.md      <- README for this directory
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   ├── README.md      <- README for this directory
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── src                <- Source code for use in this project.
│   └── README.md      <- README for this directory
│
└── videos             <- Study-related videos (if applicable)
    └── README.md      <- README for this directory
</pre>

## Resources

The file [GITFLOW.md](https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/GITFLOW.md) in this repository has some tips on working with branches and pull requests in git. [FORMATTING.md](FORMATTING.md) has tips on working with markdown in Github.