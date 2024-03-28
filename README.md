(this is a WIP document with unedited snippets)
# Fairly FAIR code in 10 steps

A simple checklist to make code accompanying research papers fairly **FAIR**: **f**indable, **a**ccessible, **i**nteroperable, and **R**eusable. 
The target audience is researchers that quickly need to make code available online. 
These steps are accessible toe everyone, and ensure you are following (almost) all FAIR principles with minimal effort.

## 1. [Create GitHub account](https://github.com/join)  

You'll only need to do this once! There are other version control systems and hosting platforms would also achieve FAIR4RS, but GitHub enables easy connectivity to Zenodo. 

## 2. [Create a code repository on Github](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories#create-a-repository) and [upload your code](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository) 

Be mindful not to upload code or data that may contain sensitive private.

## 3. [Choose a license](https://choosealicense.com)
Information on how to choose a license:
https://book.the-turing-way.org/reproducible-research/licensing#where-to-find-open-licenses-for-different-types-of-workhttps://the-turing-way.netlify.app/reproducible-research/licensing 
https://www.software.ac.uk/guide/choosing-open-source-licence
https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository#including-an-open-source-license-in-your-repository

## 4. Write a [README](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

In your README, include at least the following information:

  * Prequisites
  * Usage
  * Citation information (you do this in step 9)

## 5. [Create a Zenodo account](https://help.zenodo.org/docs/get-started/create-an-account/)

Many repositories can issue DOIs for your code. We chose Zenodo because of its GitHub integration.

## 6. [Link your GitHub repository with Zenodo](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content#issuing-a-persistent-identifier-for-your-repository-with-zenodo)

By linking the repository, you can make sure a persistent Digitial Object Identifier (DOI) is assigned to each release.
This important so that others can refer to specific versions of your code.

## 7. [Make a release of your repository](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository)

A release signifies an easily recognizable and specific iteration of your code, and will trigger Zenodo to create a DOI.

## 8. Add Metadata in Zenodo

In Zenodo, add all relevant metadata such as authors, their ORCID, keywords, programming language, related works etc.. To do so, go to the record page and click the orange Edit button in the top-right corner. You will be taken to a form where you can edit the metadata. Once you are done modifying it, click "Save" and then "Publish".

## 9. Add DOI badge and citation info to the repository README

On the right panel in Zenodo under Details, click on the badge with the doi, and copy the markdown text into the top of your README file. Add a “Citation” section to the bottom of your README, and copy the citation info from Zenodo into it.

## 10. Add DOI to the manuscript

Now you can add the DOI to your code availability statement in the manuscript according to the venue's guidelines.
This ensures that everyone that reads your paper will also have access to your code.

## Next

First, congratulations on publishing Fairly Fair Code! For completely FAIR code, it is also important that:

 - The code uses no proprietary dependencies, data, or data formats.
 - The code and documentation follow domain-relevant community standards.

Example of how to structure the content of the repo: https://aeadataeditor.github.io/aea-de-guidance/preparing-for-data-deposit.html#ideal-structure-of-a-replication-package 
https://github.com/cookiecutter/cookiecutter


This is not meant for software packages, libraries, or workflows, where stricter standards should be employed!

This is only one of many ways to make your code FAIR. We chose this workflow for its simplicity
