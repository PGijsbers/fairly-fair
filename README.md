# Fairly FAIR code in 10 steps

A simple checklist to make code accompanying research papers fairly **FAIR**: **f**indable, **a**ccessible, **i**nteroperable, and **r**eusable. 
This guide is for researchers that want to make code available online with minimal effort. 
These steps are accessible to everyone, and ensure you are following (almost) all FAIR principles with minimal effort.

## 1. Create [a GitHub account](https://github.com/join)

You'll only need to do this once! Using a platform where you can host your code repository publicly allows others to browse, use, and (optionally) contribute to your code. We recommend Github because of its easy integration with Zenodo (which we use later), but you could also consider alternatives like [Gitlab](https://gitlab.com/users/sign_up) or [Codeberg](https://codeberg.org/user/cbrgp/vY9AXwg). 

## 2. [Choose a license](https://choosealicense.com)

The intent is to share your code with everyone to allow them, so don't overthink it! You can also find more in-depth information in the [Turing Way](https://book.the-turing-way.org/reproducible-research/licensing#where-to-find-open-licenses-for-different-types-of-work) book.


## 3. Create a [code repository on Github](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories#create-a-repository) and [upload your code](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository) 

When creating a repository, make sure to select the license you choose in step 2 in the "Choose a license" dropdown menu.
Be mindful not to upload code or data that may contain privacy sensitive elements.

## 4. Write a [README](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

In your README, include at least the following information:

  * Overview: What is the purpose of your code?
  * Prequisites: What other software or hardware is required to run your code?
  * Usage: How can users run your code? Are there parameters to your code?
  * License: Under which license did you make your code available?
  * Citation information: How should others cite your code? (you do this in step 9)
  * Contact: Who should be contacted with questions or reports about your code, and how?

## 5. [Create a Zenodo account](https://help.zenodo.org/docs/get-started/create-an-account/)

We want to ensure that there is a persistent way to refer to exact versions of your code. 
Repositories such as Zenodo issue Digital Object Identifiers ([DOI](https://www.doi.org/the-identifier/what-is-a-doi/)).
There are alternatives, but we recommend Zenodo because of its GitHub integration.

## 6. [Link your GitHub repository with Zenodo](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content#issuing-a-persistent-identifier-for-your-repository-with-zenodo)

By linking the repository, you can make sure a persistent DOI is assigned to each release.
This important so that others can refer to specific versions of your code.

## 7. [Make a release of your repository](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository)

A release signifies an easily recognizable and specific iteration of your code, and will trigger Zenodo to create a DOI.

## 8. Add Metadata in Zenodo

In Zenodo, add all relevant metadata by going to the record page and clicking the orange `Edit` button in the top-right corner. 
You will be taken to a form where you can edit the metadata. 
Once you are done modifying it, click `Save` and then `Publish`.
Good metadata can help people find your code, and provides them context.

## 9. Add DOI badge and citation info to the repository README

On the right panel in Zenodo under Details, click on the badge with the doi, and copy the markdown text into the top of your README file. 
The DOI badge is a sign that your software will remain findable.
Then, add a “Citation” section to the bottom of your README, and copy the citation info from Zenodo into it.

## 10. Add DOI to the manuscript

Now you can add the DOI to your code availability statement in the manuscript according to the venue's guidelines.
This ensures that everyone that reads your paper will also have access to your code.

# Next

First, congratulations on publishing Fairly Fair Code! 
The steps you took greatly improve the ability for other people to understand and use your work, and will be appreciated by many future readers (possibly even your future self :)).
For completely FAIR code, it is also important that:

 - The code uses no proprietary dependencies, data, or data formats. Consider using [an open data format](https://opendatahandbook.org/guide/en/appendices/file-formats/).
 - The code and documentation follow domain-relevant community standards. You may consider [standards from your scientific domain](https://aeadataeditor.github.io/aea-de-guidance/preparing-for-data-deposit.html#ideal-structure-of-a-replication-package) as well as standards for [default project structures](https://github.com/cookiecutter/cookiecutter).

Your project may already adhere to that, and if so, great! If not, you may either go back and revise it, or simply keep it in mind for the next project you do. 
If you're interested in taking it even further, the [Turing Way](https://book.the-turing-way.org) is a great digital resource for all things reproducible, ethical, and collaborative (data) science.

### Disclaimer
This is not meant for software packages, libraries, or workflows, where stricter standards should be employed!
This is only one of many ways to make your code FAIR. We chose this workflow for its simplicity.

### Attribution
This document is inspired by the [FAIR Cheatsheets](https://github.com/UtrechtUniversity/FAIR-Cheatsheets) of Utrecht University.

This document was written during the [2024 Open Science Retreat](https://openscienceretreat.eu) by Niklas Hohmann, Ana Martinovici, Christian Meesters, Benedikt Langenberg, Kjong Lehmann, and Pieter Gijsbers (in no particular order). We also thank other attendees of the event for their thoughtful input and suggestions.

