kikit separate --source 'annotation; ref: B1' ZakladniElektronika.kicad_pcb jlcout/build/HlavniDeska.kicad_pcb
kikit separate --source 'annotation; ref: B2' ZakladniElektronika.kicad_pcb jlcout/build/LedDeska.kicad_pcb

kikit fab jlcpcb --no-drc --assembly --schematic ZakladniElektronika.kicad_sch jlcout/build/HlavniDeska.kicad_pcb jlcout/HlavniDeska
kikit fab jlcpcb --no-drc --assembly --schematic ZakladniElektronika.kicad_sch jlcout/build/LedDeska.kicad_pcb jlcout/LedDeska
