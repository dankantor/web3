# Database

According to [Wikipedia](https://en.wikipedia.org/wiki/Database) a database is an organized collection of data stored and accessed electronically from a computer system. 

Let's break that down to help us understand exactly what that sentence means. We'll use Twitter as an example and see how they use a database to power their service. 

## Stored Data

Twitter has lots of data. To keep things simple, let's focus on one type of data - a tweet. A tweet in Twitter has certain properties such as text, an author, and a date. There are other properties a tweet may have but we are keeping it simple.

To represent a tweet in Twitter's database, think of how a spreadsheet works. It has columns and rows. A column typically contains the property name and the row contains the actual data. 

Databases are similar to spreadsheets. In this case, a tweet in Twitter's database looks something like this:

| Text      | Author | Date |
| ----------- | ----------- | ----------- |
| This is a really great tweet     | @dankantor       | Dec 27, 2021 |

Every tweet created is stored in Twitter's database. When you use the Twitter app it is accessing this data.

## Electronic Access

A database stores data and allows computer systems to access it. Generally, a different computer will "talk" to the computer a database is running on. It will do things such as read the data from a database or will write new data to it. 

We are oversimplifying now but imagine that Twitter's database is running in a data center somewhere in California. When you open the Twitter app on your phone it will talk to Twitter's database and ask for the newest tweets. The database will send the tweet data to your phone which will then display the tweets for you to read. In this way, your phone is a computer system that is electronically accessing the data stored in Twitter's database.

## Conclusion

Most apps and websites, like Twitter, have a database that stores all of its data. Your phone talks to this database and then displays the data according to how the app or website is designed. In the case of Twitter, there are millions of people running the Twitter app and they are all talking to Twitter's database. Since Twitter's database is running on a computer that only Twitter controls, we call this a centralized database. In the next section let's learn about decentralized databases and how they are different from centralized ones. 
