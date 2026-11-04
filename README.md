# About

Here you will find free-to-use .csv files of past osu!taiko California user data. 

All user data is taken from the public osu! API. 
Usernames are collected from [osu! World](https://osuworld.octo.moe/) and any other relevant data on osu!, such as team data or user profiles.

## Download

**https://drive.google.com/drive/folders/1GoyK6zKBijLN0w4HDsOg8FuFCK2YY6Xm?usp=sharing**

## If using with SQLite

Use the following schema:

```sql
CREATE TABLE users (
    user_id INTEGER PRIMARY KEY NOT NULL,
    username TEXT,
    global_rank INTEGER,
    country_rank INTEGER,
    pp REAL,
    ranked_score REAL,
    accuracy REAL,
    total_ss INTEGER,
    total_s INTEGER,
    total_a INTEGER
)
```

## If there is a user that should not be here

Contact @somebody_33 on Discord or [message me on osu!](https://osu.ppy.sh/users/16830329), and I'll remove the user from the datasets as soon as possible.

# Columns

## user_id
ID of user on bancho

## username

## global_rank
the user's rank (null if inactive)

## country_rank
rank in USA

## pp

## ranked_score
ranked score in billions

## accuracy

## total_ss
sum of SS and silver SS ranks

## total_s
sum of S and silver S ranks

## total_a

