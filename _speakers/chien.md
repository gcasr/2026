---
name: Andrew Chien
affiliation: University of Chicago
bio: |
    Andrew is an ACM Fellow (2004), IEEE Fellow (2006), AAAS Fellow (2007), and an NSF Young Investigator (1994). He has received numerous awards and recognitions for his research. He has served on the Advisory Committee for the NSF Computing, Information, Science and Engineering (CISE) Directorate, the NSF Office of Advanced Cyberinfrastructure (OAC), and on DARPA's Information Science and Technology (ISAT) study group. He served as Editor-in-Chief for Communications of the ACM (CACM) from 2017-2022, and served as Intel Vice President of Research from 2005-2010, and also on Advisory Boards of numerous Universities (Stanford, University of California - Berkeley, University of Washington, Ecole Polytechnique Federale Lausanne, University of Virginia), Government Agencies (National Science Foundation, Department of Energy), the Computing Research Association (CRA), and numerous companies (Intel, Samsung, Huawei, Lancium).
description: "UpDown: Breaking through the ceiling on Graph Computing Performance"
abstract: |
    Graph computations are challenging for programming and performance due to low data-reuse and irregular data, achieving poor performance on CPU’s and GPU’s.   The UpDown System radically improves both programmability and performance.  UpDown architecture enables fine-grained parallelism: 1-cycle thread creation and management, 1-cycle messages.  And, split-transaction DRAM access that unlocks the power of HBM’s massive memory bandwidth, under software control.  We will describe how UpDown’s KVMSR+UDWeave framework and global address space enables high-level programming of fine-grained parallelism.

    <p>UpDown performance on skewed-graph computations is 100x vs multicore CPU’s (single-node), and scales to 1,000 and 10,000-fold speedup on BFS, Pagerank, Triangle Count, K-truss and more.  Straightup GPU comparisons show 10-60x speedup.  Comparison to supercomputers show 10-1000x ISO-power performance advantages.</p>

    <p>The UpDown system was created under IARPA’s AGILE program, and is being commercialized in a Chicago-based startup.  This startup is doing leading edge hardware design, including HBM and co-packaged optics with the goal of revolutionizing intelligence/graph analytics, network cybersecurity, financial fraud, and graphRAG + future AI/ML.</p>
img: chien.jpeg
affil_img: uchicago.png
web: http://people.cs.uchicago.edu/~aachien/lssg/people/andrew-chien/
keynote: false
---
