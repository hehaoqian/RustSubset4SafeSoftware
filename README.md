# RustSubset4SafeSoftware
[RS3]: #rs3

This shall be a collection of rules that restrict Rust to a common ruleset
that enables the development of software that has to fulfill functional
safety requirements.


## Table of Contents
[Table of Contents]: #table-of-contents

  - [Opening](#rs3)
  - [Table of Contents]
  - [Applicable domains]
  - [License]

## Applicable domains
[Applicable domains]: #applicable-domains

The domains that are targeted by this Rust subset are mainly:
- Automotive: [ISO26262](https://www.iso.org/standard/68383.html)
- Aerospace: [DO-178C](https://en.wikipedia.org/wiki/DO-178C)
- General: [IEC 61508](https://www.iec.ch/functionalsafety/)

## Similar subsets
[Similar subsets]: #similar-subsets

- C
    - [MISRA C](https://www.misra.org.uk/Activities/MISRAC/tabid/160/Default.aspx)

- C++
    - [MISRA C++](https://www.misra.org.uk/Activities/MISRAC/tabid/171/Default.aspx) (C++98)
    - [AUTOSAR Guidelines for the use of the C++14 language in critical and safety-related systems](https://www.autosar.org/fileadmin/user_upload/standards/adaptive/17-10/AUTOSAR_RS_CPP14Guidelines.pdf)
    - [High Integrity C++ Coding Standard](https://www.perforce.com/resources/qac/high-integrity-cpp-coding-standard)
    - [SEI CERT C++ Coding Standard](https://resources.sei.cmu.edu/downloads/secure-coding/assets/sei-cert-cpp-coding-standard-2016-v01.pdf)
    - [Joint Strike Fighter AIR VEHICLE C++ CODING STANDARDS](http://www.stroustrup.com/JSF-AV-rules.pdf)

- Ada
    - [NASA Flight Software Branch Ada Coding Standard](https://web.archive.org/web/20100527142102/http://software.gsfc.nasa.gov/AssetsApproved/PA2.4.1.1.1.pdf)

## License
[License]: #license

This repository is currently in the process of being licensed under either of:

* Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
* MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contributions

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.