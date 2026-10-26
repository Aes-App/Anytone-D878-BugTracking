# AnyTone D878UV / D878UVII Firmware Bug Tracking

**Model:** AnyTone AT-D878UVII (D878UV Plus series), and the gen-1 AT-D878UV where noted

**Firmware:** V4.01a, image `D878UVII_V4.01a_20251103.CDD` (GigaDevice). The gen-1 AT-D878UV V4.01a image `D878UV_V4.01a_20251103.CDD` is built from the same program, but the issues are written against the D878UVII image and have not been checked one by one on the gen-1 build.

**Method:** Static reverse engineering of the firmware image (disassembly and decompilation). Each finding is re-checked against the disassembly and reviewed independently; some need a check on a physical radio. Each issue says which.

**Purpose:** Bug tracking. Each issue describes one bug, dead-code path or notable behaviour found in this firmware, with where it is, what it does, how to reproduce it and how to verify it, so others can review and contribute.

**Labels:** `functional` (user-visible), `memory-safety`, `latent` (limited/no current impact), `dead-code`, plus `verified` / `unconfirmed` and `needs-radio-test`.

Function and variable names in the issues are reverse-engineering labels, not AnyTone's own names. I will try to report these to AnyTone first. The RE source is not published.
