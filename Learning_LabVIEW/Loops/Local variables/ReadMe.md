# Loops

## Local Variable

**Local Variable**: Read or write to one of the controls or indicators.

### Mechanical Actions of Boolean Controls 

Switch - hold value until pressed again

Latch - revert to original value after being read

	Default action for buttons is "latch when released"
	
	Not compatiable with local variables

	
**Note**

1. right-click  on the stop 
2. Go to *Mechanical Action* 
3. Select the option *Switch When Released*


### Types of LabVIEW Variables

* Local variables - pass data within the same VI, on the same computer
* Global variables - pass data between separate VIs, on the same computer
* Network - published variables - pass data between separate VIs on separate computers (on the same network)

### Use Local Variable Sparingly 

* Avoid using local variables simply to reduce the number of wires
* Use local variables when you intentionally need to break data flow