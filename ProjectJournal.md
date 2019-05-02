# Project ProjectJournal

<<<<<<< HEAD

=======
>>>>>>> e740cf6a498a41ff5844fa732322f5cca702b62e

## S3
* Buckets
  * TwitterRawLocation : s3://socialmediaanalyticsblogpost-tweetsbucket-1a8yo9ahc0wqt/raw/
  * TwitterEntitiesLocation : s3://socialmediaanalyticsblogpost-tweetsbucket-1a8yo9ahc0wqt/entities/
  * TwitterSentimentLocation : s3://socialmediaanalyticsblogpost-tweetsbucket-1a8yo9ahc0wqt/sentiment/
  * S3ConsoleURL : https://s3.console.aws.amazon.com/s3/buckets/socialmediaanalyticsblogpost-tweetsbucket-1a8yo9ahc0wqt/?region=us-east-1&tab=overview

* Region : US East (N. Virginia)

## Lambda
* Runtime : Nodejs 6.10
* Environment Variables
  * ENTITY_STREAM : SocialMediaAnalyticsBlogPos-EntitiesFirehoseStream-14PY1IFNSS3Y1
  * SENTIMENT_STREAM : SocialMediaAnalyticsBlogPo-SentimentFirehoseStream-5OZHSECPZBRT
* Resources with access to function:
  * Amazon Cloud Watch Logs
  * Amazon Kinesis Firehose
  * Amazon Comprehend
  * Amazon S3
  * Amazon Translate
* Triggers
  * Event Type : Amazon S3 Object Creation
  * Prefix: raw/
