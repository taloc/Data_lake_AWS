# Data_lake_AWS

Data lake project in AWS using HDFS and S3:

This is an ETL (extract, transform, load) data project of a fictional company called Sparkify where a set of JSON files containing a music songs and user usaga data are stored in AWS S3 servers. 
The task is to create a set of dimensional tables in a star schema to be stored back into AWS S3 for the company's analytical team study of usage behaviour.

## Data source

### This contains the song database:
Song data: s3://udacity-dend/song_data
### This one contains the user log:
Log data: s3://udacity-dend/log_data

Each file is in JSON format and contains metadata about a song and the artist of that song. The files are partitioned by the first three letters of each song's track ID. For example, here are filepaths to two files in this dataset.
`song_data/A/B/C/TRABCEI128F424C983.json
song_data/A/A/B/TRAABJL12903CDCF1A.json`

## Requirements:

AWS credentials with enough credits to run S3
Python 3.8 




