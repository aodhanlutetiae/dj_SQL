## dj_SQL

This is an outline of resources and basic syntax for learning SQL for data journalism. It uses SQLite. The half-day class structure is:

- [PREP: SQL Teaching](https://www.sqlteaching.com/) Up to and including GROUP BY (+ relational databases video)
- [Select Star](https://selectstarsql.com/) (Chapter 1)
- Overview of SQL for data journalism
- [Queries to a DATASETTE of the Register of Members' Interests](https://register-of-members-interests.datasettes.com/). This uses the MySociety XML of the [Register of Members' Interests](https://www.parliament.uk/mps-lords-and-offices/standards-and-financial-interests/parliamentary-commissioner-for-standards/registers-of-interests/register-of-members-financial-interests/). There is a (background repo)[https://github.com/simonw/register-of-members-interests-datasette]). 
- [7-table database of money to MPs, via a .db and a Datasette](https://til.simonwillison.net/shot-scraper/scraping-flourish). This uses the Sky News Register of Members' Interests (MPs), Register of APPGs and Electoral Commission's party donation database.
- [SQL murder mystery](http://mystery.knightlab.com/index.html#experienced)

---
<!-- **Extra**
- JOINs on SQLite using geog.db and [SQLIME in-browser](https://sqlime.org/) (or [Colab JOINS notebook](https://colab.research.google.com/drive/13Pph-0FMivBNmLqudq6-Pc735FsodYkR?usp=sharing))
  - SELECT * FROM nations JOIN cities ON nations.id = cities.id
  - SELECT * FROM cities LEFT JOIN nations ON nations.id = cities.id
- SQLite in a [Franchise notebook](https://franchise.cloud/app/) (or [Colab TDF notebook](https://colab.research.google.com/drive/1n3IO3Gi8oUuiDq4j10tcP-2Nq_R8R5sW?usp=sharing)) to query single Tour de France table, letour.db
- SQLite on the command line (see Clinton emails PDF) or in [Colab CLINTON notebook](https://colab.research.google.com/drive/1NOUTBoVt7Lf34IcWFSKXQVq90dXiF7IN?usp=sharing)
- Google Sheets [example](https://github.com/aodhanlutetiae/dj_SQL/blob/main/tdf_sql_using_QUERY.xlsx)

 -->

<!-- - Application STILL TO COME: database driven user app on [Glitch](https://hello-sqlite.glitch.me/)
QUID CHATGPT?
 -->
