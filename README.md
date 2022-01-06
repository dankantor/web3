---
description: What is a database?
---

# Database

According to [Wikipedia](https://en.wikipedia.org/wiki/Database) a database is an organized collection of data stored and accessed electronically from a computer system.

Let's break it down to help us understand exactly what that sentence means. We'll use Twitter as an example and see how they use a database to power their service.

### Stored Data

Twitter has lots of data. To keep things simple, let's focus on one type of data - a tweet. A tweet in Twitter has a few properties including text, an author, and a date.

To represent a tweet in Twitter's database, think of how a spreadsheet works. It has columns and rows. A column typically contains the property name and the row contains the actual data.

Databases are similar to spreadsheets. In this case, a tweet in Twitter's database looks something like this:

| Text                         | Author     | Date         |
| ---------------------------- | ---------- | ------------ |
| This is a really great tweet | @dankantor | Dec 27, 2021 |
