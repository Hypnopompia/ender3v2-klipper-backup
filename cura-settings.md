# Start gcode
```
;Filament name = {material_name}
;Filament type = {material_type}
;Filament weight = {filament_weight}
;Nozzle diameter = {machine_nozzle_size}
;Extruder temp
;M109 S{material_print_temperature_layer_0}
;Bed temp
;M190 S{material_bed_temperature_layer_0}
START_PRINT BED_TEMP={material_bed_temperature_layer_0} EXTRUDER_TEMP={material_print_temperature_layer_0}
```

# End gcode
```
END_PRINT
```
