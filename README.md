# README

<!-- user_table -->
|email|string|NOT NULL|
|password|string|NOT NULL|
|name|string|NOT NULL|
|profile|text|NOT NULL|
|position|text|NOT NULL|

<!-- prototype_table -->

|title|string|NOT NULL|
|catch_copy|text|NOT NULL|
|concept|text|NOT NULL|
|name|ActiveStorage|
|user|references|

<!-- comments_table -->

|text|text|NOT NULL|
|user|references|
|prototype|references|