# X-Team 58 Style Guide

Style guides improve the uniformity and readibility of the code, reducing errors and streamlining collaboration.

## Naming conventions

Capitalized for the first letter of each word starting from the second. It may change, depending on specific scenarios, 
such as the first letter of the name for interfaces and classes should also be capitalized.

### Examples
* interfaces
	Eg. BinarySearchTreeADT, PriorityQueueADT
* classes
	Eg. NodeTree, Node
* exception types
	Eg. DuplicateKeyExceptions, RuntimeException    
* fields
	Eg. data, ptr
* methods
	Eg. deleteFirstItem, insertIntegerOnly
* parameters
	Eg. sizeOfArray, listOfParents
* local variables
	Eg. numOfInput, counter
* instance constants
	Eg. MAX_NUM
* class constants
	Eg. PIE_VALUE, MIN_INTEGER

## Commenting style for public and private members of a class or interface:

* //... : highlight the major steps of algorithms, explain long calculations or conditions tied to unobvious state, clarify convoluted or unusual code, and clarify the purpose of non-temporary local variables and fields.
* Java doc: used for classes, interfaces, and methods

### Examples

* classes - use Javadoc formatting before each class
* fields
	// key: variable to store the value of this node

* constructors - use Javadoc formatting before each constructor
* methods - use Javadoc formatting before each constructor
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  * switch statement
  * while loops
  * for loops
  * enhanced for loops
