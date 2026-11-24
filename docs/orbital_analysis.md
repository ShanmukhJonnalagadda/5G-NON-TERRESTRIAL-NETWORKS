# Orbital analysis

Source: Sections IV–V of the original report.

| Platform | Illustrative altitude from report | Engineering trade-off |
|---|---|---|
| LEO | 600 km example | Shorter path; rapid motion and handovers |
| MEO | 10,000 km example | Intermediate distance and propagation delay |
| GEO | 35,786 km | Wide footprint; longer propagation path |
| HAPS | Not specified | Aerial coverage; platform resource constraints |

The report discusses illustrative transmission-delay values of 14.2 ms for a 600 km LEO case, 95.2 ms for MEO, 272.4 ms for GEO, and 1.526 ms for HAPS. These are quoted research examples, not measurements or directly comparable one-way zenith delays; their path geometry and timing definitions are not fully specified in the paper.

## Challenges

- Propagation delay affects signaling, access, handover and HARQ.
- Doppler shift varies with relative velocity and carrier frequency; the paper discusses GNSS-based compensation and residual receiver corrections.
- OFDM PAPR places demands on payload power amplifiers; the report discusses clipping and array-based approaches.
- Hierarchical constellations introduce inter-layer connectivity and coordination opportunities.

No orbit propagation model or measured delay dataset was supplied with the original work.
