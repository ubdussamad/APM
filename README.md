# //////////////////////////// Advanced Pointing Mechanisms

The goal is to trace subtle movements of calibrated retina to imppliment a pointing device.


Initially it'll be implimented in python and if it works or shows any promise, it'll be ported to C for performance gains. 

Perfomance is a big issue as the proposed device will be using web cam and thus this project **dosen't has a very hard ground to stand on.**

Realized issues with the idea up-til now:
	
	* Web-cam resolution.
	* Frame-rate
	* Low light performance
	* Is this thing even possible?
	* The whole delay created due to this.
	* Eye Blinks
	* Click Inputs
