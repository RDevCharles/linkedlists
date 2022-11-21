# Array Recap & Linkedlists

#### What is an Array?
A data structure that allows for the storage of multiple items under a single variable name. The elements of this data structure are accessed using a zero based index.
[Why arrays are 0 indexed](https://developerinsider.co/why-does-the-indexing-of-array-start-with-zero-in-c/) 

As we know the this how we may declare one: 
```sh
const myArray = [1,2,3,4,5,6,7,8]
```
And if we want to access the first element in this array here's how we do it.
```sh
myArray [0] // this gives us access to the value number 1
```
#### But What is an Array...really?
At the end of this morning exercise you will be able to:

- Know the differnce between static arrays and dynamic arrays
- Understand the limitations of this data structure
- What is a linked list

> If you don't fully understand the data structure 
> then you won't know how to manipulate it.

## Static Arrays (aka fixed-length arrays or fixed arrays)
Static arrays have their length determined when the array is created.

## Dynamic Arrays
A dynamic array is an array with a big improvement: automatic resizing. These are the kind of arrays that we've been dealing with. Languages like javascript and python use dynamic arrays by default so these are the arrays we have been dealing with.

## A downfall of Arrays
Arrays tend to be the goto data structure when we program. If we need to store a few values? Throw it in an array. Need to program dynamically? An array may be your best freind. But there's a computational tax we don't consider when we utilize arrays. 

When we store an array, whether it is a static array in a language like C or dynamic array in Javascript memory is allocated the same. Let's take a look at what happens when push a few elements:


=============> Create image for this
```sh
const myArray = [1,2,3,4,5,6,7,8] //[1,2,3,4,5,6,7,8, , ,]
```

## Linked Lists
We've learning that an array is stored in contiguios memory and copied then resized when needed.
So as we can see when adding to our array we pay that tax. Enter linked lists.
A linked list data structure stores a list of nodes (we call these elements in an array) where each node holds a value and a pointer that points to another value. <======= Expound on this.
Lets visualize our node right next to how we would code it.

ENTER IMG HERE
