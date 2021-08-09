# html-css-js

**HTML, CSS & JS**


**1.	Center the box horizontally and vertically.**

•	To center the box horizontally and vertically we first set its position to absolute so that it is absolute to its last relative parent. Then we align it from top 50% and left 50% in order to bring it to center. At last, we provide it translate to -50% of its size from left as well as from right.

•	Here is the source code for it:
https://codepen.io/shatakshigupta/pen/KKmrOXZ

<img src="https://user-images.githubusercontent.com/85827044/128728462-5dbfaebf-b060-4a9d-be52-655964eb86bd.png" width="350px" height="200px"/>




**2.	Add two numbers using arrow functions.**

let addTwoNum = (a, b) => a+b;

console.log (addTwoNum (5, 6));

•	Here is the source code for it:
https://codepen.io/shatakshigupta/pen/zYwMgVQ

<img src="https://user-images.githubusercontent.com/85827044/128728460-275eaa6e-8f9f-4638-ad4d-b77769483bf2.png" width="300px" height="200px"/>

	

**3.	How to add elements at the last of an array**

•	To add any element at the last of an array we use push method as array.push(“element”)

•	Here is the source code for it:
https://codepen.io/shatakshigupta/pen/gOWZYyj?editors=1111

<img src="https://user-images.githubusercontent.com/85827044/128728456-8ed74ffe-513f-496f-8d22-7c3e2566eac9.png" width="300px" height="200px"/>



**4.	Draw a SVG Circle of Radius 20-30 m**

•	To draw a SVG Circle we can first define its height and width, it will guide us where do we have to draw that circle. Inside svg tag we will add circle tag with its desired radius and cx(cordinate of x) & cy(cordinate of y). We can provide stroke color and size for that circle. 

Here is the source code for it: 
https://codepen.io/shatakshigupta/pen/Vwbqwqq

<img src="https://user-images.githubusercontent.com/85827044/128728479-9a0e6294-f79e-4f91-bd35-4109d6ed0047.png" width="350px" height="200px"/>



**5.	Function to delete array elements in JavaScript.**

• To delete elements in an array we can use **pop()** method if we want to remove element from the end, **shift()** method if we want to remove element from the starting and **splice()** method if we want to delete element at a particular index. 

•	//Remove element using pop

let array1 = [1, 2, "HI", 5, "Hello"];

console.log(array1.pop()); 

//"Hello" will be printed in console as it is at the last index


•	//Remove element using shift

let array2 = [12, "HI", 5, "Hello", "World", 43];

console.log(array2.shift()); 

//12 will be printed in console as it is at the first index


•	//Remove element using splice

let array3 = ["xyz", 5, 76, 43, "abc"];

console.log(array3.splice(2,1)); 

//[76] will be printed as array of 1 element in console as starting element is on index 2 and only 1 element is deleted

//new array3 will be ["xyz", 5, 43, "abc"];

console.log(array3.splice(1,3));

//[5,43,"abc"] will be printed as array of 3 element in console as starting element is on index 1 and 3 elements are deleted


•	Here is the source code for it:
https://codepen.io/shatakshigupta/pen/jOmXEWm?editors=1012

<img src="https://user-images.githubusercontent.com/85827044/128728474-875f8423-7303-400c-aa3c-669b3dc16d2e.png" width="300px" height="200px"/>




**6.	How can we add elements at any specific position in JS?**

•	To add an element in an array at a specific position, we can use **splice()** method. Splice takes in 3 parameters, first for the inex where we have to start, second for the number of element from that index which we want to delete and third for the element which we have to add.

let array = [12, "HI", 5, "Hello", "World", 43];

array.splice(2, 0, 56);

console.log(array); 

//number 56 will be added at the index of 2 and since second parameter is 0, so no eleent is deleted.

•	Here is the source code for it:
https://codepen.io/shatakshigupta/pen/eYWbmGj?editors=1012

<img src="https://user-images.githubusercontent.com/85827044/128728472-168babd6-0dcc-47ee-aee1-014e0bdbd09b.png" width="300px" height="200px"/>



**7.	Create a anchor tag heading tag and paragraph tag and add LinkedIn link**

**The content in heading tag should be underlined use border to do it**

**Give styling to anchor heading and paragraph tag without using id and class**

**Create a button and change its background color**

**Align text to center, change div background color, add hovering effects, creating links**



•	Here is the source code for the above task:
https://codepen.io/shatakshigupta/pen/gOWZbym?editors=1111


<img src="https://user-images.githubusercontent.com/85827044/128728466-c59e5521-71b0-4f4c-8c7d-6979f2b323f7.png" width="350px" height="200px"/>



