## Array methods
## 1. Creating an array
### i) literals
>>>>>let arr_nums = [1,4,5]
### ii) Array Constructor
>>>>> let scores = new Array()

To create an array and initialize it using array and constructor

>>>>>let scores = new Array(5,6,7,8)

## 2. Accessing Array elements

To access the elements in an array, specify the index in brackets. Note array indexes start at zero.

```javascript
arrayName[index]
e.g
scores[1] //  outputs 6
```
## 3. Array size
Length property returns the size of the array.
```javascript
scores.length
```
# Basic array operations
## 4. Adding elements in array
### i) Unshift()
Adds elements at the beginning of the array
```javascript
scores.unshift(3)
```
**Returns** the length of the new array

### ii) push()
**Usecase** Adds an element at the end of the array
**Return** It returns the length of the new array

```javascript
scores.push(2)
```

## 5. Removing elements from an array
### i) shift()
**Usecase** Removes the first element in the array
**Return** Returns the removed element

```javascript
scores.shift()
```
### ii) pop()
**usecase** Removes the last element in an array
**Return** Returns the removed element
## 6. Transversing an array
### i) for loop
```javascript
for(let i=0; i<array.length;i++){
    //logic
}
```
# Other Array methods
##