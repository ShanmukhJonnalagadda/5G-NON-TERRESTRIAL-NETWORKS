# Modulation and coding

Source: Section VI of the original report.

MCS combines a modulation order and coding rate. Link adaptation selects an MCS based on radio conditions and error performance. The report discusses a typical 10% BLER target as an example, not a universal requirement.

| Modulation | Uncoded bits per modulation symbol |
|---|---:|
| QPSK | 2 |
| 16-QAM | 4 |
| 64-QAM | 6 |
| 256-QAM | 8 |

Higher modulation orders can carry more bits per symbol but generally require better signal quality. Net throughput also depends on coding, overhead and resource allocation.

The report discusses PDSCH MCS tables in 3GPP TS 38.214, DCI over PDCCH, RRC configuration and RNTI-dependent table selection. Actual MCS table entries and reserved indices depend on the applicable specification and configuration.

No link-level BLER simulation or measured throughput data was supplied.
