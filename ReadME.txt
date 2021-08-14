start environment:
	source activate TensorFlow
run the below command line:
	python multi-bin-histone-predict-R-loop.py example_bin.bed  example_bin_result_1.txt > example_bin_result_2.txt
additionally, it generates five png files:
	example_bin_1.png    correlation matrix plot for the bin
	example_bin_2.png    scaled algorithm comparison based on mean squared error
	example_bin_3.png    scaled algorithm comparison based on root mean squared error
	example_bin_4.png    gridSearchCV implement for extra trees regressor models
	example_bin_5.png    output the relative importance of epigenetics marks and predictive R squared