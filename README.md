# COP2664-1-Lesson-5-Programming-Exercise-5.2
This is a GitHub repository link for Programming Exercise 5.2 of Lesson 5.

// This program is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.

import Foundation // The library that allows the program to use the functions of the Swift programming language.
var array = [1, 2, 3, 4, 5, 6] // The array that will be used to determine if the number 5 apears in the array as the first or last element of a set of numbers.
var array2 = [1, 2, 3, 4]
var array3 = [1, 2, 3, 4, 5]
var array4 = [1, 2, 3]
var array5 = [1, 2, 3, 4, 5, 6, 7]
func firstLast(array: [Int]) -> Bool { // This function is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
  if array.first == 5 || array.last == 5 {
    return true
  } else {
    return false
  } 
}
print(firstLast(array: array))
print(firstLast(array: array2))
print(firstLast(array: array3)) // This prints out the result of the function.
func firstLast2(array: [Int]) -> Bool {
  if array.first == array.last { // This function is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
    return true
  } else {
    return false
  }
}
print(firstLast2(array: array))
print(firstLast2(array: array2))
print(firstLast2(array: array3))
func sum(array: [Int]) -> Int { // This function is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
  var sum = 0
  for i in array { // This for loop is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
    sum += i
  }
  return sum
}
print(sum(array: array))
print(sum(array: array2))
print(sum(array: array3))
func sum2(array: [Int]) -> Int { // This function is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
  var sum = 0
  for i in array {
    if i == array.first || i == array.last { // This if statement is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
      sum += i
    }
  }
  return sum
}
print(sum2(array: array))
print(sum2(array: array2))
print(sum2(array: array3))
func sum3(array: [Int]) -> Int { // This function is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
  var sum = 0
  for i in array {
    if i == array.first && i == array.last { // This if statement is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
      sum += i
    }
  }
  return sum
}
print(sum3(array: array))
print(sum3(array: array2))
print(sum3(array: array3))
func sum4(array: [Int]) -> Int { // This function is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
  var sum = 0
  for i in array {
    if i == array.first && i == array.last { // This if statement is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
      sum += i
    }
  }
  return sum
}
print(sum4(array: array))
print(sum4(array: array2))
print(sum4(array: array3))
func sum5(array: [Int]) -> Int { // This function is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
  var sum = 0
  for i in array {
    if i == array.first && i == array.last { // This if statement is used to determine if the number 5 apears in an array as the first or last element of a set of numbers and if it does it will print out the number of times it appears in the array making it either true or false.
      sum += i
    }
  }
  return sum // This returns the sum of the array.
}
