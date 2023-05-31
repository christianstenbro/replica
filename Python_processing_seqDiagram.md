
```mermaid

sequenceDiagram
    Note over Original Data: n = 274
    
    Original Data ->> Processed Data: Filtered out non-replication studies <br> + within-paper replications
    
    Note over Processed Data: n = 91
    
    Processed Data ->> Cloud Data 1: Uploaded the processed data <br> base to Google Drive to append original papers <br> to the replication study papers

    Note over Cloud Data 1: n = 91

    Cloud Data 1 ->> Cloud Data 2: Appended abstracts from original <br> papers. Some replication studies replicated <br> multiple studies, hence the sample size is <br> increased

```



