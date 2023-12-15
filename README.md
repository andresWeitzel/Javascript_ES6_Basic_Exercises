# Javascript_ES6_Basic_Exercises
Basic javascript exercises with version 6 of the ECMAScript standard

 <br>

<!------Start Index----->

## Index 📜

<details>
 <summary> See </summary>
 <br>
  
 ### Section 1) Strings and Objects
* [Write a JavaScript Program to Copy a String to an Empty String.](#write-a-javascript-program-to-copy-a-string-to-an-empty-string-)


### Section 2) Arrays
* [Create an array with random numbers and loop through it.](#write-a-javascript-program-to-copy-a-string-to-an-empty-string-)
 
 
<br>

</details>

<!------Stop Index----->

<br>

<br>

## Section 1) Strings and Objects

### Write a JavaScript Program to Copy a String to an Empty String [🔝](#index-)

<details>
  <summary>See solution</summary>
 <br>

#### Solution
 ```js
let emptyString = "";
let stringWithContent = "7623762736762367";
emptyString = emptyString + stringWithContent;

console.log(emptyString);
 ```

#### Console
 ```js
7623762736762367
 ```

<br>

</details>

<br>

<br>


## Section 2) Arrays

### Create an array with random numbers and loop through it [🔝](#index-)

<details>
  <summary>See solution</summary>
 <br>

#### Solution
 ```js
let arrayRandomNumbers = [12,32,31,66,7,928];

let arrayRandomNumbersResult = [...arrayRandomNumbers];

console.log(arrayRandomNumbersResult);
 ```

#### Console
 ```js
(6) [12, 32, 31, 66, 7, 928]
0:12
1:32
2:31
3:66
4:7
5:928
 ```

<br>

</details>
