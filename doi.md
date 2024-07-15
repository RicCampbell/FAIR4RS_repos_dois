---
title: "DOIs"
teaching: 15
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 

- What is a DOI?
- What good is a DOI (compared to say an URL)?
- How do I get a DOI?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Understand what a DOI is
- Understand how they differ from other ways to link to your work
- Understand the creation and sourcing a DOI for your work

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

The code that you write is important. No matter the size, style, or langauage it is an integral part of the research that it is part of, or of course sometimes it is the main output of the research project.

Historically research outputs have been focused on papers, and while this is still mostly true, there has been a change in recent years to give better acknolwdgement to other research outputs, such as code. There has also been a shift (which we are continuing to see) that funders are requiring other outputs from projects to be made available, and while this is mostly focused on the data that has been collected or used, in certain fields code is also part of this. You may also come across conferences or awards that require code to be available (and open) to be able to submit or be considered. There's also been a rich history of code being made free and available to other.

Regardless of the reason you want to disseminate your code, there are some ways you can make this easier for both yourself and anyone who wishes to use you code, such as DOI's, using repositories, metadata, and knowing how to cite yourself.

## What is a DOI?

A DOI is a type of PID. A PID is a Persistent Identifier, and a DOI is a Digital Object Identifier. A single DOI is a linked to a digital object and always directs to that object, regardless of the location or potential changes to metadata. The most common use of DOIs is for journal articles. A single article should have a single DOI, but they can also be used for databases or software/code.


::::::::::::::::::::::::::::::::::::::: callout

# Example DOI

This is what a DOI looks like:  [10.1016/j.ascom.2020.100427]

:::::::::::::::::::::::::::::::::::::::::::::::

You've probably seen these many times before because, like that one, they are used for journal articles. Interestingly, the article that links to is about a tool that has been created, is freely available, has a licence applied to it, but has no link to the [code/software itself][https://github.com/astrom-tom/SPARTAN].

## Isn't that just a link/URL?

No. The internet as a whole is much more fragile than most people think. There is a myriad of different ways that things break, or cease to exist. While there are of course some old webpages that are still up for no apparent reason, and multiple archieves and projects that try and capture parts of the internet ([Wayback Machine][https://web.archive.org/], [Software Heritage][https://www.softwareheritage.org/]), these are by no means complete.

But speaking of your own code, if it's on a webpage (maybe your own), hosting isn't free are you planning on keeping this webpage for a long time? Are you never moving it from that page/URL, do you know if other people are using that link?

::::::::::::::::::::::::::::::::::::::: callout

A DOI essentially makes it someone else's job to ensure that the resolves to the right digital object.

:::::::::::::::::::::::::::::::::::::::::::::::

Only registered organisations can created DOI's. To be able to mint a DOI, an organiation must meet the International DOI Foundataions standards and pay to become a member, meaning that they must have the ability to ensure the DOIs are maintained.

They are also designed to be short and human readable, again unlike most URLs. Whereas shortened URLs are not persistant.

## Versions

Version control of course very important around code (see Version control part of the FAIR4RS training), and you shouldn't create more than one DOI for a single digital object, however you can version with DOIs;

::::::::::::::::::::::::::::::::::::::: callout
# DOIs with multiple versions

10.15131/shef.data.22633528*.v2*

:::::::::::::::::::::::::::::::::::::::::::::::

That part at the end indicates which version the doi will resolve to. If you have written some code for a research project, and the current version is the one that was used, but you are still developing it, referrencing that version in any paper or outputs will allow people to see exactly what the code looked like at the time the research was conducted.

It's important to note that if no version suffix is included in the DOI link then it will resolve to the most recent version of the object. This is sometimes exactly what is wanted and sometimes not, so it's good to think about this when using a DOI.

## How do I get a DOI?

To get a DOI for code the best place is to use a repository. It's important to note that (currently) GitHub does not mint DOIs. Some examples of repositories that do are [Zenodo][about.zenodo.org] and the University's institutional repository [ORDA][orda.shef.ac.uk]

When you make a deposit in a repository that does mint DOIs, there should be nothing extra you have to do, when it has been published it there will be a DOI that you can use to cite and reference to your work.

!["Image 1 - DOI location in a Zenodo deposit"](images/FAIR4RS Zenodo doi image.png)


!["Image 2 - DOI location in a ORDA deposit"](episodes/images/FAIR4RS ORDA doi image.png)


