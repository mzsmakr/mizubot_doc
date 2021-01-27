### mizubot doc
mizubot is to set your own scan point and notification filter with set center point in radius. scan point will be scanned every 10 mimutes.
<br><br>
### Procedure
1 Set scan point with
```
$scan latitude longitude
``` 
2 Set notification center with 
```
$center latitude longitude (radius)
```
radius is in meter and optional. If not set 100 meter is used as default. mizubot will look for pokemons and raids within the set center and radius. <br><br>
3 Set notification filters <br>
**pokemon notification** <br>
3-1 Create filter by
```
$createfilter
```
This command will create filter `1` <br>
3-2 Add pokemon
```
$addpoke filternum pokemonname
```
Example
```
$addpoke 1 Larvitor
```
will add Larvitor to filter 1 <br>
`all` to get all pokemon. You can add as many pokemons as you want to the filter. <br><br>
3-3 Adjust radius for the filter <br>
```
$setrad filternum radius
```
Example<br>
```
$setrad 1 70
```
will set 70 meter radius to filter 1. <br><br>
3-4 Set IV to the filter <br>
```
$setiv filternum miniv maxiv
```
to set min/max iv to the filter. <br>
Example
```
$setiv 1 90 100
```
will get you notification between 90-100% iv pokemons. <br>
Available parameters are <br>
attack :&nbsp;&nbsp;&nbsp;`$setatk filter min max`<br>
defence: `$setdef filter min max`<br>
stamina: `$setsta filter min max`<br>
CP:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`$setcp filter min max` <br>
setlevel:&nbsp;&nbsp;`$setlevel filter min max`<br>


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




