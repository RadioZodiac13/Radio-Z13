# Radio Z13

**Experimental research tools and documentation related to the Zodiac Z13 communication.**

This repository documents a research path, a family of experimental simulators, and the current state of an analog-instrument hypothesis developed around Z13.

> **Status:** experimental and unvalidated. This repository does **not** claim to present a demonstrated cryptographic solution or a proven identification of the sender of Z13.

## Working hypothesis

The starting hypothesis is that Z13 may be approached not only as text to decipher, but as a possible set of instructions whose operations require an appropriate analog tool or receiver.

The historical model is deliberately constrained to methods and instruments plausible in 1970: paper, pencil, clock/watch geometry, bezel rotation, circular scales, angular measurement, basic cryptography, and potentially relevant knowledge such as radar, naval navigation, Morse code, geometry, and astronomy.

The simulators were created later to reproduce, measure, and repeat those operations. They are experimental instruments, not evidence by themselves.

## Repository contents

- [`Radio_Z13_Research_Summary.pdf`](Radio_Z13_Research_Summary.pdf) — research summary for reading and distribution.
- [`Radio_Z13_Research_Summary.docx`](Radio_Z13_Research_Summary.docx) — editable version of the research summary.
- [`Radio_Z13_Simulator_1_Circular_Receiver.html`](Radio_Z13_Simulator_1_Circular_Receiver.html) — historical Phase 1 circular receiver.
- [`Radio_Z13_Simulator_2_GFRPOSTE_Sector.html`](Radio_Z13_Simulator_2_GFRPOSTE_Sector.html) — historical Phase 2 sector observation. The selection and order of the G.F.R.POSTE subset are **not demonstrated**.
- [`Radio_Z13_Simulator_3_Instrument_v0_9.html`](Radio_Z13_Simulator_3_Instrument_v0_9.html) — current frozen experimental instrument, version 0.9.
- [`README.docx`](README.docx) — Author's Note in English.
- [`LEEME.docx`](LEEME.docx) — Author's Note in Spanish.
- [`LICENSE.txt`](LICENSE.txt) — open-use terms with attribution.
- [`SHA256SUMS.txt`](SHA256SUMS.txt) — SHA-256 hashes for integrity checking.

## Current methodological position

The work preserves both successful and failed branches of the research path. Attractive results are not treated as validation merely because they can be produced by the instrument.

The Phase 2 instrument is frozen so that mechanical operation can be separated from cryptographic interpretation. Its state space reflects combinations of controls, not millions of independent cryptographic solutions.

The current tool measures directions and angular relationships. A complete reading rule has **not** been demonstrated, and important degrees of freedom remain unresolved. Independent reproduction, criticism, falsification, and expert review are therefore essential.

**The tool has been built; the reading rule has not.**

## Simulators

The three HTML files represent different stages of the same research path rather than competing solutions.

They can be downloaded and opened locally in a modern browser. A browser-accessible version can also be served through GitHub Pages.

## Release

The frozen package is available from the repository's **Releases** section as **Radio Z13 v1.0**.

## License

The material may be used, studied, copied, modified, and redistributed under the conditions described in [`LICENSE.txt`](LICENSE.txt). Published results and derivative versions must preserve the required attribution and must not present this research as a validated cryptographic solution unless independent evidence establishes that conclusion.

## Contact

**Radio Zodiac 13**  
radiozodiac13@gmail.com

Respect for the victims and their families is a standing condition of this project.
