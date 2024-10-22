# informativeness-zTree
This repository includes zTree treatment files (.ztt files) to run the lab experiments discussed in "Competition and Price Informativeness: An Experiment" by Daniel Kwiatkowski. These files are compatible with zTree 5.1.1.

The files are: 
-client_initialization.ztt
-1seller_current.ztt
-2seller_current.ztt
-1seller_pricegrid_current.ztt
-2seller_pricegrid_current.ztt
-payoff_display.ztt

client_initialization.ztt should be run first to define variables for the clients table which keeps track of total payoffs across all treatments run in the experiment. Then one or more of the baseline treatments (1seller_current.ztt, 2seller_current.ztt) and the robustness treatments (1seller_pricegrid_current.ztt, 2seller_pricegrid_current.ztt). payoff_display.ztt is run last to display the payoffs from each treatment and their sum.

Credit for zTree software: Fischbacher, Urs. "z-Tree: Zurich toolbox for ready-made economic experiments." Experimental economics 10, no. 2 (2007): 171-178.
