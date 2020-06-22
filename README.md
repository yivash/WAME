# WAME optimizer for occupancy detection problem (Keras)
<p><b>WAME optimization for Neural Net</b></p> 
<p>Weight-wise Adaptive learning rates with Moving average Estimator (WAME) is optimization technique that explores sign and magnitude of recent gradients to speed up convergence. This technique for controlled training keeps track of moving average, so the algorithm takes in acount smoothed values which allows to be not sensitive to extremes [1]. WAME was implemented in Keras using basic Optimizer class.</p>
<p><b>Occupancy Detection problem</b></p> 
<p>Various optimization techniques like dropout and finding optimal level of neural network complexity used in order to obtain best model for occupancy detection problem (dataset available at [2]). Additionally, feature selection procedure was applied to find most informative features. </p>
<p>Two test datasets were used for the evaluation. Finally, network performed consistently with average accuracy 98.32%,
especially on indicating false negatives with the average recall value of 98.71% which is preferred metric for energy saving application.</b>
<p>[1]. <a href="https://www.elen.ucl.ac.be/Proceedings/esann/esannpdf/es2017-50.pdf"><b>“Training Convolutional Networks with Weight–wise Adaptive Learning Rates”</b></a>(Alan Mosca and George D. Magoulas)</b>
<p>[2]. <a href="http://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+"><b>"Occupancy Detection Datasets"</b></a> (datasets available at UCI repository)</b>

