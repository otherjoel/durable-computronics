# “Durable Computronics” [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](CODE_OF_CONDUCT.md)

*Durable computronics* is a placeholder name for a fantasy ethos of computing (embodied in a fantasy
set of institutions) that favors reliability, security, personal accountability and simplicity over
functionality and innovation. 

I have no vision for seeing this implemented in the real world and do not pretend that it is
feasible given the current landscape of incentives. Again, this is fantasy; approach it as
a creative “world-building” exercise for a speculative civilization, rather than as a serious policy
proposal. I would simply like to imagine a set of rules and institutions that might give rise to
a world where “software engineering” as a profession actually does carry the same legal and
scientific rigor required of electrical engineers, structural engineers, mechanical engineers, civic
engineers, etc.; where the pace of change in technology is much slower; and where technology is an
evergreen structural support to a way of life.

Contributions and pull requests are welcome. By contributing, you agree to follow the [Code of
Conduct][1] and that you license your contribution under the same license used by the rest of the
project. Please also consider publicly signing the [Single CLA](https://singlecla.com).

[1]: CODE_OF_CONDUCT.md

### Informative examples in history and fiction

* Computers in [Maniac][2], which rely heavily on mechanical inputs, and use screens almost entirely
  as dumb pixel buffers
* The Commodore 64 caked with dust and fine oil droplets that has seen active use in an auto repair
  shop for the last four decades
* The computers that control your car 
* Real-time operating systems
* The [“network
  ban”](https://scifi.stackexchange.com/questions/54734/making-sense-of-battlestar-galacticas-network-ban)
  in Battlestar Galactica (disclaimer, I haven’t actually watched the show) 

[2]: https://en.wikipedia.org/wiki/Maniac_(miniseries)

## Professional licensing and liability

The design of computational electronics, including software and interfaces, placed into use by any
person other than the designer or their adult partner(s), must be signed by a licensed Computer
Engineer (the engineer of record), as well as reviewed and approved by a public official (who shall
also be a licensed Computer Engineer). The engineer of record is personally liable for each separate
failure event of any system built according to their designs. If a system deviates from its design,
the contractor becomes liable for any such failure, whether related to the specific deviation or
not.

A design may include other certified hardware or software designs as components or layers, but
liability for failures in a design remains fully with that design’s engineer of record; it cannot
legally be passed through to its components’ engineer of record.

### Personal use

People are free to design and operate electronics of any kind for their own use or the use of other
adults residing with them, for any otherwise legal purpose, without formal training or
certification.

## Designs

Designs constitute hardware, source code *and* documentation; where certification is required, the
entire stack is reviewed and certified as a single design.

The sale or distribution of general-purpose hardware components without accompanying software, user
interface and documentation is prohibited.

The documentation must specifically address each of these areas:

* Authorized access and operation
* Information preservation (including integrity/interference guarantees)
* Environmental tolerances
* Interactions and designed behavior

Designs are categorized in Rings according to their intended use:

* **Ring 0**: Power generation and distribution; any medical use; operation of any transport faster
  than 10 km/hour, or over/through water at any speed, or more than six meters above the ground at
  any speed

* **Ring 1**: Storage and retrieval of any non-public information; measurement and/or display of
  time, weather, market prices, or any other public data used to coordinate and direct activity

Both hardware and software must be provably correct according to the criteria given in its
documentation *and* the minimum requirements (*TK*) for its ring level.

## Software and source code distribution

Software may be distributed, in source code or binary form, separately from hardware, without
licensing, certification or documentation requirements.

Any software placed into use on a non-personal system, or for any business purpose, must be part of
a formal design signed by an engineer of record and reviewed/approved by public officials.
Accordingly, commercially available software must have its complete source code available to
licensees.
