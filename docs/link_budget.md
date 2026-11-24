# Link budget considerations

Source: Section VII of the original report.

A link budget accounts for transmitted power, antenna gains and losses along the radio path to assess received signal strength.

- Orbit and altitude: distance affects free-space loss and propagation delay.
- Antenna design: directional gain improves the link when pointing is maintained.
- Atmospheric effects: rainfall may attenuate signals, especially at higher frequencies.
- Interference: margins must account for competing transmissions and network coordination.

## Optional analytical extension (not part of original results)

A basic received-power model is `Pr_dBm = Pt_dBm + Gt_dBi + Gr_dBi - Ltotal_dB`. For free-space propagation, `FSPL_dB = 92.45 + 20 log10(d_km) + 20 log10(f_GHz)`.

A full design also needs a defined geometry, carrier frequency, bandwidth, noise temperature, receiver sensitivity, atmospheric losses, pointing losses and required link margin. No numerical link budget or validated RF measurements were provided in the paper.

