### PoolWorker

A "worker" connected to a `Pool` to produce hashes for that pool. A PoolWorker
is usually a single `Miner`, but often a single `Miner` can represent several
PoolWorkers, in the cases of load distribution/balancing/failover.

| config | value |
|:---|:---|
| rest? | `true` |
| table | `poolworker` |
| extends | `` |
| autoPK | `true` |

| attribute | type | column | description |
|:---|:---|:---|:---| 
| name | `string` |  |  |   
| miner | `Miner` |  |  |   
| password | `string` |  |  |   
| pool | `Pool` |  |  |   
| currency | `Currency` |  |  |   
| quota | `integer` |  |  |   
| cgminerId | `integer` |  |  |   
| createdBy | `User` |  |  |   
| owner | `User` |  |  |   
| id | `integer` |  |  |   
| createdAt | `datetime` |  |  |   
| updatedAt | `datetime` |  |  |   

