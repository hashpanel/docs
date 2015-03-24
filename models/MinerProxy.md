### MinerProxy

A local hashpanel mining proxy. This allows data to be collected from miners on
a local subnet, but proxied upstream to a public server.

| config | value |
|:---|:---|
| rest? | `true` |
| table | `minerproxy` |
| extends | `` |
| autoPK | `true` |

| attribute | type | column | description |
|:---|:---|:---|:---| 
| name | `string` |  |  |   
| key | `string` |  |  |   
| miners | `Miner` |  |  |   
| createdBy | `User` |  |  |   
| owner | `User` |  |  |   
| id | `integer` |  |  |   
| createdAt | `datetime` |  |  |   
| updatedAt | `datetime` |  |  |   

