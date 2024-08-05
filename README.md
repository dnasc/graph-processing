# Graph Processing Platforms

Efficient processing of large graphs is challenging. With current data availability, real network traces are increasing in variety and volume, making it imperative to design solutions and systems based on parallel and distributed technologies. High-performance methodologies have the potential to benefit the graph processing community in much the same way they have advanced scientific computing. However, despite the success of high-performance computing in demanding scientific applications, graph analytics faces unique difficulties due to its data-driven nature, such as a high data-access to computing ratio and poor memory access locality.

Moreover, as the complexity of analysis increases, developing new solutions from scratch becomes increasingly demanding. This necessity underscores the importance of adopting software platforms—such as DBMS, frameworks, and libraries—to ease the development burden. Consequently, many data-oriented and graph-specific platforms have been proposed. We estimate that there are currently more than 180 platforms available for use in graph analytic tasks.

|**Platform Reference**                                                                                                         |**Year**|
|-----------------------------------------------------------------------------------------------------------------------------------|----|
|[LUMOS: Dependency-Driven Disk-based Graph Processing](https://www.usenix.org/conference/atc19/presentation/vora) |2019|
|[Fbsgraph: Accelerating Asynchronous Graph Processing Via Forward And Backward Sweeping](https://ieeexplore.ieee.org/document/8170287/) |2018|
|[GrapH: Traffic-Aware Graph Processing](https://ieeexplore.ieee.org/document/8263157)                                              |2018|
|[GraphD: Distributed Vertex-Centric Graph Processing Beyond The Memory Limit](https://ieeexplore.ieee.org/document/8016377)                                                        |2018|
|[HyVE: Hybrid Vertex-Edge Memory Hierarchy For Energy-Efficient Graph Processing](https://ieeexplore.ieee.org/document/8342150)                                                    |2018|
|[L-Powergraph: A Lightweight Distributed Graph-Parallel Communication Mechanism](https://link.springer.com/article/10.1007/s11227-018-2359-9)                                                     |2018|
|[La3: A Scalable Link- And Locality-Aware Linear Algebra-Based Graph Analytics System](https://dl.acm.org/citation.cfm?id=3228395)                                               |2018|
|[Lazygraph: Lazy Data Coherency For Replicas In Distributed Graph-Parallel Computation](https://dl.acm.org/citation.cfm?id=3178508)                                              |2018|
|[SHMEMGraph: Efficient And Balanced Graph Processing Using One-Sided Communication](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8411067)                                                  |2018|
|[Turbograph++: A Scalable And Fast Graph Analytics System](https://dl.acm.org/citation.cfm?id=3183713.3196915)                                                                           |2018|
|[Wonderland: A Novel Abstraction-Based Out-Of-Core Graph Processing System](https://dl.acm.org/citation.cfm?id=3173208)                                                          |2018|
|                                                                                                                                   |    |
|[A Distributed Multi-GPU System For Fast Graph Processing](https://dl.acm.org/citation.cfm?id=3173079)                                                                           |2017|
|[BlockGraphChi: Enabling Block Update In Out-Of-Core Graph Processing](https://link.springer.com/article/10.1007/s10766-017-0532-z)                                                               |2017|
|[Cypher-Based Graph Pattern Matching In Gradoop](https://dl.acm.org/citation.cfm?id=3078450)                                                                                    |2017|
|[Foregraph Exploring Large Scale Graph Processing On Multi FPGA Architecture](https://dl.acm.org/citation.cfm?id=3021739)                                                        |2017|
|[Frog: Asynchronous Graph Processing On Gpu With Hybrid Coloring Model](https://ieeexplore.ieee.org/document/8017445)                                                              |2017|
|[G-Thinker: Big Graph Mining Made Easier And Faster](https://dl.acm.org/citation.cfm?id=3190545&dl=ACM&coll=DL)                                                                                 |2017|
|[Graphene: Fine-Grained Io Management For Graph Computing](https://www.usenix.org/conference/fast17/technical-sessions/presentation/liu)                                                                           |2017|
|[Graphflow: An Active Graph Database](https://dl.acm.org/citation.cfm?id=3056445)                                                                                                |2017|
|[GraphH High Performance Big Graph Analytics In Small Clusters](https://arxiv.org/abs/1705.05595)                                                                      |2017|
|[Graphmp An Efficient Semi External Memory Big Graph Processing System On A Single Machine](https://ieeexplore.ieee.org/document/8368374)                                          |2017|
|[GraphR Accelerating Graph Processing Using ReRAM](https://arxiv.org/abs/1708.06248)                                                                                   |2017|
|[Groute: An Asynchronous Multi-GPU Programming Model For Irregular Computations](https://dl.acm.org/citation.cfm?id=3018756)                                                     |2017|
|[Hieroglyph: Locally-Sufficient Graph Processing Via Compute-Sync-Merge](https://dl.acm.org/citation.cfm?id=3078589&dl=ACM&coll=DL)                                                             |2017|
|[High Performance Graph Processing With Locality Oriented Design](https://ieeexplore.ieee.org/document/7815299)                                                                    |2017|
|[IncPregel: An Incremental Graph Parallel Computation Model](https://link.springer.com/article/10.1007%2Fs11704-016-6109-y)                                                                         |2017|
|[Julienne A Framework For Parallel Graph Algorithms Using Work Efficient Bucketing](https://dl.acm.org/citation.cfm?id=3087580)                                                  |2017|
|[Mosaic Processing A Trillion Edge Graph On A Single Machine](https://dl.acm.org/citation.cfm?id=3064191)                                                                        |2017|
|[Parallelizing Sequential Graph Computations](https://dl.acm.org/citation.cfm?id=3035942)                                                                                        |2017|
|[Squeezing Out All The Value Of Loaded Data: An Out-Of-Core Graph Processing System With Reduced Disk IO](https://dl.acm.org/citation.cfm?id=3154703)                            |2017|
|[Tink, A Temporal Graph Analytics Library For Apache Flink](https://pdfs.semanticscholar.org/03d9/3d190296ff290a869248774e6c5d72b55b44.pdf?_ga=2.231950042.432386137.1543765573-222399624.1543765573)                                                                          |2017|
|[Tux2 Distributed Graph Computation For Machine Learning](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/xiao)                                                                           |2017|
|[Wolfpath: Accelerating Iterative Traversing-Based Graph Processing Algorithms On GPU](https://link.springer.com/article/10.1007/s10766-017-0533-y)                                               |2017|
|                                                                                                                                   |    |
|[A Distributed Graph Parallel Computing System With Lightweight Communication Overhead](https://ieeexplore.ieee.org/document/7422016)                                              |2016|
|[An Edge Set Based Large Scale Graph Processing System](https://ieeexplore.ieee.org/document/7840780)                                                                              |2016|
|[Bladyg A Novel Block Centric Framework For The Analysis Of Large Dynamic Graphs](https://dl.acm.org/citation.cfm?doid=2915516.2915525)                                                    |2016|
|[DD-Graph A Highly Cost Effective Distributed Disk Based Graph Processing Framework](https://dl.acm.org/citation.cfm?id=2907294.2907299)                                              |2016|
|[Distributed Graph Processing An Approach Based On Overlay Composition](https://dl.acm.org/citation.cfm?id=2851746&dl=ACM&coll=DL)                                                              |2016|
|[epiCG A Graphunit Based Graph Processing Engine On epiC](https://www.sciencedirect.com/science/article/pii/S2214579615300344?via%3Dihub)                                                                            |2016|
|[Exploring The Hidden Dimension In Graph Processing](https://www.usenix.org/conference/osdi16/technical-sessions/presentation/zhang-mingxing)                                                                                 |2016|
|[FOG: A Fast Out-Of-Core Graph Processing Framework](https://link.springer.com/article/10.1007/s10766-016-0468-8)                                                                                 |2016|
|[G-Store: High-Performance Graph Store For Trillion-Edge Processing](https://ieeexplore.ieee.org/document/7877149)                                                                 |2016|
|[Gemini A Computation Centric Distributed Graph Processing System](https://www.usenix.org/conference/osdi16/technical-sessions/presentation/zhu)                                                                   |2016|
|[Grafalgo - A Library Of Graph Algorithms And Supporting Data Structures (revised)](https://arxiv.org/abs/1601.01597)                                                        |2016|
|[Graphframes An Integrated API For Mixing Graph And Relational Queries](https://dl.acm.org/citation.cfm?id=2960416)                                                              |2016|
|[Graphicionado: A High Performance And Energy Efficient Accelerator For Graph Analytics](https://ieeexplore.ieee.org/document/7783759)                                              |2016|
|[Graphillion Software Library For Very Large Sets Of Labeled Graphs](https://dl.acm.org/citation.cfm?id=2887499)                                                                 |2016|
|[GraphIn: An Online High Performance Incremental Graph Processing Framework ](https://dl.acm.org/citation.cfm?id=2991023)                                                        |2016|
|[Graphine: Programming Graph Parallel Computation Of Large Natural Graphs For Multicore Clusters](https://ieeexplore.ieee.org/document/7152922)                                     |2016|
|[GraphP: Reducing Communication For Pim-Based Graph Processing With Efficient Data Partition](https://ieeexplore.ieee.org/document/8327036)                                        |2016|
|[GraphPad: Optimized Graph Primitives For Parallel And Distributed Platforms](https://ieeexplore.ieee.org/document/7516027)                                                         |2016|
|[GraVF: A Vertex-Centric Distributed Graph Processing Framework On FPGAs](https://ieeexplore.ieee.org/document/7577360)                                                            |2016|
|[GTS A Fast And Scalable Graph Processing Method Based On Streaming Topology To GPUs](https://dl.acm.org/citation.cfm?id=2915204&dl=ACM&coll=DL)                                                |2016|
|[Gunrock: A High Performance Graph Processing Library On The GPU](https://dl.acm.org/citation.cfm?id=2851145)                                                                     |2016|
|[Husky: Towards A More Efficient And Expressive Distributed Computing Framework](https://dl.acm.org/citation.cfm?id=2876477)                                                     |2016|
|[Hygraph: Fast Graph Processing On Hybrid Cpu-Gpu Platforms By Dynamic Load-Balancing](http://materials.dagstuhl.de/files/17/17431/17431.AnaLuciaVarbanescu1.Preprint.pdf)                                               |2016|
|[LCC-Graph: A High Performance Graph Processing Framework With Low Communication Costs](https://ieeexplore.ieee.org/document/7590434)                                               |2016|
|[M-Flash Fast Billion Scale Graph Computation Using A Bimodal Block Processing Model](https://arxiv.org/abs/1506.01406)                                                |2016|
|[Mini-Gunrock: A Lightweight Graph Analytics Framework On The GPU](https://ieeexplore.ieee.org/document/7965101)                                                                    |2016|
|[Mizan-RMA: Accelerating Mizan Graph Processing Framework With MPI RMA](https://ieeexplore.ieee.org/document/7839668)                                                              |2016|
|[Quegel A General Purpose Query Centric Framework For Querying Big Graphs](http://www.vldb.org/pvldb/vol9/p564-yan.pdf)                                                           |2016|
|[SGraph: A Distributed Streaming System For Processing Big Graphs](https://link.springer.com/chapter/10.1007/978-3-319-42553-5_24)                                                                    |2016|
|[SNAP: A General-Purpose Network Analysis and Graph-Mining Library](https://dl.acm.org/citation.cfm?id=2898361)                                                               |2016|
|[SystemML: Declarative Machine Learning on Spark](http://www.vldb.org/pvldb/vol9/p1425-boehm.pdf)                                                                                    |2016|
|                                                                                                                                   |    |
|[Arabesque A System For Distributed Graph Mining](https://dl.acm.org/citation.cfm?id=2815410)                                                                                    |2015|
|[Chaos Scale Out Graph Processing From Secondary Storage](https://dl.acm.org/citation.cfm?id=2815408)                                                                            |2015|
|[Effective Techniques For Message Reduction And Load Balancing In Distributed Graph Computation](https://dl.acm.org/citation.cfm?id=2736277.2741096)                                     |2015|
|[Efficient Graph Computation On Hybrid Cpu And Gpu Systems](https://link.springer.com/article/10.1007/s11227-015-1378-z)                                                                          |2015|
|[Expregel A New Computational Model For Large Scale Graph Processing](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.3482)                                                                |2015|
|[Giraph Unchained: Barrierless Asynchronous Parallel Execution In Pregel-Like Graph Processing Systems](https://dl.acm.org/citation.cfm?id=2777604)                              |2015|
|[Gram Scaling Graph Computation To The Trillions](https://dl.acm.org/citation.cfm?id=2806849)                                                                                    |2015|
|[Graphmat High Performance Graph Analytics Made Productive](https://dl.acm.org/citation.cfm?doid=2809974.2809983)                                                                          |2015|
|[Graphq Graph Query Processing With Abstraction Refinement Scalable And Programmable Analytics Over Very Large Graphs On A Single Pc](https://www.usenix.org/conference/atc15/technical-session/presentation/wang-kai)|2015|
|[Graphreduce Processing Large Scale Graphs On Accelerator Based Systems](https://ieeexplore.ieee.org/document/7832802)                                                             |2015|
|[Graphs Matrices And The Graphblas Seven Good Reasons](https://www.sciencedirect.com/science/article/pii/S1877050915011618)                                                                               |2015|
|[Graphtwist: Fast Iterative Graph Computation With Two-Tier Optimizations](http://www.vldb.org/pvldb/vol8/p1262-Zhou.pdf)                                                           |2015|
|[Graphulo: Linear Algebra Graph Kernels For Nosql Databases](https://arxiv.org/abs/1508.07372)                                                                         |2015|
|[Graphz A Key Value Store Based Scalable Graph Processing System](https://ieeexplore.ieee.org/abstract/document/7307637)                                                                    |2015|
|[Gridgraph Large Scale Graph Processing On A Single Machine Using 2 Level Hierarchical Partitioning](https://www.usenix.org/conference/atc15/technical-session/presentation/zhu)                                 |2015|
|[HAGP A Hub Centric Asynchronous Graph Processing Framework For Scale Free Graph](https://ieeexplore.ieee.org/document/7152558)                                                    |2015|
|[High Performance Graph Analytics On Manycore Processors](https://ieeexplore.ieee.org/document/7161272)                                                                            |2015|
|[MIPS A Graph Mining Library]()                                                                                                        |2015|
|[NScale Neighborhood Centric Analytics On Large Graphs](https://link.springer.com/article/10.1007/s00778-015-0405-2)                                                                              |2015|
|[NUMA-Aware Graph Structured Analytics](https://dl.acm.org/citation.cfm?id=2688507)                                                                                              |2015|
|[NXgraph An Efficient Graph Processing System On A Single Machine](https://ieeexplore.ieee.org/document/7498258)                                                                   |2015|
|[PGX.D A Fast Distributed Graph Processing Engine](https://dl.acm.org/citation.cfm?id=2807620)                                                                                   |2015|
|[Ringo Interactive Graph Analytics On Big Memory Machines](https://dl.acm.org/citation.cfm?id=2735369)                                                                           |2015|
|[ScaleGraph : A High-Performance Library For Billion-Scale Graph Analytics](https://ieeexplore.ieee.org/document/7363744)                                                          |2015|
|[Smaller And Faster Parallel Processing Of Compressed Graphs With Ligra+](https://ieeexplore.ieee.org/document/7149297)                                                             |2015|
|[Sync Or Async Time To Fuse For Distributed Graph Parallel Computation](https://dl.acm.org/citation.cfm?id=2688508)                                                              |2015|
|[The Gremlin Graph Traversal Machine And Language](https://arxiv.org/abs/1508.03843)                                                                                   |2015|
|[Venus Vertex Centric Streamlined Graph Computation On A Single PC](https://ieeexplore.ieee.org/document/7113362)                                                                  |2015|
|                                                                                                                                   |    |
|[An Efficient Graph Data Processing System For Large Scale Social Network Service Applications](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.3393)                                      |2014|
|[Blogel: A Block Centric Framework For Distributed Computation On Real World Graphs](https://dl.acm.org/citation.cfm?doid=2733085.2733103)                                                  |2014|
|[BPP: Large Graph Storage For Efficient Disk-Based Processing](https://arxiv.org/pdf/1401.2327.pdf)                                                                       |2014|
|[Chronos: A Graph Engine For Temporal Graph Analysis](https://dl.acm.org/citation.cfm?id=2592799)                                                                                |2014|
|[Computation And Communication Efficient Graph Processing With Distributed Immutable View](https://dl.acm.org/citation.cfm?id=2600233)                                           |2014|
|[epiC: An Extensible And Scalable System For Processing Big Data](https://link.springer.com/article/10.1007/s00778-015-0393-2)                                                                    |2014|
|[Explore Efficient Data Organization For Large Scale Graph Analytics And Storage](https://pdfs.semanticscholar.org/deda/c1fed5a9575b7e96f11e0914a39b61c6f8db.pdf)                                                    |2014|
|[Flashgraph Processing Billion Node Graphs On An Array Of Commodity SSDs](https://www.usenix.org/conference/fast15/technical-sessions/presentation/zheng)                                                            |2014|
|[GasCL: A Vertex Centric Graph Model For GPUs](https://ieeexplore.ieee.org/document/7040962)                                                                                        |2014|
|[GoFFish A Sub Graph Centric Framework For Large Scale Graph Analytics](https://link.springer.com/chapter/10.1007/978-3-319-09873-9_38)                                                              |2014|
|[Graph Analytics Using The Vertica Relational Database](https://ieeexplore.ieee.org/document/7363873)                                                                              |2014|
|[GraphGen: An FPGA Framework For Vertex-Centric Graph Computation](https://ieeexplore.ieee.org/document/6861577)                                                                   |2014|
|[GraphHP: A Hybrid Platform For Iterative Graph Processing](https://arxiv.org/abs/1706.07221)                                                                           |2014|
|[Large Scale Graph Analytics In Aster 6 Bringing Context To Big Data Discovery](https://dl.acm.org/citation.cfm?id=2733013)                                                      |2014|
|[Managing Large Graphs On Multi-Cores With Graph Awareness](https://www.usenix.org/conference/atc12/technical-sessions/presentation/prabhakaran)                                                                          |2014|
|[MOCgraph: Scalable Distributed Graph Processing Using Message Online Computing](https://dl.acm.org/citation.cfm?id=2735501)                                                     |2014|
|[Networkit: A Tool Suite For Large Scale Complex Network Analysis](https://www.cambridge.org/core/journals/network-science/article/networkit-a-tool-suite-for-largescale-complex-network-analysis/03DB673D73EDC84C0A143864FFA17831)                                                                    |2014|
|[PathGraph: A Path Centric Graph Processing System](https://ieeexplore.ieee.org/document/7384525)                                                                                   |2014|
|[Replication-Based Fault-Tolerance For Large-Scale Graph Processing](https://ieeexplore.ieee.org/document/7927721)                                                                 |2014|
|[Scalable SIMD-Efficient Graph Processing On GPUs](https://ieeexplore.ieee.org/document/7429293)                                                                                   |2014|
|[Seraph: An Efficient, Low-Cost System For Concurrent Graph Processing](https://dl.acm.org/citation.cfm?id=2600222)                                                              |2014|
|                                                                                                                                   |    |
|[A Lightweight Infrastructure For Graph Analytics](https://dl.acm.org/citation.cfm?id=2522739)                                                                                   |2013|
|[BC-BSP: A BSP-Based Parallel Iterative Processing System For Big Data On Cloud Architecture](https://link.springer.com/chapter/10.1007/978-3-642-40270-8_3)                                        |2013|
|[From Think Like A Vertex To Think Like A Graph](https://dl.acm.org/citation.cfm?id=2732238)                                                                                     |2013|
|[Giraphx: Parallel Yet Serializable Large-Scale Graph Processing](https://link.springer.com/chapter/10.1007/978-3-642-40047-6_47)                                                                    |2013|
|[GPS: A Graph Processing System](https://dl.acm.org/citation.cfm?id=2484843)                                                                                                      |2013|
|[GraphX: Graph Processing In A Distributed Dataflow Framework](https://www.usenix.org/node/186217)                                                                        |2013|
|[GRE: A Graph Runtime Engine For Large-Scale Distributed Graph-Parallel Applications](https://arxiv.org/abs/1310.5603)                                                |2013|
|[LFGraph: Simple And Fast Distributed Graph Analytics](https://dl.acm.org/citation.cfm?doid=2524211.2524218)                                                                                |2013|
|[Ligra: A Lightweight Graph Processing Framework For Shared Memory](https://dl.acm.org/citation.cfm?id=2442530)                                                                   |2013|
|[Medusa Simplified Graph Processing On GPUs](https://ieeexplore.ieee.org/document/6497047)                                                                                         |2013|
|[MMap: Fast Billion-Scale Graph Computation On A PC Via Memory Mapping](https://ieeexplore.ieee.org/document/7004226)                                                              |2013|
|[Naiad: A Timely Dataflow System](https://dl.acm.org/citation.cfm?doid=2517349.2522738)                                                                                                     |2013|
|[PAGE: A Partition Aware Engine For Parallel Graph Computation](https://ieeexplore.ieee.org/document/6823116)                                                                      |2013|
|[PowerLyra: Differentiated Graph Computation And Partitioning On Skewed Graphs](https://dl.acm.org/citation.cfm?id=2741970)                                                       |2013|
|[Pregelix Bigger Graph Analytics On A Dataflow Engine](http://www.vldb.org/pvldb/vol8/p161-bu.pdf)                                                                               |2013|
|[Presto: Distributed Machine Learning And Graph Processing With Sparse Matrices](https://dl.acm.org/citation.cfm?id=2465371)                                                     |2013|
|[Scale-Up Graph Processing: A Storage-Centric View](https://dl.acm.org/citation.cfm?id=2484433)                                                                                  |2013|
|[Scalegraph A High Performance Library For Billion Scale Graph Analytics](https://ieeexplore.ieee.org/document/7363744)                                                            |2013|
|[SociaLite: Datalog Extensions For Efficient Social Network Analysis](https://dl.acm.org/citation.cfm?id=2511289)                                                                 |2013|
|[The Graph Story Of The Sap HANA Database](http://cs.emis.de/LNI/Proceedings/Proceedings214/403.pdf)                                                                                           |2013|
|[Towards Gpu-Accelerated Large-Scale Graph Processing In The Cloud](https://ieeexplore.ieee.org/document/6753772)                                                                  |2013|
|[TripleBit: A Fast And Compact System For Large Scale RDF Data](https://dl.acm.org/citation.cfm?doid=2536349.2536352)                                                                     |2013|
|[Turbograph: A Fast Parallel Graph Engine Handling Billion Scale Graphs In A Single PC](https://dl.acm.org/citation.cfm?id=2487581)                                               |2013|
|[X-Stream: Edge-Centric Graph Processing Using Streaming Partitions](https://dl.acm.org/citation.cfm?id=2522740)                                                                 |2013|
|                                                                                                                                   |    |
|[A GPU Implementation Of Generalized Graph Processing Algorithm GIM-V](https://ieeexplore.ieee.org/document/6355866)                                                               |2012|
|[Asynchronous Large-Scale Graph Processing Made Easy](http://cidrdb.org/cidr2013/Papers/CIDR13_Paper58.pdf)                                                                                |2012|
|[Giraph Unchained: Barrierless Asynchronous Parallel Execution In Pregel Like Graph Processing Systems](https://dl.acm.org/citation.cfm?id=2777604)                               |2012|
|[GraphChi: Large Scale Graph Computation On Just A PC](https://www.usenix.org/conference/osdi12/technical-sessions/presentation/kyrola)                                                                                |2012|
|[Green-Marl: A DSL For Easy And Efficient Graph Analysis](https://dl.acm.org/citation.cfm?id=2151013)                                                                             |2012|
|[Kineograph: Taking The Pulse Of A Fast Changing And Connected World](https://dl.acm.org/citation.cfm?doid=2168836.2168846)                                                                 |2012|
|[Maiter: An Asynchronous Graph Processing Framework For Delta-Based Accumulative Iterative Computation](https://www.computer.org/csdl/trans/td/2014/08/06600686.html)                              |2012|
|[Managing Large Graphs On Multi Cores With Graph Awareness](https://www.microsoft.com/en-us/research/wp-content/uploads/2012/06/grace.pdf)                                                                          |2012|
|[Mizan: A System For Dynamic Load Balancing In Large Scale Graph Processing](https://dl.acm.org/citation.cfm?id=2465369)                                                          |2012|
|[On Graphs, GPUS, And Blind Dating: A Workload To Processor Matchmaking Quest](https://ieeexplore.ieee.org/document/6569867)                                                        |2012|
|[Powergraph: Distributed Graph Parallel Computation On Natural Graphs](https://www.usenix.org/node/170825)                                                                |2012|
|[Resilient Distributed Datasets: A Fault Tolerant Abstraction For In Memory Cluster Computing](https://www.usenix.org/conference/nsdi12/technical-sessions/presentation/zaharia)                                        |2012|
|[STINGER: High Performance Data Structure For Streaming Graphs](https://ieeexplore.ieee.org/abstract/document/6408680)                                                                       |2012|
|[The STAPL Parallel Graph Library](https://link.springer.com/chapter/10.1007/978-3-642-37658-0_4)                                                                                                   |2012|
|[Trinity: A Distributed Graph Engine On A Memory Cloud](https://dl.acm.org/citation.cfm?id=2467799)                                                                              |2012|
|                                                                                                                                   |    |
|[A Flexible Open Source Toolbox For Scalable Complex Graph Analysis](https://www.cs.ucsb.edu/research/tech-reports/2011-10)                                                                 |2011|
|[CIEL: A Universal Execution Engine For Distributed Data-Flow Computing](https://www.usenix.org/conference/nsdi11/ciel-universal-execution-engine-distributed-data-flow-computing)                                                             |2011|
|[DisNet: A Framework For Distributed Graph Computation](https://www3.nd.edu/~nchawla/papers/ASONAM11a.pdf)                                                                              |2011|
|[GBASE: An Efficient Analysis Platform For Large Graphs](https://link.springer.com/article/10.1007/s00778-012-0283-9)                                                                              |2011|
|[HipG: Parallel Processing Of Large-Scale Graphs](https://dl.acm.org/citation.cfm?id=2007185)                                                                                    |2011|
|[Hyracks: A Flexible And Extensible Foundation For Data Intensive Computing](https://ieeexplore.ieee.org/document/5767921)                                                          |2011|
|[Ihadoop: Asynchronous Iterations For Mapreduce](https://ieeexplore.ieee.org/document/6133130)                                                                                     |2011|
|[iMapReduce: A Distributed Computing Framework For Iterative Computation](https://link.springer.com/article/10.1007/s10723-012-9204-9)                                                            |2011|
|[MapReduce in MPI for Large-scale graph algorithms](https://dl.acm.org/citation.cfm?id=2286704)                                                                                  |2011|
|[MapReduce: simplified data processing on large clusters](https://dl.acm.org/citation.cfm?id=1327492)                                                                               |2011|
|[Parallelizing Machine Learning– Functionally: A Framework And Abstractions For Parallel Graph Processing](https://infoscience.epfl.ch/record/165111/files/scalawksp11.pdfs)                           |2011|
|[Piccolo: Building Fast, Distributed Programs With Partitioned Tables](https://www.usenix.org/conference/osdi10/piccolo-building-fast-distributed-programs-partitioned-tables)                                                               |2011|
|[Priter: A Distributed Framework For Prioritized Iterative Computations](https://ieeexplore.ieee.org/document/6302132/)                                                             |2011|
|[The Combinatorial Blas Design Implementation And Applications](https://journals.sagepub.com/doi/10.1177/1094342011403516)                                                                      |2011|
|                                                                                                                                   |    |
|[GraphLab: A New Framework For Parallel Machine Learning](https://arxiv.org/abs/1006.4990)                                                                             |2010|
|[Haloop: Efficient Iterative Data Processing On Large Clusters](https://homes.cs.washington.edu/~mernst/pubs/haloop-vldb2012-abstract.html)                                                                      |2010|
|[Hama: An Efficient Matrix Computation With The Mapreduce Framework](https://ieeexplore.ieee.org/document/5708522)                                                                  |2010|
|[HypergraphDB: A Generalized Graph Database](https://link.springer.com/chapter/10.1007/978-3-642-16720-1_3)                                                                                          |2010|
|[Infinitegraph: The Distributed Graph Database](https://www.objectivity.com/products/infinitegraph/)                                                                                      |2010|
|[Nephele/PACTs: A Programming Model And Execution Framework For Web Scale Analytical Processing](https://dl.acm.org/citation.cfm?id=1807148)                                       |2010|
|[On The Efficiency And Programmability Of Large Graph Processing In The Cloud](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Surfer_tr.pdf)                                                       |2010|
|[Pregel: A System For Large Scale Graph Processing](https://dl.acm.org/citation.cfm?id=1807184)                                                                                   |2010|
|[Signal-Collect: Graph Algorithms For The (Semantic) Web](https://link.springer.com/chapter/10.1007/978-3-642-17746-0_48)                                                                            |2010|
|[Twister: A Runtime For Iterative Mapreduce](https://dl.acm.org/citation.cfm?id=1851593)                                                                                         |2010|
|                                                                                                                                   |    |
|[PEGASUS: Mining Peta Scale Graphs](https://link.springer.com/article/10.1007/s10115-010-0305-0)                                                                                                   |2009|
|[The Stratosphere Platform For Big Data Analytics](https://dl.acm.org/citation.cfm?id=2691544)                                                                                   |2009|
|                                                                                                                                   |    |
|[Dryad Distributed Data Parallel Programs From Sequential Building Blocks](https://dl.acm.org/citation.cfm?id=1273005)                                                           |2007|
|[RDF Support In The Virtuoso DBMS](https://link.springer.com/chapter/10.1007/978-3-642-02184-8_2)                                                                                                   |2007|
|[Software And Algorithms For Graph Queries On Multithreaded Architectures](https://ieeexplore.ieee.org/document/4228413)                                                           |2007|
|                                                                                                                                   |    |
|[The Parallel BGL: A Generic Library For Distributed Graph Computations](https://pdfs.semanticscholar.org/d7f4/49c199ce86d3b8039899caabb31b54ced7f2.pdf)                                                             |2005|
|                                                                                                                                   |    |
|[The Boost Graph Library](https://www.boost.org/doc/libs/1_66_0/libs/graph/doc/)                                                                                                            |2002|
