- This technique is often used when the evaluation metric is [[F-score]]
	- You need to do thresholding to determine if an example is in the positive or negative class
- This is hard when:
	- 1) The train and test distributions are different
	- 2) You introduce new models into your blend
		- cause each model introduces new biases & variances
	- Solution: use [[percentile thresholding]]