# Database

## What is a Database?
A [database](https://en.wikipedia.org/wiki/Database) is an organized collection of data stored and accessed electronically from a computer system. Ok, so what does that actually mean? To help us understand, let's use Twitter as an example. 

## Stored Data

Twitter has lots of data. To keep things simple, let's focus on two types of data - users and tweets. A user in twitter has a screen name and a full name. There are other properties a user may have such as an avatar, description, and location but let's stick to screen name and full name. To represent a user in Twitter's database, think of how a spreadsheet works. It has columns and rows. Databases are generally similar to spreadsheets. In this case, a user in Twitter's database looks something like this:

| Screen Name      | Full Name |
| ----------- | ----------- |
| @dankantor      | Dan Kantor       |
| @jack   | Jack Dorsey        |

A tweet in Twiiter also has some properties - text, author, date. A tweet in Twitter's database looks something like this:

| Text      | Author | Date |
| ----------- | ----------- | ----------- |
| This is a really great tweet     | @dankantor       | Dec 27, 2021 |

All of this data is stored in Twitter's database. When you use the Twitter app it is accessing this data.
