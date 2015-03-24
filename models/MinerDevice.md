### MinerDevice

The device (hardware) specification for a `Miner` connected to hashpanel.

| config | value |
|:---|:---|
| rest? | `true` |
| table | `minerdevice` |
| extends | `` |
| autoPK | `false` |

| attribute | type | column | description |
|:---|:---|:---|:---| 
| name | `string` |  |  |   
| manufacturer | `string` |  |  |   
| hashRate | `float` |  |  |   
| wattage | `integer` |  |  |   
| voltage | `float` |  |  |   
| algorithm | `string` |  |  |   
| website | `string` |  |  |   
| releaseDate | `date` |  |  |   
| miners | `Miner` |  |  |   
