## Purpose of this template

Use this template each time you want to share a script, function or other analysis tool. Create a new repository as often as necessary.

## Instructions for creating a repository from this template

To use this template to create your own repository, follow the steps below.
1. Click the green "Use this template" button at the top of this page.
2. In the "Owner" drop down list, select whole-communities-whole-health so that the repository you create is visible to other people within WCWH. (You do not want your username here).
3. Choose a descriptive repository name.
4. Select "Private" to keep your repository visible only to people in the WCWH Github organization, and "Public" if you want it to be publicly available.
5. Verify that your screen matches the picture below. Click the green button "Create repository from template."

<p style="text-align:center;" align="center">
  <img align="center" src="https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/images/template-demo.png" width="75%" /></p>

You have now created a copy of this template that the same files and folder structure. 

## Next Steps
Use this repository to upload sample calculations, scripts, sample data sets, etc. that would be userful to a someone who needs to understand the work you do (i.e. a new grad student). Here are some things to keep in mind:
1. Delete the text in this file and use README.md to describe what is in the repository you created. Include relevant usage instructions for future researchers.
2. Data included in your repository should be dummy data only that can be used in tandem with code you include here
3. A suggested repository organization structure is below. Adapt it as necessary for your
   purposes. Include a README file in each sub directory to describe its purpose. 

## Suggested Repository Organization

<pre>
├── LICENSE            <- Include as necessary for repositories intended as open source
├── README.md          <- The top-level README for users of this repository
├── data
│   ├── README.md      <- README for this directory
│   ├── external       <- Data from third party sources
│   ├── interim        <- Intermediate data that has been transformed
│   ├── processed      <- The final, canonical data sets for modeling
│   └── raw            <- The original data
│
├── images             <- Study-related images
│   └── README.md      <- README for this directory
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials
│   └── README.md      <- README for this directory
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc
│   ├── README.md      <- README for this directory
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── src                <- Source code for use in this project
│   └── README.md      <- README for this directory
│
└── videos             <- Study-related videos (if applicable)
    └── README.md      <- README for this directory
</pre>

## Resources

The file [GITFLOW.md](https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/GITFLOW.md) in this repository has some tips on working with branches and pull requests in git. [FORMATTING.md](FORMATTING.md) has tips on working with markdown in Github. 

<img src="https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/images/1-colorOrange_FB.png" alt="WCWH" width="200"/>