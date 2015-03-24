### Pool

Specification (connection information) for a mining pool that hashpanel Miners
can connect to.

| config | value |
|:---|:---|
| rest? | `true` |
| table | `pool` |
| extends | `` |
| autoPK | `false` |

| attribute | type | column | description |
|:---|:---|:---|:---| 
| name | `string` |  |  |   
| url | `string` |  |  |   
| workers | `PoolWorker` |  |  |   
