---
title: "The Live Index: Why Vector Search Should Be a Streaming Problem"
url: "https://risingwave.com/blog/risingwave-native-vector-search-streaming-live-index/"
date: "2026-05-22"
author: "Yuhao Su"
feed_url: "https://risingwave.com/blog"
---
The article argues that vector search should be treated as a streaming problem rather than a batch operation, since traditional vector databases operate on static snapshots that lag behind data changes. RisingWave proposes integrating vector indexing directly into a streaming database, collapsing the gap between data updates and queryable indexes to sub-second latency while eliminating separate ETL pipelines and consistency management.
