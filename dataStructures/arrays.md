## Arrays
A collection of items stored at continuous memory locations
Arrays represent many instances in one variable


### Declaring Arrays in C and C++

int arr[10];
int arr[] = {10, 20, 30, 40};

#### Accessing elements
int arr[5];
arr[0] = 5;
arr[2] = -10;

### Arrays in Java
Work differently than in C.
In java all arrays are dynamically allocated.
Java find length of array using member length since its an object.
Size of an array must be specified by an int value.

#### Declaration
One-Dimensional Array:
type var-name[];
type[] varname;
type determines data type of each element in array
byte byteArray[];
short shortArray[];
MyClass myClassArray[];

#### Instatiating an Array
var-name = new type [size];
int intArray[];
intArray = new int[20]; OR int[] intArray = new int[20];

#### Accessing elements in java array using loop
for (int i = 0; i < arr.length; i++) 
  System.out.println("Element at index " + i + " : "+ arr[i]);

### Array index out of bounds exception
Occurs when array has been accessed with an illegal index. Negative or greater than or equal to size of array

### Multidimensional Arrays
arrays of arrays with each element of an array holding a reference to another array. Also known as jagged arrays.
Created by appending one set of square brackets ([]) per dimension.

int[][] intArray = new int[10][20]; // a 2D array or matrix
int[][][] intArray = new int[10][20][30]; // a 3D array
