| &nbsp; | &nbsp; | &nbsp; |
|---|---|---|
| id | string | unique identifier for this Weighted backend |
| uri | string | URI of the WeightedBackend API resource |
| created_at | string | timestamp when the backend was created, RFC 3339 format |
| description | string | human-readable description of this backend. Optional |
| metadata | string | arbitrary user-defined machine-readable data of this backend. Optional |
| backends | Map&lt;string, int64&gt; | the ids of the child backends to their weights [0-10000] |