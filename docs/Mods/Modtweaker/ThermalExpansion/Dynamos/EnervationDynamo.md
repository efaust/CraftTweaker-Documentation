# Enervation Dynamo

## Import the package
To shorten method calls you can [import](/AdvancedFunctions/Import/) the package like so:  
```zenscript
import mods.thermalexpansion.EnervationDynamo;
```


## Add Fuel

```zenscript
//mods.thermalexpansion.EnervationDynamo.addFuel(ILiquidStack stack, int energy);
mods.thermalexpansion.EnervationDynamo.addFuel(<liquid:water>, 13);
```

## Remove Fuel

```zenscript
//mods.thermalexpansion.EnervationDynamo.removeFuel(ILiquidStack stack);
mods.thermalexpansion.EnervationDynamo.removeFuel(<liquid:water>);
```