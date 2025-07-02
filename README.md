## dj_SQL

This is an outline of workshop(s) for learning SQL for data journalism. It uses SQLite. For writing queries, the best options are [SQLime](https://sqlime.org/) in your browser or the command line with sqlite3 installed. 

### PREP
- [SQL Teaching](https://www.sqlteaching.com/) Up to and including GROUP BY (preparatory: before class)
- Video intro to [relational databasese](https://www.youtube.com/watch?v=OqjJjpjDRLc)
- [Select Star](https://selectstarsql.com/) (Chapter 1: Beazley's Last Statement)
- Overview of SQL for data journalism (class slides)

### PRACTICE
- [Sqlite database](https://github.com/instituteforgov/ifg-ministers-database-public) of UK Ministers from IFG (inside Data file from repository) or [via DuckDB](https://github.com/instituteforgov/ifg-ministers-database-public/blob/main/tutorial/duckdb_tutorial.MD) (tutorial)
- [Queries to a DATASETTE of the Register of Members' Interests](https://register-of-members-interests.datasettes.com/). This uses the MySociety XML of the [Register of Members' Interests](https://www.parliament.uk/mps-lords-and-offices/standards-and-financial-interests/parliamentary-commissioner-for-standards/registers-of-interests/register-of-members-financial-interests/). There is a [background repo](https://github.com/simonw/register-of-members-interests-datasette). 
- 7-table database of money to MPs, [via a .db you can download](https://static.simonwillison.net/static/2023/sky-westminster-files.db) and a [Datasette](https://lite.datasette.io/?sql=https://gist.github.com/simonw/ee4d5938016b10c490f7efa03c4bf185). This uses the Sky News Register of Members' Interests (MPs), Register of APPGs and Electoral Commission's party donation database. Background [here](https://til.simonwillison.net/shot-scraper/scraping-flourish).
- [SQL murder mystery](http://mystery.knightlab.com/index.html#experienced)
- Another [SQL mystery](https://www.sqlnoir.com/) to solve

### CLOUD
- Using Athena (AWS) and SQL [to query data](https://palewi.re/docs/first-athena-query/)(course)
- Google Big Query [for datasets](https://docs.google.com/presentation/d/1KSuvk23sUVTqH6fpe367_M3W2LGAyJrMroqLZyMdILc/edit?slide=id.p#slide=id.p)

