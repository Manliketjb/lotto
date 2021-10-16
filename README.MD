## lottoscript converted by Captainrum89, Updated by ManLikeTJB

First of all **DONT** rename the folder (lotto).
just upload the lotto into your recources.

## Requirements
- QbCore framework (https://github.com/qbcore-framework)
- none

## Setup
1. Download or clone this repository inside your resources folder
2. Remove the "-main" part from folder name
3. Upload the **lotto.png** into your **inventory/html/images** folder
4. Add a line to your server.cfg file -> **start qb-carrobbery**
5. ADD *see below* to your **qb-core/shared.lua**

```
["lotto"] = {
  ["name"] = "lotto",
  ["label"] = "Lotto ticket",
  ["weight"] = 10,
  ["type"] = "item", 
  ["image"] = "lotto.png",
  ["unique"] = false, 
  ["useable"] = true, 
  ["shouldClose"] = true,  
  ["combinable"] = nil,  
  ["description"] = "Lucky Ticket"},
 ```
 
## Win screen
https://media.giphy.com/media/tupEdbE0QE6USnbZsr/source.gif

## Lost screen
https://media.giphy.com/media/l1Kx74oMJweCiFZOL6/source.gif

``` 
Credits to the original author for the script.

DO NOT SELL THIS SCRIPT, ITS FREE FOR QBCORE COMMUNITY 
```
