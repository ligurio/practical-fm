## A List of companies that use formal verification methods in software engineering

If you see a company on the list that doesn't exist anymore, or does not use formal methods anymore,
please send a pull request with an explanation. The same goes if you're currently working at, or know a company that uses formal methods but is not on the list. Please include the website, github (if applicable), locations, and sector.
If the company is hiring please include a link to the ad.

| Name | Location | Sector | Source |
| :--- | :------- | :----- | :----- |
[Amazon](https://www.amazon.com/) | USA | eCommerce, Cloud computing | ```TLA+``` [How Amazon Web Services Uses Formal Methods](https://cacm.acm.org/magazines/2015/4/184701-how-amazon-web-services-uses-formal-methods/abstract), [Use of Formal Methods at Amazon Web Services](http://lamport.azurewebsites.net/tla/amazon.html)
[Airbus](http://www.airbus.com/) | France |  | ```Astrée```: "In 2003, Astrée proved the absence of any runtime errors in the primary flight-control software of an Airbus model. The system’s 132,000 lines of C code were analyzed completely automatically in only 80 minutes on a 2.8GHz 32-bit PC using 300MB of memory (and in only 50 minutes on an AMD Athlon 64 using 580MB of memory). Since then, Airbus France has been using Astrée in the development of safety-critical software for vari­ous plane series, including the A380.", ```Coq``` ([Interview with Xavier Leroy](https://www.cs.cmu.edu/~popl-interviews/leroy.html))
[Altran](https://www.altran.com/us/en/) | France, Paris |  | ```SPARK``` [SPARK contributors](http://www.spark-2014.org/contributors)
[Apple](https://www.apple.com/) | Santa Clara Valley, California, USA | Hardware and Software |
[ARM](https://www.arm.com/company) | USA, California, San Jose | Hardware | [Verifying against the official ARM specification](https://alastairreid.github.io/using-armarm/), ```TLA+``` [Linux Kernel](https://git.kernel.org/pub/scm/linux/kernel/git/cmarinas/kernel-tla.git/about/)
[AdaCore](http://www.adacore.com/company) | USA, New York | ? | ?
[Alacris](https://alacris.io/) | ? | Blockchain | | 
[BAE Systems](http://www.baesystems.com/en/home) | | | ```Coq``` [Reddit](https://www.reddit.com/r/Coq/comments/7ajnct/coq_in_industry/dpavptl/)
[Bedrock Systems](https://www.bedrocksystems.com/) | USA, Menlo Park, CA | ? | ? 
[The Boeing Company](http://www.boeing.com/) | USA | Aerospace, Defense |```Coq``` (no proof), ```Ivory``` ([source](https://github.com/GaloisInc/ivory/tree/master/ivory-paper))
[Bosch](https://www.bosch.com/) | Germany | Automotive | [Astrée](https://www.absint.com/bosch_as.htm)
[Centaur Technology](https://centtech.com/) | USA | Hardware | ``ACL2`` | ```ACL2``` [Industrial Use of ACL2]
[Cog Systems](https://cog.systems/) | Australia, New South Wales, Sydney | | [Site](https://cog.systems/d4-secure-sdk/)
[Data61](https://www.csiro.au/) | Australia | | ``` Isabelle/HOL``` ([The seL4 verification project](http://ts.data61.csiro.au/projects/seL4-verification/))
[Ethereum](https://ethereum.org/) | Switzerland | | ```Why3``` [Dev Update: Formal Methods](https://blog.ethereum.org/2016/09/01/formal-methods-roadmap/), ```Isabelle/HOL``` [A Lem formalization of EVM and some Isabelle/HOL proofs](https://github.com/pirapira/eth-isabelle), ```Coq``` [Formal Verification of Ethereum Contracts](https://github.com/pirapira/ethereum-formal-verification-overview)
[eSpark Learning](https://www.esparklearning.com/) | USA, IL, Chicago | Education | ```TLA+``` [Formal Methods in Practice: Using TLA+ at eSpark Learning](https://medium.com/espark-engineering-blog/formal-methods-in-practice-8f20d72bce4f)
[Elastic](https://www.elastic.co/) | Global | Search & analytics software | ```TLA+``` ```Isabelle/HOL``` [elasticsearch-formal-models repository](https://github.com/elastic/elasticsearch-formal-models) [conference talk](https://www.elastic.co/elasticon/conf/2018/sf/reliable-by-design-applying-formal-methods-to-distributed-systems) and [current open positions](https://www.elastic.co/about/careers#engineering)
[Facebook](https://www.facebook.com/) | USA |  | ```INFER``` [Moving Fast with Software Verification](https://research.fb.com/wp-content/uploads/2016/11/publication00124_download0001.pdf)
[FireEye](https://www.fireeye.com/) | Dresden, Germany (team defunct) | Security | ```Coq``` [Job announcement: formal methods engineer and scientific developer at FireEye](https://coq-club.inria.narkive.com/KjBqxSSI/job-announcement-formal-methods-engineer-and-scientific-developer-at-fireeye)
[FinProof](https://finproof.io/v2/) | Russia, SPb | Finance (Blockchain) | ```Coq```, ```Agda```
[Galois](https://galois.com) | Portland, Oregon, USA | Consulting/Research | ```Coq``` (?)
[Google](https://google.com/) | CA, USA | Cloud computing, Computer software, AI | ```Coq``` ([Simple High-Level Code For Cryptographic Arithmetic – With Proofs, Without Compromises](http://adam.chlipala.net/papers/FiatCryptoSP19/FiatCryptoSP19.pdf) (Chromium))
[Grammatech](https://www.grammatech.com/about) | | | ```Frama-C``` [C Library annotations in ACSL for Frama-C: experience report](http://annotationsforall.org/resources/links/GT-libc-experience-report.pdf)
[Green Hills Software](https://www.ghs.com/) | USA | Aerospace | ```ACL2``` [Industrial Use of ACL2](http://www.cs.man.ac.uk/~regerg/arcade/papers/paper_12.pdf)
IBM | USA | ? | ```SPIN/Promela``` [Paul E. McKenney's Journal](https://paulmck.livejournal.com/tag/promela), [What is RCU, Fundamentally?](https://lwn.net/Articles/262464/) (Linux Kernel, RCU)
[Intel](https://www.intel.com/) | USA | Hardware | `Prover` ([Fifteen Years of Formal Property Verification in Intel](https://link.springer.com/chapter/10.1007%2F978-3-540-69850-0_8?LI=true)), `HOL Light` ([Formal verification of IA-64 division algorithms](https://www.cl.cam.ac.uk/~jrh13/papers/hol00.html))
[InfoTecs](https://infotecs.ru/) | Russia, Moscow |  |  ```TLA+```, ```Coq```, [Construction and formal verification of a fault-tolerant distributed mutual exclusion algorithm](https://dl.acm.org/citation.cfm?doid=3123569.3123571), [Построение и верификация отказоустойчивого алгоритма распределенной блокировки](https://osday.ru/presentations/day1/Shishkin.pdf)
[ISP RAS](http://ispras.ru/) | Moscow, Russia | Operating systems; hardware | ```Frama-C```, ```Jessie```, ```Why3``` [Astraver](https://forge.ispras.ru/projects/astraver), [Linux kernel library functions formally verified](https://github.com/evdenis/verker); ```SPIN/Promela```, ```Microtesk``` [Site](http://microtesk.org/); ```Event-B``` [Моделирование и верификация политик безопасности управления доступом в операционных системах](http://www.ispras.ru/publications/2018/security_policy_modeling_and_verification/), [part of the Event-B specification](https://github.com/17451k/base-model); ```Isabelle/HOL``` [Formal specification of the Cap9 kernel](https://github.com/Daohub-io/cap9-spec)
[Kernkonzept](https://www.kernkonzept.com/) | Germany | Operating systems | [Site](https://www.kernkonzept.com/)
[Kaspersky Lab](https://www.kaspersky.com) | Moscow, Russia | Security/AV | [Что представляет собой операционная система Kaspesky OS?](https://xakep.ru/2012/11/26/kaspersky-os/), ```Ivory``` ([source](https://ruhaskell.org/posts/talks/2016/08/18/ivory-high-performance-code-for-haskell.html))
[Machine Zone Inc.](https://www.mz.com/) | Russia | Mobile gaming software, Real-time computing, Cloud-based networking  | ```TLA+``` [Twitter](https://twitter.com/levwalkin/status/827129877186752513)
[Microsoft](https://www.microsoft.com/) | Redmond, USA | Software development | ```TLA+``` [TLA+ Proofs](https://www.microsoft.com/en-us/research/publication/tla-proofs/), [Thinking for Programmers](https://channel9.msdn.com/Events/Build/2014/3-642#time=21m46s), [High-level TLA+ specifications for the five consistency levels offered by Azure Cosmos DB](https://github.com/Azure/azure-cosmos-tla), ```Microsoft’s Static Driver Verifier``` [Thorough static analysis of device drivers](https://www.microsoft.com/en-us/research/publication/thorough-static-analysis-of-device-drivers/)
MongoDB | New York, USA | Software development | ```TLA+``` [TLA+ Spec of a simplified part of MongoDB replication system](https://github.com/visualzhou/mongo-repl-tla)
NASA | USA | Space | ```PVS``` [NASA Langley Formal Methods Research Program](https://shemesh.larc.nasa.gov/fm/). ```JPF``` [Java Pathfinder](https://en.wikipedia.org/wiki/Java_Pathfinder),  [Robust Software Engineering Group](https://ti.arc.nasa.gov/tech/rse/),  ```Model Checking``` [Jet Propulsion Laboratory](https://lars-lab.jpl.nasa.gov/projects.html), ```SPIN/Promela``` [Inspiring Applications of Spin](http://spinroot.com/spin/success.html), ```PVS``` ([source](https://www.eeweb.com/profile/adarbari/articles/a-brief-history-of-formal-verification))
[Oracle](https://www.oracle.com/) | Redwood Shores, CA, USA | Enterprise software, Cloud computing, Computer hardware | `ACL2` ([Proving Theorems about Java and the JVM with ACL2](https://www.cs.utexas.edu/users/moore/publications/marktoberdorf-02/index.html))
[Particular Software](https://particular.net/) | | | ```TLA+``` [TLA+ Specifications for NServiceBus](https://github.com/tmasternak/NServiceBus.ModelChecking)
PingCAP | | | ```TLA+``` [TLA+ in TiDB](https://github.com/pingcap/tla-plus)
[Rockwell Collins](https://www.rockwellcollins.com/) | USA, Cedar Rapids, Iowa | High Assurance Systems | [Formal Methods in the Aerospace Industry: Follow the Money](http://www.jaist.ac.jp/icfem2012/Cofer-ICFEM2012.pdf)
[Synopsis](https://www.synopsys.com/) | ? | ? | [Site](https://www.synopsys.com/verification.html)
[SiFive](https://www.sifive.com) | USA, San Francisco Bay Area | Hardware | ```Coq``` [LinkedIn](https://www.linkedin.com/jobs/view/coq-proof-assistant-based-formal-verification-at-sifive-800018056/)
[Statebox](https://statebox.org/) | Amsterdam, Netherlands | Blockchain | ```Idris``` ([github](https://github.com/statebox)) 
[Sukhoi](https://www.sukhoi.org/) | Russia, Moscow | Aerospace and defense | [```ANSYS SCADE Suite```](https://www.ansys.com/products/embedded-software/ansys-scade-suite) (source - [A Formally Verified Compiler for Lustre](http://www.tbrk.org/papers/pldi17-slides.pdf)) 
[TrustInSoft](https://trust-in-soft.com/) | USA, CA, San Francisco | - | ```TrustInSoft Analyzer``` [Site](https://trust-in-soft.com/polarssl-verification-kit/)
[Trustworthy Systems](https://ts.data61.csiro.au/) | Australia, Sydney  |  | ```Isabelle/HOL```, ```Coq``` [Site](https://ts.data61.csiro.au/projects/TS/l4.verified/)
[JetBrains](https://jetbrains.org) | Saint Petersburg, Russia | - | [Site](https://research.jetbrains.org/ru/groups/group-for-dependent-types-and-hott)
[МЦСТ](http://www.mcst.ru/) | Moscow, Russia | ? | ```SPIN/Promela``` [Методы и средства верификации протоколов когерентности памяти](https://www.youtube.com/watch?v=67eD3hLmU_8&t=43s)
[T-Platforms](https://www.t-platforms.ru/) | Moscow, Russia | - | ```Coq```, ```SPIN/Promela```, ```TLA+```, ```McErlang```, ```mCRL2``` [Employee CV](https://ru.linkedin.com/in/evgeniy-shishkin-9b1b67b3)
CERN | Genève, Switzerland | | ```mCRL2``` [Control Software of the CMS Experiment at CERN’s Large Hadron Collider](https://www.mcrl2.org/web/user_manual/showcases/CMS.html)
[Zilliqa](https://zilliqa.com/) | Singapore | Blockchain | ```Coq``` [scilla-coq project](https://github.com/Zilliqa/scilla-coq)

### See also

* [Formal Methods Companies](http://formalmethods.wikia.com/wiki/Companies) (outdated)
* Open vacancies on [indeed.com](https://www.indeed.com/q-Logic-Formal-Verification-jobs.html)
* [Formal Methods:  Practice and Experience](https://www-users.cs.york.ac.uk/~jw524/papers/WoodcockLBF09.pdf)
* http://alloytools.org/citations/case-studies.html
* [Overview of formal methods in software engineering](https://www.foi.se/rest-api/report/FOI-R--4156--SE)
