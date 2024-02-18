What is an Array
An array is a collection of data.
An array can only contain one kind of data at a type
Examples:
Integer Array : [1,4,2,55,43]
String Array : [“Hello.”, “Do”, “you”, “see”, “that?”]
Double Array : [3.14, 2.71, -1.0, 0.0]
Uses of Arrays
A List of people
Test Data
Common Array Keywords
Append
Adds an element to a list
Foreach
Iterates through an array like a for-loop
Concat
 Combines 2 arrays
Pop
Removes the last element of the array and returns it
Splice / SubList
Takes out part of the array and returns it
Join
Combines all the elements of an array into one big string
IndexOf
Finds the index of an element in an array
Length
returns the length of an array
Remove
Removes an element from the array

Arrays in AP CollegeBoard PsuedoCode




Arrays in SwiftUI
Defining an Array
var variableName : [DataType] = [data,data,data]
var variableName = [data,data,data]
var variableName : [DataType]()
Array Methods
print(arrayName)
Prints out all the arrays of an array
[1,2,3,4,5]
array.append(data)
Adds an element to an array
[1,2,3,4,5].append(6) => [1,2,3,4,5,6]
array.append(contentsOf: array2)
Combines 2 arrays
[1,2,3].append(contentsOf:[4,5,6]) => [1,2,3,4,5,6]
array.insert(data, at: index)
Adds an element to an array at an index
[1,2,3,4].insert(6, at: 2) => [1,2,6,3,4]
array[index] = newData
Modifies the element at index
array.remove(at: index)
Removes and returns an element at index
[1,2,3,4].remove(at: 3) => [1,2,3]
array.sort()	
sorts array elements
array.shuffle()
changes the order of array elements
forEach(array, id: \.self){element in …}
calls a function for each element
array.contains(data)
searches for the element in an array
array.swapAt(index1,index2)
exchanges the position of array elements
array.reverse()
reverses the order of array elements
