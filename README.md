# JabRef Bibliography Management [![Hacktoberfest](https://img.shields.io/github/hacktoberfest/2019/JabRef/jabref?suggestion_label=hacktoberfest)](https://www.jabref.org/hacktoberfest/2019.html)

[![Build Status](https://travis-ci.org/JabRef/jabref.svg?branch=master)](https://travis-ci.org/JabRef/jabref)
[![codecov.io](https://codecov.io/github/JabRef/jabref/coverage.svg?branch=master)](https://codecov.io/github/JabRef/jabref?branch=master)
[![Donation](https://img.shields.io/badge/donate%20to-jabref-orange.svg)](https://github.com/JabRef/jabref/wiki/Donations)
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/jabref/localized.svg)](https://crowdin.com/project/jabref)

JabRef is an open-source, cross-platform citation and reference management tool licensed under the  [MIT license](https://tldrlegal.com/license/mit-license).

Stay on top of your literature: JabRef helps you to collect and organize sources, find the paper you need and discover the latest research.
![main table](https://www.jabref.org/img/JabRef-4-0-MainTable.png)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Bug Reports, Suggestions, Other Feedback](#bug-reports-suggestions-other-feedback)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements) / [License](#license)

## Features

JabRef is a cross-platform application that works on Windows, Linux and Mac OS X. It is available free of charge and is actively developed.
JabRef supports you in every step of your research work.

#### Collect

- Search across many online scientific catalogues like CiteSeer, CrossRef, Google Scholar, IEEEXplore, INSPIRE-HEP, Medline PubMed, MathSciNet, Springer, arXiv, and zbMATH
- Import options for over 15 reference formats
- Easily retrieve and link full-text articles
- Fetch complete bibliographic information based on ISBN, DOI, PubMed-ID and arXiv-ID
- Extract metadata from PDFs
- [JabFox Firefox Add-on](https://addons.mozilla.org/en-US/firefox/addon/jabfox/) lets you import new references directly from the browser with one click
	
#### Organize

- Group your research into hierarchical collections and organize research items based on keywords/tags, search terms or your manual assignments
- Advanced search and filter features
- Complete and fix bibliographic data by comparing with curated online catalogues such as Google Scholar, Springer or MathSciNet
- Customizable citation key generator
- Customize and add new metadata fields or reference types
- Find and merge duplicates
- Attach related documents: 20 different kinds of documents supported out of the box, completely customizable and extendable
- Automatically rename and move associated documents according to customizable rules
- Keep track of what you read: ranking, priority, printed, quality-assured 
	
#### Cite

- Native [BibTeX] and [Biblatex] support
- Cite-as-you-write functionality for external applications such as Emacs, Kile, LyX, Texmaker, TeXstudio, Vim and WinEdt.
- Format references in one of the many thousand built-in citation styles or create your style
- Support for Word and LibreOffice/OpenOffice for inserting and formatting citations
	
#### Share

- Many built-in export options or create your export format
- Library is saved as a simple text file and thus it is easy to share with others via Dropbox and is version-control friendly
- Work in a team: sync the contents of your library via a SQL database

## Installation

Fresh development builds are available at [builds.jabref.org](https://builds.jabref.org/master/).
The [latest stable release is available at FossHub](https://www.fosshub.com/JabRef.html).

JabRef runs on any system equipped with the Java Virtual Machine (Java 11 or higher), which can be downloaded at no cost from [AdoptOpenDJK](https://adoptopenjdk.net/).
From JabRef 4.0 onwards, [JavaFX] support has to be installed.
 - Windows: JabRef offers an installer, which also adds a shortcut to JabRef to your start menu. Please also see our [Windows FAQ](https://help.jabref.org/en/FAQwindows)
 - Linux: Please see our [Installation Guide](http://help.jabref.org/en/Installation).
 - Mac OS X: Please see our [Mac OS X FAQ](https://help.jabref.org/en/FAQosx).

In addition, JabRef can be downloaded as an executable `.jar` file. 
Try to double click the `jar` file or execute the following command:
     `java -jar <path to jar>`

## Bug Reports, Suggestions, Other Feedback

[![Donation](https://img.shields.io/badge/donate%20to-jabref-orange.svg)](https://github.com/JabRef/jabref/wiki/Donations)

We are thankful for any bug reports or other feedback.
If you have ideas for new features you want to be included in JabRef, [tell us in our forum](http://discourse.jabref.org/c/features)!
If you need support in using JabRef, please read [the documentation](https://help.jabref.org/) first and have a look at our [community forum](http://discourse.jabref.org/c/help).
You can use our [GitHub issue tracker](https://github.com/JabRef/jabref/issues) to file bug reports.

An explanation of donation possibilities and usage of donations is available at our [donations page](https://github.com/JabRef/jabref/wiki/Donations).

## Contributing

[![Help Contribute to Open Source](https://www.codetriage.com/jabref/jabref/badges/users.svg)](https://www.codetriage.com/jabref/jabref)
[![Join the chat at https://gitter.im/JabRef/jabref](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/JabRef/jabref?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![OpenHub](https://www.openhub.net/p/jabref/widgets/project_thin_badge.gif)](https://www.openhub.net/p/jabref)

> Not a programmer? [Learn how to help.](https://help.jabref.org/en/FAQcontributing)

Want to be part of a free and open-source project that tens of thousands of scientists use every day? Check out the ways you can contribute, below:
- For details on how to contribute, have a look at our [guidelines for contributing](CONTRIBUTING.md).
- You are welcome to contribute new features. To get your code included into JabRef, just [fork](https://help.github.com/en/articles/fork-a-repo) the JabRef repository, make your changes, and create a [pull request](https://help.github.com/en/articles/about-pull-requests).
- To work on existing JabRef issues, check out our [issue tracker](https://github.com/JabRef/jabref/issues). New to open source contributing? Look for issues with the ["good first issue"](https://github.com/JabRef/jabref/labels/good%20first%20issue) label to get started.

We view pull requests as a collaborative process.
Submit a pull request early to get feedback from the team on work in progress.
We will discuss improvements with you and agree to merge them once the [developers](https://github.com/JabRef/jabref/blob/master/DEVELOPERS) approve.

If you want a step-by-step walk-through on how to set-up your workspace, please check [this guideline](https://github.com/JabRef/jabref/wiki/Guidelines-for-setting-up-a-local-workspace).

To compile JabRef from source, you need a Java compiler supporting Java 1.8 and `JAVA_HOME` pointing to this JDK.
You have to set `GRADLE_OPTS` to `-Dfile.encoding=UTF-8` as [gradle uses the JVM's platform encoding](https://discuss.gradle.org/t/is-there-a-way-to-tell-gradle-to-read-gradle-build-scripts-using-a-specified-encoding/7535).

To run it, just execute `gradlew run`.
When you want to develop, it is necessary to generate additional sources using `gradlew generateSource`
and then generate the Eclipse `gradlew eclipse`.
For IntelliJ IDEA, just import the project via a Gradle Import by pointing at the `build.gradle`.

`gradlew test` executes all tests. We use [Travis CI](https://travis-ci.org/) for executing the tests after each commit. For developing, it is sufficient to locally only run the associated test for the classes you changed. Travis will report any other failure.


## Acknowledgements

We use [install4j], the multi-platform installer builder. We've got an [open-source license](https://www.ej-technologies.com/buy/install4j/openSource).

## License

Since version 3.6, JabRef is licensed under the [MIT license](https://tldrlegal.com/license/mit-license).
See the [LICENSE.md](LICENSE.md) for the full MIT license.

JabRef also uses libraries, fonts, and icons distributed by other parties.
See [external libraries](external-libraries.txt) for details.

  [BibTeX]: https://www.ctan.org/pkg/bibtex
  [Biblatex]: https://www.ctan.org/pkg/biblatex
  [install4j]: https://www.ej-technologies.com/products/install4j/overview.html
  [JabRef]: https://www.jabref.org
  [JavaFX]: https://en.wikipedia.org/wiki/JavaFX
