# README

## usersテーブル

|column|Type|Pptions|
|------|----|-------|
|name|string|null: false, unique: true, index: true|
|email|string|null: false, unique: true|

## groupsテーブル

|column|Type|Pptions|
|------|----|-------|
|name|string|null: false, index: true|
|user_id|integer|null: false, foreign_key: true|


## textsテーブル

|column|Type|Pptions|
|------|----|-------|
|text|text|null: false|
|user_id|integer|null: false, foreign_key: true|
|group_id|integer|null: false, foreign_key: true|


## imagesテーブル

|column|Type|Pptions|
|------|----|-------|
|image|text|null: false|
|user_id|integer|null: false, foreign_key: true|
|group_id|integer|null: false, foreign_key: true|


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
