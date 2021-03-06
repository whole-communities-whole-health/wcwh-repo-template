## Purpose

Use this template each time you want to share a script, function or other analysis tool. Create a new repository from this template as often as necessary.

## Instructions for Creating a Repository From This Template

To use this template to create your own repository in the WCWH organization, follow the steps below.
1. Click the green "Use this template" button at the top of this page.
2. In the "Owner" drop down list, select whole-communities-whole-health so that the repository you create is visible to other people within WCWH. (You do not want your username here). If you do not have the option to change the owner, contact [Joe Midura](https://github.com/josephmidura) so that he can add you to the organization.
3. Choose a descriptive repository name.
4. Select "Private" to keep your repository visible only to people in the WCWH Github organization, and "Public" if you want it to be publicly available.
5. Verify that your screen matches the picture below. Click the green button "Create repository from template."

<p style="text-align:center;" align="center">
  <img align="center" src="https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/images/template-demo.png" width="75%" /></p>

You have now created a copy of this template that the same files and folder structure as this template.  

## Manage Access to Your Repository  

If you created a private repository according to the steps above, you are by default the only person who can access it. To share your repository with other people within the WCWH organization on Github, follow the steps below.  

1. In your new repository, click settings from the menu at the top right, and "Collaborators and teams" from the sidebar on the left. Click the "Add teams" button and search for "researchers" in the pop up window. Choose "whole-communities-whole-health/researchers" when it appears. 

<p style="text-align:center;" align="center">
  <img align="center" src="https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/images/search.png" width="50%" /></p>

2. Choose the level of access you want to grant to the researcher team from the pop up window.  

<p style="text-align:center;" align="center">
  <img align="center" src="https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/images/grant-access.png" width="50%" /></p>

3. Optional: You can grant additional permissions on a repository to a specific person or [group of people](https://docs.github.com/en/organizations/organizing-members-into-teams/creating-a-team) if desired.

## Next Steps for Your New Repository

Use this repository to upload sample calculations, scripts, sample data sets, etc. that would be userful to a someone who needs to understand the work you do (i.e. a new grad student). Here are some things to keep in mind:
1. Delete the text in this file and instead describe what is in the repository you created. Include relevant usage instructions for future researchers.
2. Data included in your repository should be dummy data only that can be used in tandem with code you include here
3. A sample repository organization structure is below. Adapt it as necessary for your purposes. If you're only sharing a single script, your repository will look different.

## Sample Repository Organization

<pre>
????????? LICENSE            <- Include for repositories intended as open source
???
????????? README.md          <- The top-level README for users of this repository
???
????????? data
??????? ????????? README.md      <- README for this directory
??????? ????????? external       <- Data from third party sources
??????? ????????? interim        <- Intermediate data that has been transformed
???   ????????? processed      <- The final data set for modeling
??????? ????????? raw            <- The original data
???
????????? images             <- Relevant images
??????? ????????? README.md      <- README for this directory
???
????????? references         <- Data dictionaries, manuals, and other explanatory materials
??????? ????????? README.md      <- README for this directory
???
????????? reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
??????? ????????? README.md      <- README for this directory
??????? ????????? figures        <- Generated graphics and figures for use in reporting
???
????????? src                <- Source code for use in this project
??????? ????????? README.md      <- README for this directory
???
????????? videos             <- Study-related videos (if applicable)
 ???? ????????? README.md      <- README for this directory
</pre>

## Github Resources

The repository [wcwh-github-resources](https://github.com/whole-communities-whole-health/wcwh-github-resources) has resources for people unfamiliar with Github.

<img src="https://github.com/whole-communities-whole-health/wcwh-repo-template/blob/main/images/1-colorOrange_FB.png" alt="WCWH" width="200"/>
