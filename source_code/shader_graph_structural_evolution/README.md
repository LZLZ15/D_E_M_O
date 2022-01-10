# Graph Analysis on the Shader Codes of Online Video Games 
<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Graph creation](#Graph-creation)
* [Scripts Explanation](#Scripts-Explanation)
  * [Graph Analysis](#Graph-Analysis)
  * [Single Game Analysis](#Single-game)
  * [Intergame Analysis](#Inter-game)
* [Useful linkes](#Useful-linkes)
* [Reference](#Reference)



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- Graph creation -->
## Graph  
The sample graphs of disassembly shaders can be found in  [Link to the folder](sample_graph/)


<!-- Scripts Explanation -->
## Scripts Explanation

All the scripts are written in python 3.8. To run the script, please lunch a python tools like Anaconda or directly run "python xx.py" 


### Single Game Analysis
[Link to the folder](Single_Game/)

1. Evolution of Shader Code Graphs

   [Figue3a plot](Single_Game/figure3a_barplot_node_FS.py)
	
	An example to analyze plot figure 3a.
	

2. Sudden Change Detection in Frames

   [Figure 8 plot](Graph_Analysis/WL_kernel_2consecutiveFrame_FS.py)
   
   An example for figure 8
   
3. A Frame's Scene Prediction

   [Prepare dataset (Merge all graphs)](Single_Game/merge_allgraph_into1_perframe_GTA5_cs_hs_ls.py)

   An example to merge all graphs in the same frame as one disjoint graph. 
   
   [GCN with interpretability library](https://github.com/tsKenneth/interpretable-graph-classification)

   Make use of the existing libraries for GCN and the result explainability.


    

<!-- Useful linkes -->
## Useful linkes
1. [gSpan](https://github.com/betterenvi/gSpan)
2. [RenderDoc](https://renderdoc.org/)
3. [AMD GPU Toolkit](https://gpuopen.com/introducing-radeon-developer-tool-suite/})
4. [NVIDIA Shader Disassembly library](https://developer.nvidia.com/shader-disasm)
5. [Interpretability-GCN](https://github.com/tsKenneth/interpretable-graph-classification)



<!-- Reference -->
## Reference

