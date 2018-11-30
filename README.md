# Graph Processing Platforms

The efficient processing of large graphs is challenging. Given the current availability of data, real network traces are growing in variety and volume turning imperative the design of solutions and systems based on parallel and distributed technologies. In this sense, high performance methodologies could potentially leverage graph processing community similarly to what they accomplished in scientific computing. However, despite of high performance computing success in computing-demanding scientific applications, graph analytics suffers from distinct and inherent difficulties given its data-driven nature, e.g, high data-access computing ratio and poor locality of memory access. Furthermore, as one's analysis requires a more complex infrastructure, the development effort for crafting new solutions from scratch turns imperative the adoption of software platforms --- DBMS, frameworks and libraries --- to alleviate the development burden. In this scenario, many platforms data oriented and graph specific have been proposed. We estimate that there are currently more than 180 platforms that can be employed in graph analytic tasks.

|                                                                                                                                   |    |
|-----------------------------------------------------------------------------------------------------------------------------------|----|
|Fbsgraph: Accelerating Asynchronous Graph Processing Via Forward And Backward Sweeping                                             |2018|
|Graph: Traffic-Aware Graph Processing                                                                                              |2018|
|Graphd: Distributed Vertex-Centric Graph Processing Beyond The Memory Limit                                                        |2018|
|Hyve: Hybrid Vertex-Edge Memory Hierarchy For Energy-Efficient Graph Processing                                                    |2018|
|L-Powergraph: A Lightweight Distributed Graph-Parallel Communication Mechanism                                                     |2018|
|La3: A Scalable Link- And Locality-Aware Linear Algebra-Based Graph Analytics System                                               |2018|
|Lazygraph: Lazy Data Coherency For Replicas In Distributed Graph-Parallel Computation                                              |2018|
|Shmemgraph: Efficient And Balanced Graph Processing Using One-Sided Communication                                                  |2018|
|Turbograph++: A Scalable And Fast Graph Analytics System                                                                           |2018|
|Wonderland: A Novel Abstraction-Based Out-Of-Core Graph Processing System                                                          |2018|
|A Distributed Multi-Gpu System For Fast Graph Processing                                                                           |2017|
|Blockgraphchi: Enabling Block Update In Out-Of-Core Graph Processing                                                               |2017|
|Cypher-Based Graph Pattern Matching In Gradoop                                                                                     |2017|
|Foregraph Exploring Large Scale Graph Processing On Multi Fpga Architecture                                                        |2017|
|Frog: Asynchronous Graph Processing On Gpu With Hybrid Coloring Model                                                              |2017|
|G-Thinker: Big Graph Mining Made Easier And Faster                                                                                 |2017|
|Graphene: Fine-Grained Io Management For Graph Computing                                                                           |2017|
|Graphflow: An Active Graph Database                                                                                                |2017|
|Graphh High Performance Big Graph Analytics In Small Clusters                                                                      |2017|
|Graphmp An Efficient Semi External Memory Big Graph Processing System On A Single Machine                                          |2017|
|Graphr Accelerating Graph Processing Using Reram                                                                                   |2017|
|Groute: An Asynchronous Multi-Gpu Programming Model For Irregular Computations                                                     |2017|
|Hieroglyph: Locally-Sufficient Graph Processing Via Compute-Sync-Merge                                                             |2017|
|High Performance Graph Processing With Locality Oriented Design                                                                    |2017|
|Incpregel: An Incremental Graph Parallel Computation Model                                                                         |2017|
|Julienne A Framework For Parallel Graph Algorithms Using Work Efficient Bucketing                                                  |2017|
|Mosaic Processing A Trillion Edge Graph On A Single Machine                                                                        |2017|
|Parallelizing Sequential Graph Computations                                                                                        |2017|
|Squeezing Out All The Value Of Loaded Data: An Out-Of-Core Graph Processing System With Reduced Disk Io                            |2017|
|Tink, A Temporal Graph Analytics Library For Apache Flink                                                                          |2017|
|Tux 2 Distributed Graph Computation For Machine Learning                                                                           |2017|
|Wolfpath: Accelerating Iterative Traversing-Based Graph Processing Algorithms On Gpu                                               |2017|
|A Distributed Graph Parallel Computing System With Lightweight Communication Overhead                                              |2016|
|An Edge Set Based Large Scale Graph Processing System                                                                              |2016|
|Bladyg A Novel Block Centric Framework For The Analysis Of Large Dynamic Graphs                                                    |2016|
|Dd Graph A Highly Cost Effective Distributed Disk Based Graph Processing Framework                                                 |2016|
|Distributed Graph Processing An Approach Based On Overlay Composition                                                              |2016|
|Epicg A Graphunit Based Graph Processing Engine On Epic                                                                            |2016|
|Exploring The Hidden Dimension In Graph Processing                                                                                 |2016|
|Fog: A Fast Out-Of-Core Graph Processing Framework                                                                                 |2016|
|G-Store: High-Performance Graph Store For Trillion-Edge Processing                                                                 |2016|
|Gemini A Computation Centric Distributed Graph Processing System                                                                   |2016|
|Grafalgoa Library Of Graph Algorithms And Supporting Data Structuresrevised                                                        |2016|
|Graphframes An Integrated Api For Mixing Graph And Relational Queries                                                              |2016|
|Graphicionado A High Performance And Energy Efficient Accelerator For Graph Analytics                                              |2016|
|Graphillion Software Library For Very Large Sets Of Labeled Graphs                                                                 |2016|
|Graphin: An Online High Performance Incremental Graph Processing Framework                                                         |2016|
|Graphine Programming Graph Parallel Computation Of Large Natural Graphs For Multicore Clusters                                     |2016|
|Graphp: Reducing Communication For Pim-Based Graph Processing With Efficient Data Partition                                        |2016|
|Graphpad Optimized Graph Primitives For Parallel And Distributed Platforms                                                         |2016|
|Gravf: A Vertex-Centric Distributed Graph Processing Framework On Fpgas                                                            |2016|
|Gts A Fast And Scalable Graph Processing Method Based On Streaming Topology To Gpus                                                |2016|
|Gunrock A High Performance Graph Processing Library On The Gpu                                                                     |2016|
|Husky: Towards A More Efficient And Expressive Distributed Computing Framework                                                     |2016|
|Hygraph: Fast Graph Processing On Hybrid Cpu-Gpu Platforms By Dynamic Load-Balancing                                               |2016|
|Lcc Graph A High Performance Graph Processing Framework With Low Communication Costs                                               |2016|
|M-Flash Fast Billion Scale Graph Computation Using A Bimodal Block Processing Model                                                |2016|
|Mini Gunrock A Lightweight Graph Analytics Framework On The Gpu                                                                    |2016|
|Mizan-Rma: Accelerating Mizan Graph Processing Framework With Mpi Rma                                                              |2016|
|Quegel A General Purpose Query Centric Framework For Querying Big Graphs                                                           |2016|
|Sgraph A Distributed Streaming System For Processing Big Graphs                                                                    |2016|
|Snap A General Purpose Network Analysis And Graph Mining Library                                                                   |2016|
|Systemml: Declarative Machine Learning On Spark                                                                                    |2016|
|Arabesque A System For Distributed Graph Mining                                                                                    |2015|
|Chaos Scale Out Graph Processing From Secondary Storage                                                                            |2015|
|Effective Techniques For Message Reduction And Load Balancing In Distributed Graph Computation                                     |2015|
|Efficient Graph Computation On Hybrid Cpu And Gpu Systems                                                                          |2015|
|Expregel A New Computational Model For Large Scale Graph Processing                                                                |2015|
|Giraph Unchained: Barrierless Asynchronous Parallel Execution In Pregel-Like Graph Processing Systems                              |2015|
|Gram Scaling Graph Computation To The Trillions                                                                                    |2015|
|Graphmat High Performance Graph Analytics Made Productive                                                                          |2015|
|Graphq Graph Query Processing With Abstraction Refinement Scalable And Programmable Analytics Over Very Large Graphs On A Single Pc|2015|
|Graphreduce Processing Large Scale Graphs On Accelerator Based Systems                                                             |2015|
|Graphs Matrices And The Graphblas Seven Good Reasons                                                                               |2015|
|Graphtwist: Fast Iterative Graph Computation With Two-Tier Optimizations                                                           |2015|
|Graphulo: Linear Algebra Graph Kernels For Nosql Databases                                                                         |2015|
|Graphz A Key Value Store Based Scalable Graph Processing System                                                                    |2015|
|Gridgraph Large Scale Graph Processing On A Single Machine Using 2 Level Hierarchical Partitioning                                 |2015|
|Hagp A Hub Centric Asynchronous Graph Processing Framework For Scale Free Graph                                                    |2015|
|High Performance Graph Analytics On Manycore Processors                                                                            |2015|
|Mips A Graph Mining Library                                                                                                        |2015|
|Nscale Neighborhood Centric Analytics On Large Graphs                                                                              |2015|
|Numa Aware Graph Structured Analytics                                                                                              |2015|
|Nxgraph An Efficient Graph Processing System On A Single Machine                                                                   |2015|
|Pgx D A Fast Distributed Graph Processing Engine                                                                                   |2015|
|Ringo Interactive Graph Analytics On Big Memory Machines                                                                           |2015|
|Scalegraph : A High-Performance Library For Billion-Scale Graph Analytics                                                          |2015|
|Smaller And Faster Parallel Processing Of Compressed Graphs With Ligra                                                             |2015|
|Sync Or Async Time To Fuse For Distributed Graph Parallel Computation                                                              |2015|
|The Gremlin Graph Traversal Machine And Language                                                                                   |2015|
|Venus Vertex Centric Streamlined Graph Computation On A Single Pc                                                                  |2015|
|An Efficient Graph Data Processing System For Large Scale Social Network Service Applications                                      |2014|
|Blogel A Block Centric Framework For Distributed Computation On Real World Graphs                                                  |2014|
|Bpp: Large Graph Storage For Efficient Disk-Based Processing                                                                       |2014|
|Chronos: A Graph Engine For Temporal Graph Analysis                                                                                |2014|
|Computation And Communication Efficient Graph Processing With Distributed Immutable View                                           |2014|
|Epic: An Extensible And Scalable System For Processing Big Data                                                                    |2014|
|Explore Efficient Data Organization For Large Scale Graph Analytics And Storage                                                    |2014|
|Flashgraph Processing Billion Node Graphs On An Array Of Commodity Ssds                                                            |2014|
|Gascl A Vertex Centric Graph Model For Gpus                                                                                        |2014|
|Goffish A Sub Graph Centric Framework For Large Scale Graph Analytics                                                              |2014|
|Graph Analytics Using The Vertica Relational Database                                                                              |2014|
|Graphgen: An Fpga Framework For Vertex-Centric Graph Computation                                                                   |2014|
|Graphhp A Hybrid Platform For Iterative Graph Processing                                                                           |2014|
|Large Scale Graph Analytics In Aster 6 Bringing Context To Big Data Discovery                                                      |2014|
|Managing Large Graphs On Multi-Cores With Graph Awareness                                                                          |2014|
|Mocgraph: Scalable Distributed Graph Processing Using Message Online Computing                                                     |2014|
|Networkit A Tool Suite For Large Scale Complex Network Analysis                                                                    |2014|
|Pathgraph A Path Centric Graph Processing System                                                                                   |2014|
|Replication-Based Fault-Tolerance For Large-Scale Graph Processing                                                                 |2014|
|Scalable Simd-Efficient Graph Processing On Gpus                                                                                   |2014|
|Seraph: An Efficient, Low-Cost System For Concurrent Graph Processing                                                              |2014|
|A Lightweight Infrastructure For Graph Analytics                                                                                   |2013|
|Bc-Bsp: A Bsp-Based Parallel Iterative Processing System For Big Data On Cloud Architecture                                        |2013|
|From Think Like A Vertex To Think Like A Graph                                                                                     |2013|
|Giraphx: Parallel Yet Serializable Large-Scale Graph Processing                                                                    |2013|
|Gps A Graph Processing System                                                                                                      |2013|
|Graphx Graph Processing In A Distributed Dataflow Framework                                                                        |2013|
|Gre: A Graph Runtime Engine For Large-Scale Distributed Graph-Parallel Applications                                                |2013|
|Lfgraph Simple And Fast Distributed Graph Analytics                                                                                |2013|
|Ligra A Lightweight Graph Processing Framework For Shared Memory                                                                   |2013|
|Medusa Simplified Graph Processing On Gpus                                                                                         |2013|
|Mmap: Fast Billion-Scale Graph Computation On A Pc Via Memory Mapping                                                              |2013|
|Naiad A Timely Dataflow System                                                                                                     |2013|
|Page: A Partition Aware Engine For Parallel Graph Computation                                                                      |2013|
|Powerlyra Differentiated Graph Computation And Partitioning On Skewed Graphs                                                       |2013|
|Pregelix Bigger Graph Analytics On A Dataflow Engine                                                                               |2013|
|Presto: Distributed Machine Learning And Graph Processing With Sparse Matrices                                                     |2013|
|Scale-Up Graph Processing: A Storage-Centric View                                                                                  |2013|
|Scalegraph A High Performance Library For Billion Scale Graph Analytics                                                            |2013|
|Socialite Datalog Extensions For Efficient Social Network Analysis                                                                 |2013|
|The Graph Story Of The Sap Hana Database                                                                                           |2013|
|Towards Gpu-Accelerated Large-Scale Graph Processing In The Cloud                                                                  |2013|
|Triplebit: A Fast And Compact System For Large Scale Rdf Data                                                                      |2013|
|Turbograph A Fast Parallel Graph Engine Handling Billion Scale Graphs In A Single Pc                                               |2013|
|X-Stream: Edge-Centric Graph Processing Using Streaming Partitions                                                                 |2013|
|A Gpu Implementation Of Generalized Graph Processing Algorithm Gim-V                                                               |2012|
|Asynchronous Large-Scale Graph Processing Made Easy                                                                                |2012|
|Giraph Unchained Barrierless Asynchronous Parallel Execution In Pregel Like Graph Processing Systems                               |2012|
|Graphchi Large Scale Graph Computation On Just A Pc                                                                                |2012|
|Green Marl A Dsl For Easy And Efficient Graph Analysis                                                                             |2012|
|Kineograph Taking The Pulse Of A Fast Changing And Connected World                                                                 |2012|
|Maiter: An Asynchronous Graph Processing Framework For Delta-Based Accumulative Iterative Computation                              |2012|
|Managing Large Graphs On Multi Cores With Graph Awareness                                                                          |2012|
|Mizan A System For Dynamic Load Balancing In Large Scale Graph Processing                                                          |2012|
|On Graphs, Gpus, And Blind Dating A Workload To Processor Matchmaking Quest                                                        |2012|
|Powergraph Distributed Graph Parallel Computation On Natural Graphs                                                                |2012|
|Resilient Distributed Datasets A Fault Tolerant Abstraction For In Memory Cluster Computing                                        |2012|
|Stinger High Performance Data Structure For Streaming Graphs                                                                       |2012|
|The Stapl Parallel Graph Library                                                                                                   |2012|
|Trinity: A Distributed Graph Engine On A Memory Cloud                                                                              |2012|
|A Flexible Open Source Toolbox For Scalable Complex Graph Analysis                                                                 |2011|
|Ciel: A Universal Execution Engine For Distributed Data-Flow Computing                                                             |2011|
|Disnet: A Framework For Distributed Graph Computation                                                                              |2011|
|Gbase An Efficient Analysis Platform For Large Graphs                                                                              |2011|
|Hipg: Parallel Processing Of Large-Scale Graphs                                                                                    |2011|
|Hyracks A Flexible And Extensible Foundation For Data Intensive Computing                                                          |2011|
|Ihadoop: Asynchronous Iterations For Mapreduce                                                                                     |2011|
|Imapreduce: A Distributed Computing Framework For Iterative Computation                                                            |2011|
|Mapreduce In Mpi For Large-Scale Graph Algorithms                                                                                  |2011|
|Mapreduce Simplied Data Processing On Large Clusters                                                                               |2011|
|Parallelizing Machine Learning– Functionally: A Framework And Abstractions For Parallel Graph Processing                           |2011|
|Piccolo: Building Fast, Distributed Programs With Partitioned Tables                                                               |2011|
|Priter: A Distributed Framework For Prioritized Iterative Computations                                                             |2011|
|The Combinatorial Blas Design Implementation And Applications                                                                      |2011|
|Graphlab A New Framework For Parallel Machine Learning                                                                             |2010|
|Haloop: Efficient Iterative Data Processing On Large Clusters                                                                      |2010|
|Hama An Efficient Matrix Computation With The Mapreduce Framework                                                                  |2010|
|Hypergraphdb A Generalized Graph Database                                                                                          |2010|
|Infinitegraph: The Distributed Graph Database                                                                                      |2010|
|Nephelepacts A Programming Model And Execution Framework For Web Scale Analytical Processing                                       |2010|
|On The Efficiency And Programmability Of Large Graph Processing In The Cloud                                                       |2010|
|Pregel A System For Large Scale Graph Processing                                                                                   |2010|
|Signal-Collect: Graph Algorithms For The (Semantic) Web                                                                            |2010|
|Twister: A Runtime For Iterative Mapreduce                                                                                         |2010|
|Pegasus Mining Peta Scale Graphs                                                                                                   |2009|
|The Stratosphere Platform For Big Data Analytics                                                                                   |2009|
|Dryad Distributed Data Parallel Programs From Sequential Building Blocks                                                           |2007|
|Rdf Support In The Virtuoso Dbms                                                                                                   |2007|
|Software And Algorithms For Graph Queries On Multithreaded Architectures                                                           |2007|
|The Parallel Bgl: A Generic Library For Distributed Graph Computations                                                             |2005|
|The Boost Graph Library                                                                                                            |2002|
