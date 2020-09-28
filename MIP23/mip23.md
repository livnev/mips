# MIP23: Farmable Collateral Adapters (`CropJoin`)

## Preamble
```
MIP#: 23
Title: Farmable Collateral Adapters (`CropJoin`)
Author(s): Lev Livnev (@equivrel), ￼🌧️ McRainface
Contributors: n/a
Type: Technical
Status: Request for Comments (RFC)
Date Proposed: 2020-09-27
Date Ratified: <yyyy-mm-dd>
Dependencies: n/a
Replaces: n/a
License: AGPL3+
```
## References

- The proposed [cUsdcCropJoin](https://github.com/) implementation

## Sentence summary

This proposal provides a smart contract implementation of `CropJoin`, a module which XXX, allowing XXX.

## Paragraph summary

The Dai Stablecoin System is intended to XXX. Currently, XXXX. In contrast, XXX.

## Component summary

**MIP20c1: Definitions:** defines XXX, YYY, ...

**MIP20c2: Desired properties:** lists important properties that the implementation must satisfy.

**MIP20c3: Proposed code:** contains snippet of proposed implementation.

**MIP20c4: Test cases:** lists existing test cases, including integration test

**MIP20c5: Security considerations:** comments on the limited nature of the security implications of adding the XXX.

**MIP20c6: Other considerations:** describes the changes to governance of XXX, and contrasts the proposal in this MIP with XXX.

**MIP20c7: Formal verification/audit information:** comments on the amenability of the proposed code to formal verification, even though formal specification, audit, or code review have yet to be conducted.

**MIP20c8: Licensing:** states the license under which the proposal and code are distributed.


## Motivation

In an environment where the supply of DAI is too low to meet demand, XXX.

A crucial requirement in the implementation of this policy is XXX.

## Specification

### MIP20c1: Definitions

- **XXX**: YYY

### MIP20c2: Desired properties

- XXX

### MIP20c3: Proposed code
   see XXX. The core functionality is simple:

```
XXX
```

### MIP20c4: Test cases

see XXX

- `test_XXX`
- `test_mainnet_XXX` (this one is an integration test using the mainnet deployment of XXX)

### MIP20c5: Security considerations

The proposed solution is simple and non-invasive XXX.

### MIP20c6: Other considerations

Upon adoption of this MIP, XXX.

This MIP can be compared with XXX.

### MIP20c7: Formal verification/audit information

The proposed contract is written in a way which is amenable to formal specification and verification, in accordance with the style and practices of the core multi-collateral DAI contracts, though it has not been formally specified. No audit or code review has taken place yet.

### MIP20c8: Licensing
   - [AGPL3+](https://www.gnu.org/licenses/agpl-3.0.en.html)
