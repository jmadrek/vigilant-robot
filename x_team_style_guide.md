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

* classes
/**
 * This balanced search tree class implements SearchTreeADT with the type of AVL
 * to sort items. This data type enables to achieve O(logN) for lookup, insert, 
 * and delete operations. 
 */
public class BalancedSearchTree<T extends Comparable<T>> implements SearchTreeADT<T> {
* fields
	// key: variable to store the value of this node
	// left: pointer variable pointing to its left child
	// right: pointer variable pointing to its right child
	K key;
 Treenode<K> left;
 Treenode<K> right;
* constructors
		/**
	 * Constructor to initialize node
	 * <p>
	 * @param item: value to store in the new node
	 * @param left: pointer pointing to its left child
	 * @param right: pointer pointing to its right child
	 */
		public Treenode(K item, Treenode<K> left, Treenode<K> right) {    
			key = item;
			this.left = left;
			this.right = right;
		}
* methods
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  * switch statement
  * while loops
  * for loops
  * enhanced for loops
  
   Selection and looping statements do not require braces if their body contains only one statement.
   Use tabs/spaces to indicate the level of nesting. Indentation occurs in fixed-width intervals, four whitespaces specifically. 
   
  statement header {
      body
      body
  }
