# Security Data Centralization
Collection of ETL/ELT of various security sources for ingestion and use within snowflake. Primary ingest point is s3 with snowpipe.   The Table structures are standard from the upstream format and could be used within other sql compliant engines.   

## Prerequisites

-   s3 buckets with appropriate bucket policys for snowpipe access
-   IAM cross account role setup for snowpipe access
-   Appropriate permissions in snowflake to create, databases, schemas, pipes, streams storage integrations and tasks. 
-   Logs writing/streaming to the s3 buckets. 

## Sources

| Source  | Method   | Field Documentation  |
|---|---|---|
| Lacework  | Snowpipe + Streams/tasks  | https://docs.lacework.com/category/snowflake-data-share-views  |
|   |   |   |
|   |   |   |
