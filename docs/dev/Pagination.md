# Opendistro ODBC Driver Cursor (Pagination) Support

## Overview
Elasticsearch ODBC Driver supports forward-only cursor. This document illustrates how the cursor(pagination) is handled in driver. 

For information on how the pagination is supported on Elasticsearch server, check [Opendistro SQL Cursor (Pagination) Support](https://github.com/opendistro-for-elasticsearch/sql/blob/master/docs/dev/Pagination.md).

## Data Flow
<img src="img/data_flow.png" width="50%">

## Detailed Design
<img src="img/async_result_retrieval.png">

