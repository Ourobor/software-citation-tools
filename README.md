# Software Citation Tools

[![Join the chat at https://gitter.im/mozillascience/software-citation-tools](https://badges.gitter.im/mozillascience/software-citation-tools.svg)](https://gitter.im/mozillascience/software-citation-tools?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The Software Citation Tools will be a suite of tools for the scientific community to assist them in citing software that is found online and used in research and scientific papers.  The purpose of this is to reduce friction for researchers to cite software and make sure that software developers are given the credit they are due.  The suite will be developed in conjunction with Mozilla Science Lab via Abigail Cabunoc Mayes, the scientific community, and the open source software development community.  The project will require extensive interviews with members of the research community to gather information on how they are currently citing software, and how these tools can streamline that process.

At the core of the Software Citation Tools suite will be a package written in JavaScript using npm.  This package will provide functions which will take a GitHub repository URL and return a citation for the software compliant with the Software Citation Principles.  Stretch goals for this package may include accepting other types of software repositories as input, and accepting parameters that will change the format of the citation.  For example, parameters to generate long and short versions of a citation, or output for different citation standards.  The priority of stretch goals will be determined based on the needs of the scientific community.

Utilizing the citation package, two or more applications will be developed.  Two such applications might be a webapp interface to allow researchers to utilize the package conveniently, and a browser plugin to produce the citation when the user has navigated to a repo.
