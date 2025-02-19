# [rusEFI project](rusEFI-project)
## Ignition
[Ignition settings](#ignition-settings)

[Dwell](#dwell)

[Ignition Cylinder Extra Timing](#ignition-cylinder-extra-timing)

[Ignition Table](#ignition-table)

[Warmup timing correction](#warmup-timing-correction)

[Ignition Intake Air Temp correction](#ignition-intake-air-temp-correction)

### Ignition settings
![x](overview/TS_generated/dialog_Ignition_settings.png)

Two wire wasted: This is needed if your coils are individually wired (COP) and you wish to use batch ignition (wasted spark).

Timing Mode: Dynamic uses the timing map to decide the ignition timing, Static timing fixes the timing to the value set below (only use for checking static timing).

Use TPS-based Advance Table: This flag allows to use TPS for ignition lookup while in Speed Density Fuel Mode

Dizzy out Pin: This implementation makes a pulse every time one of the coils is charged, using coil dwell for pulse width. See also tachOutputPin

### Dwell
![x](overview/TS_generated/dialog_Dwell.png)

### Ignition Cylinder Extra Timing
![x](overview/TS_generated/dialog_Ignition_Cylinder_Extra_Timing.png)

### Ignition Table
![x](overview/TS_generated/dialog_Ignition_Table.png)

### Warmup timing correction
![x](overview/TS_generated/dialog_Warmup_timing_correction.png)

### Ignition Intake Air Temp correction
![x](overview/TS_generated/dialog_Ignition_Intake_Air_Temp_correction.png)


generated by class com.rusefi.MdGenerator on Fri May 01 15:24:28 EDT 2020
