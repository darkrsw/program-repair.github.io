# program-repair.org [![build](https://github.com/program-repair/program-repair.github.io/actions/workflows/build.yml/badge.svg)](https://github.com/program-repair/program-repair.github.io/actions/workflows/build.yml)

This website is a community-driven effort to provide up-to-date [automated program repair](https://en.wikipedia.org/wiki/Automatic_bug_fixing) bibliography, and links to publicly available tools and benchmarks.

## Content Policy ##

The bibliography section lists publications on automated program repair that

* are peer-reviewed;
* designed/evaluated for program repair.

The bibliographic records on this website are automatically extracted from dblp.org.

The tools/benchmarks sections list only tools/benchmarks that

* have corresponding publications in the bibliography section;
* publicly available;
* designed/evaluated for program repair.

The website hosts community pages &mdash; static webpages that present some useful information about program repair, e.g. visualise experiments. If you would like to maintain a community page under program-repair.org, please create an issue.

## Contributions ##

The easiest way to contribute is to submit a new publication/tool/benchmark via GitHub issues. When submitting an issue, please provide the puiblication's DBLP key. To obtain the DBLP key, find the publication on dblp.org, and hover your mouse over "export record". To submit a new tool or benchmark, please provide the DBLP key of its corresponding publication. Note that publications appear on DBLP with a delay. 

Typically, your contribution will be accepted faster if you create a pull request. For that, you need to add your data into program-repair.org's database stored in the `data` directory, and then generate the website. Note that when making simple changes, you can skip regenerating the website, because it will be done automatically by GitHub actions, but generally we recommend regenerating website to test your changes before create an PR. If you want to verify your modifications locally:

1. Install Python 3 and dependencies (e.g. `pip3 install -r requirements.txt`).
2. Run build script (e.g. `python3 build.py`).
3. Open `index.html` in your browser to verify your modifications.

## Maintenance ##

Related SE journals on DBLP:

* [Transactions on Software Engineering (TSE)](https://dblp.uni-trier.de/db/journals/tse/index.html)
* [Transactions on Software Engineering and Methodology (TOSEM)](https://dblp.uni-trier.de/db/journals/tosem/index.html)
* [Empirical Software Engineering (EMSE)](https://dblp.uni-trier.de/db/journals/ese/index.html)

Related SE conferences on DBLP:

* [International Conference on Software Engineering (ICSE)](https://dblp.uni-trier.de/db/conf/icse/index.html)
* [Conference on the Foundations of Software Engineering (FSE)](https://dblp.uni-trier.de/db/conf/sigsoft/index.html)
* [International Conference on Automated Software Engineering (ASE)](https://dblp.uni-trier.de/db/conf/kbse/index.html)
* [International Symposium on Software Testing and Analysis (ISSTA)](https://dblp.uni-trier.de/db/conf/issta/index.html)
* [International Conference on Software Analysis, Evolution, and Reengineering (SANER)](https://dblp.uni-trier.de/db/conf/wcre/index.html)
* [International Conference on Software Testing, Verification, and Validation (ICST)](https://dblp.uni-trier.de/db/conf/icst/index.html)
* [Working Conference on Mining Software Repositories (MSR)](https://dblp.uni-trier.de/db/conf/msr/index.html)


Related PL conferences on DBLP:

* [Symposium on Programming Language Design and Implementation (PLDI)](https://dblp.uni-trier.de/db/conf/pldi/index.html)
* [Symposium on Principles of Programming Languages (POPL)](https://dblp.uni-trier.de/db/conf/popl/index.html)

Related FM conferences on DBLP:

* [International Conference on Computer Aided Verification (CAV)](https://dblp.org/db/conf/cav/index.html)
* [International Conference on Tools and Algorithms for Construction and Analysis of Systems (TACAS)](https://dblp.org/db/conf/tacas/index.html)

Related ML conferences on DBLP:

* [International Conference on Machine Learning (ICML)](https://dblp.org/db/conf/icml/index.html)

Related workshops on DBLP:

* [Workshop on Automated Program Repair (APR)](https://dblp.org/db/conf/icse-apr/index.html)
* [International Genetic Improvement Workshop (GI)](https://dblp.org/db/conf/gi-ws/index.html)
