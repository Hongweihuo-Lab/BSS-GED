# BSS_GED
An Efficient Algorithm for Graph Edit Distance Computation

## What is it?
BSS_GED is a vertex-mapping based method for graph edit distance (GED) computation. It employs the beam-stack
search paradigm, combined with two specially designed heuristics to improve the GED computation, achieving a trade-off between memory utilization and expensive backtracking calls. Also, a novel strategy is proposed to identify invalid and redundant mappings, leading to a reduced search space. 

## How to use it?   
### Step I. Install
   1. download (or clone) the source code from https://github.com/Hongweihuo-Lab/BSS-GED/
   2. Compile the source code. 
### Step II. run BSS_GED
   1. run the shell command: "./BSSGED database n query m bound w", where    
       (1) database is the graph database.       
       (2) n is the number of graphs in the database.        
       (3) query is the set of query graphs. 
       (4) m is the number of graphs in the query.     
       (5) bound is the GED threshold. Specifically, bound = -1 means that we perform the exact 
           GED computation; and otherwise, we perform the threshold-based graph similarity search.        
       (6) w is the beam width.        
       
## Paper
X. Chen, H. Huo, J. Huan, and J. S. Vitter. An Efficient Algorithm for Graph Edit Distance Computation. Knowledge-Based Systems, 163: 762–775, 2019.
 
### Feedback
Please report bugs to X. Chen <jackcxy@126.com> if any. Your feedback and test results are welcome.
