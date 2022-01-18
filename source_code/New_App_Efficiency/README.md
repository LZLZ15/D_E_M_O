# ShaderNet New App Efficiency
<!-- TABLE OF CONTENTS -->

### Intergame Analysis
[Link to the folder](Inter_Game/)

1. Frequent subgraph result analysis 

    Frequent subgraph mining utilized the library of gSpan in the link listed in useful link. 

    An example to convert gSpan output text to edgelist and nodelist: 
    
    Scripts:[convert gSpan result to graph format](New_App_Tuning/fsm_file_to_edgelist_hash.py)

    An example to select longest distinct subgraphs from gSpan result: 
    
    Scripts: [select longest patterns from gSpan result ](New_App_Tuning/select_distinct_subgraph_labelgame.py)


2. shader efficiency prediction

    There are 2 steps in efficiency prediction

    Step1: Dataset preparation

	[Prepare train dataset](prepare_dataset_predict_efficiency_select_distinct_hw_used_in_shader.py)
	
    Step2: Classification  
    
	[random_forest](randomForest.py)

    

<!-- Useful linkes -->
## Useful linkes
1. [gSpan](https://github.com/betterenvi/gSpan)

<!-- Reference -->
## Reference

