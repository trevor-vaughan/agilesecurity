Despite decades of investment, traditional reactive cybersecurity approaches such as firewalls, anti-virus, and analytics continue to fail to keep systems secure. Agile Security seeks to create software that is fundamentally resilient to cyberattacks yet practical and easy to implement.

These seven principles are guideposts to implementing agile security for software systems, from Internet of Things to cloud applications. A truly secure software system employs all seven, as each principle reinforces the others. As with Agile Engineering approaches, however, it is still worthwhile to incrementally adopt these principles.

Principles of Agile Security
-------

#### Be Diverse: Monoculture is deadly
In agriculture, a single-variety crop is extremely vulnerable to large-scale loss when a new crop disease breaks out. Cyberattacks are like diseases engineered to attack a weakness in a particular set of bits. Why run the exact same set of bits as available to hackers? Moving target defense technologies such as binary scrambling can automatically and transparently create polymorphic software. Polymorphic software is diverse internally (e.g. binaries, protocols, configurations) but semantically equivalent for seamless compatibility.

#### Be Dynamic: “Standing Still” rhymes with “Hit Me!”
Every boxer quickly learns that you are harder to hit if you are moving in an unpredictable manner. Stationary servers and services are inviting targets just waiting to be hit. Moving target defense techniques can create unpredictable system dynamism—changes in IP addresses, server images, security keys, data locations, binaries, etc.—that makes systems unrecognizable and resilient to cookie cutter threats, all while preserving ease of use for legitimate operators.

#### Be Minimal: small, focused systems win
Size and complexity adds risk. Avoid huge, monolithic software and instead engineer your systems and interfaces to present as small a profile as possible to the attacker. Small is easier to debug, verify, operate, scale and monitor.

#### Be Repeatable: Know what you run and run what you know
Traditional approaches of monolithic operating systems and hand-installed configurations yield errors and room for attackers to hide. The entirety of a software system—both code and configuration—should be completely described in a traceable manner so that you can accurately reproduce and analyze issues as they arise and completely understand what changed.

#### Be Validated: Attackers use validation tools to find flaws, why don’t you?
Attackers search for and exploit flaws in code and systems. Like spellcheck for documents, software and configuration validation tools and processes can analyze, identify, and even fix flaws. These tools should be used to eliminate large classes of easily preventable hacks, and integrated into the engineering pipeline.

#### Be Encrypted: Exposed data is just that
Encrypt all data by default throughout its full lifecycle—at rest, in transit, and even in memory. Processing of unencrypted data should be done in as minimal and constrained environments as possible. Publicly shareable and auditable encryption schemes (e.g. blockchain and the like) should be used where appropriate.

#### Be Compartmentalized: Eliminate single points of failure
Security is only as strong as the weakest link—assume that weak leak will be found! User authentication should be multi-factor or better; complex systems should be partitioned into smaller, more manageable and individually defended units; per-field and per role permissions should be used to compartmentalize access to data; use a two-person rule or separation of duties so that no single sysadmin, entity or key should has all powerful access to the entirety of a system.

About
-----

Agile Security specification is sponsored by [Polyverse Corporation](https://polyverse.io).

If you'd like to leave feedback, please [open an issue on
GitHub](https://github.com/polyverse-security/agilesecurity/issues).


License
-------

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Creative Commons - Attribution 4.0 International (CC BY 4.0)
https://creativecommons.org/licenses/by/4.0/
