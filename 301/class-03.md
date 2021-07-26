# **Passing Functions as Props**

## Lists & Keys

1. **What does .map() return?**

   * It returns a map object, which iterates through an array and calls a specified function for each of the items. For each object in the array, a block of JSX elements is returned.

2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**
   * array.map(function(currentValue, index, arr), thisValue) and all items need a unique `key`, by this key you will be able to return the actual needed data.

3. **Each list item needs a unique `Key`.**

4. **What is the purpose of a key?**
   * Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

***

## The Spread Operator

1. **What is the spread operator?**

* **Spread syntax** refers to the use of an ellipsis of three dots `(…)` to expand an iterable object into the list of arguments.

2. **List the things that the spread operator can do:**

* Copying an array.
* Concatenating arrays.
* Using `Math` functions.
* Using an array as arguments.
* Adding an item to a list.
* Adding to state in React.
* Combining objects.
* Converting NodeList to Array.

3. **Give an example of using the spread operator to combine two arrays.**

```
  let arrOfMales = ["Mohammad" , "Anas" , "Malik"];
  let arrofFemales = ["Sara" , "Shahd" , "Farah"];
  let arrBothGender = [...arrOfMales , ...arrofFemales];
  //The result will be for arrBothGender = ["Mohammad", "Anas", "Malik", "Sara", "Shahd", "Farah"];
```

4. **Give an example of using the spread operator to add a new item to an array.**

```
let array1 = [21, 20, 19];
let array2 = [18, 17, ...a]; 
```

```
then array2 = [21,20,19,18,17]
```

5. **Give an example of using the spread operator to combine two objects into one.**

```
let student = { name: 'Mohammad Harb', gender: 'Male' };
let major = { name: 'Industrial Engineering', NumberOfSemesters: '10' };
let fullInfo = {...student, ...major};

/*
Object {
  "name": "Industrial Engineering",
  "NumberOfSemesters": "10",
  "gender": "Male",
  "name": "Mohammad Harb",
}
* /
```

***

## Passing Functions Between Components

1. **In the video, what is the first step that the developer does to pass functions between components?**

creat a function and pass name object to it.

2. **In your own words, what does the increment function do?**

its looping throw the names of the objects and check if the name choosen and it matched the name inside the old object then counter will be increasing for that name by one. After that it will be returning to the new variable. Finally the state of the old object will be updated.

3. **How can you pass a method from a parent component into a child component?**

passing it as props to Child.

4. **How does the child component invoke a method that was passed to it from a parent component?**

before the `render()`

```
this.props.'give a function name'('the element that you want to be changed')
```

then using onClick button.

***
