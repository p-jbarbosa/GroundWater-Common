# SQL Changes

## change data lenght on job table

2018-04-15

``` sql

ALTER TABLE "etl-control".job ALTER COLUMN status TYPE varchar(32) USING status::varchar ;

```