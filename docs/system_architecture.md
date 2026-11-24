# System architecture

Source: original report, Sections I–II and IV.

5G NTN supplements terrestrial cellular coverage with airborne or spaceborne nodes. User equipment (UE) communicates through a service link to a satellite; a feeder link connects the satellite to a terrestrial gateway.

## Transparent payload

A relay forwards radio signals between UE and gateway, with gNB processing on the ground. See the [conceptual diagram](../images/transparent_payload.svg). This reduces onboard base-station processing, but depends on the ground infrastructure and feeder link.

## Regenerative payload

The satellite performs onboard processing, potentially hosting gNB functions. See the [conceptual diagram](../images/regenerative_payload.svg). Processing placement changes routing, timing and onboard resource requirements. Exact function splits depend on implementation.

## Service variants

- NTN-IoT: remote sensing and low-rate device connectivity.
- NTN-NR: integration with 5G New Radio for compatible terminals and gateways.
- HAPS: aerial platforms complement satellite and terrestrial coverage.

The original paper includes an industry architecture illustration on page 1; the SVGs here are newly drawn conceptual summaries, not reproductions of that figure.
