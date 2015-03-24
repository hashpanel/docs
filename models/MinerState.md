### MinerState

The state of a physical `Miner` at a given point in time, essentialized by the
status response from cgminer. These states are saved and constitute the
"history" of a `Miner`.

| config | value |
|:---|:---|
| rest? | `true` |
| table | `minerstate` |
| extends | `` |
| autoPK | `true` |

| attribute | type | column | description |
|:---|:---|:---|:---| 
| success | `boolean` |  |  |   
| error | `json` |  |  |   
| version | `json` |  |  |   
| summary | `json` |  |  |   
| devs | `json` |  |  |   
| event | `string` |  |  |   
| miner | `Miner` |  |  |   
| id | `integer` |  |  |   
| createdAt | `datetime` |  |  |   

