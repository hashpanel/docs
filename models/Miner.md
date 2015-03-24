### Miner

A physical bitcoin miner that is producing hashes. A `Miner` is connected to
hashpanel by providing the hostname/ip address and port through which the
cgminer rpc api can be reached. Updates to the model are simultaneously
reflected in persistence to the database as well as a cgminer API call to the
actual physical miner.

| config | value |
|:---|:---|
| rest? | `true` |
| table | `miner` |
| extends | `` |
| autoPK | `true` |

| attribute | type | column | description |
|:---|:---|:---|:---| 
| name | `string` |  |  |   
| device | `MinerDevice` |  |  |   
| proxy | `MinerProxy` |  |  |   
| notes | `text` |  |  |   
| hashRate | `float` |  |  |   
| purchasePrice | `float` |  |  |   
| monthlyFee | `float` |  |  |   
| beginService | `date` |  |  |   
| endService | `date` |  |  |   
| host | `string` |  |  |   
| port | `integer` |  |  |   
| internalAddress | `string` |  |  |   
| site | `Site` |  |  |   
| group | `Group` |  |  |   
| state | `MinerState` |  |  |   
| history | `MinerState` |  |  |   
| interval | `integer` |  |  |   
| workers | `PoolWorker` |  |  |   
| createdBy | `User` |  |  |   
| owner | `User` |  |  |   
| id | `integer` |  |  |   
| createdAt | `datetime` |  |  |   
| updatedAt | `datetime` |  |  |   
