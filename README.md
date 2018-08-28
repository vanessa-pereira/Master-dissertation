# Msc in Medical Informatics dissertation: Governance of openEHR based local repository compliant with openEHR Clinical Knowledge Manager

This repository contains all the LateX files from my medical informatics master dissertation entitled "Governance of openEHR based local repository compliant with openEHR Clinical Knowledge Manager" + pdf file. Made with overleaf.


## Abstract

<p align="justify">The openEHR is a free open-source standard which provides specifications of how to store, share
and retrieve health data with the main idea of separating this data from applications implementation
logic as an agnostic approach. It has his own governance library repository of resources or artifacts
(archetypes and templates) called Clinical Knowledge Manager (CKM), that is under constant review by
an online community of health care and informatics experts. However, there is an emerging issue. Each
company or institution working with openEHR archetypes and templates for their projects, have their
own local repository with a file system or a Control Version System (CVS) to manage them. These local
repositories are usually created at the start of a project by downloading copies of the available archetypes
from the CKM at a certain point in time and usually these are not kept updated. Over the years, the
main CKM (also known as International openEHR CKM) had new updated versions for the different
archetypes, having a very well-structured management of the archetype’s lifecycles, with the new version
being approved after a community consensus (Leslie, 2017). This implies that knowledge in the openEHR
CKM stays always updated, but that does not necessarily happen on the local repositories.

Until now, there was no clear definition on how to solve this issue: how to manage a local repository,
keep it connected to the CKM and maintain the local repository updated and compliant with it. Based
on this problem, the aim of the study was to find and implement a suitable way of having the different
openEHR local repositories updated and compliant with the international openEHR CKM. In order to
reach it, studies were made, such as:<p>

1. Learn how the openEHR CKM works, history, features, functionalities and how the verification of
new versions of artifacts is made;
2. Study state of art methodologies used for managing software and document lifecycles;
3. Review of the openEHR specifications for Reference Model (RM) and Archetype Model (AM),
related with archetype identification and versioning;
4. Creation of documentation about how to deal with archetype versioning on a local repository and
a script to compare the artifacts content in both repositories and verify new updates for each
archetype from openEHR CKM;
5. Development and implementation of the proposed methodology and verification of results.

<p align="justify">Initially was made a comparison analysis between archetypes stored in a local repository of an ongoing
project and the current version of the same archetypes in the international openEHR CKM, which
consisted on a direct comparison between the major version (V.x), versioning parameters and the content
of archetypes. A local repository for testing was provided and the openEHR CKM mirror is publicly
available on GitHub. The tools used were composed by ”ADL Designer” version 2 from Marand, GitHub 
REST API, GitLab REST API, openEHR CKM and Tortoise SVN. The script for comparison of both
repositories was based on Angular 2 and Typescript and used REST API calls from ADL Designer and
GitHub API.<p>
  
<p align="justify">The junction of all the information gathered from this study allowed to create a methodology and
a script for versioning comparison, along with documentation of how to deal with the versioning of
openEHR archetypes on new and ongoing projects of local repositories. It is expected to contribute with
an added value to the governance of openEHR resources. The study was made along with Faculty of
Medicine of Porto University in Portugal and Marand d.o.o in Slovenia under the Erasmus + internships
mobility from September 2017 to September 2018.

**Keywords:** (MeSH) Electronic Health Records, Medical Informatics, Health Information Exchange,
Health Information Management (Non-MeSH) OpenEHR, Version Control
<p>
