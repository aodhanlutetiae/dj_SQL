## dj_SQL

This is an outline of resources and basic syntax for learning SQL for data journalism. It uses SQLite. The "Morning B" section has too much material and can be trimmed; otherwise the class structure is:

**Morning A**
- [SQL Teaching](https://www.sqlteaching.com/) (up to and including GROUP BY)
- Overview (slideshow) of databases, SQL syntax and joins for data journalism
- [Select Star](https://selectstarsql.com/) (first two chapters)
---
**Morning B**
- JOINs on SQLite using geog.db and [SQLIME in-browser](https://sqlime.org/) (or [Colab notebook](https://colab.research.google.com/drive/13Pph-0FMivBNmLqudq6-Pc735FsodYkR?usp=sharing))
  - SELECT * FROM nations JOIN cities ON nations.id = cities.id
  - SELECT * FROM cities LEFT JOIN nations ON nations.id = cities.id
- SQLite in a [Franchise notebook](https://franchise.cloud/app/) (or [Colab notebook](https://colab.research.google.com/drive/1n3IO3Gi8oUuiDq4j10tcP-2Nq_R8R5sW?usp=sharing)) to query single table database of Tour de France, letour.db
- SQLite on the command line (see Clinton emails PDF) or in [Colab notebook](https://colab.research.google.com/drive/1NOUTBoVt7Lf34IcWFSKXQVq90dXiF7IN?usp=sharing)
- Google Sheets [example](https://github.com/aodhanlutetiae/dj_SQL/blob/main/tdf_sql_using_QUERY.xlsx)

---
**Afternoon**
- Using [Datasette](https://datasette.io/) and [Queries to a Datasette of Members' Interests](https://github.com/simonw/register-of-members-interests-datasette)
- [SQL murder mystery](http://mystery.knightlab.com/index.html#experienced)
- Application STILL TO COME: database driven user app on [Glitch](https://hello-sqlite.glitch.me/)
