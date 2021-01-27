### mizubot doc
mizubot is to set your own scan point and notification filter with set center point in radius. scan point will be scanned every 10 mimutes.
<br><br>
### Procedure
1. Set scan point with
    `$scan latitude longitude` 
2. Set notification center with `$center latitude longitude (radius)`. radius is in meter and optional. If not set 100 meter is used as default. mizubot will look for pokemons and raids within the set center and radius. 
3. 
**Scan command**
***
**Set scan point** <br>
`$scan latitude longitude` <br>
Example <br>
`$scan 41.591201 -93.603763` <br>
<br>
**Delete scan point** <br>
`$delscan` <br>
<br>
**Check current scan point** <br>
`$checkscan` <br>
<br>

**Nortification command**
***
**Set notification center** <br>
`$center latitude longitude (radius)` <br>
radius in meter is optional. If not set 100 meter will be used as default notification center. <br><br>
**Check center** <br>
`$checkcenter` <br><br>
**Pause all notification** <br>
`$pause` <br><br>
**Unpause notification** <br>
`$unpause` <br><br>
<br>

**




