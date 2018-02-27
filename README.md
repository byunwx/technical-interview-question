# technical-interview-questions /* # <--h1 .  * <-- bullet point */

## HTML

### What is DOCTYPE?
* A keyword that alerts the browser how to process a file.

### What is quirks mode?
*technique to use old browser to read undifined DOCTYPE FILES. OR OLD BROWSER TO USE NEW HTML

### <div> vs. <section>.
*visual vs .

### css.
*Cascading Style Sheets.

### HTTP . //s.
*Hyper Text Transfer Protocol //Secure.

### What is the difference between <span> and <div>?
  *
### What is the data-* attribute?
  *
### expression vs declaration of function
  *expresstion = gets hoisted
  *declaration does not

### NODE IS
* open soruce, cross- platform javascript runtime enviroment designed to be run ourtside of browsers.
* Asynchronous Threading - no order

### cms
* content management system

### PHP
* synchronous Threading - answer in ordered of request

## if the string on process.argv[2] is palindrome console.log palindrome if not not palindrome
```javascript
var string = process.argv[2];
var stringHalf = 10;
var count= 0;

if (string.length%2 == 0) {
  stringHalf= string.length/2-1;
  for (var i = 0; i < stringHalf; i++) {
    if(string[i]==string[string.length-1-i]){
      count+=1;
    }
  }
} else {
  stringHalf= (string.length-1)/2;
  for (var i = 0; i < stringHalf; i++) {
    if(string[i]==string[string.length-1-i]){
      count+=1;
    }
  }
}


if (count==stringHalf && string.length>1) {
  console.log(process.argv[2]);
  console.log("is palindrome");
}else if(string.length==1){
  console.log("You only have one letter")
}else{
  console.log(process.argv[2]);
  console.log("is not palindrome")
}
```
### Write a function that outputs an array of the nth Fibonacci number.
```javascript
var processNum=[0, 1];
var results=processNum[n];
var n= process.argv[2];

if(n>1){
  for (var i = 2; i <= n; i++) {
    var added= processNum[i-1]+processNum[i-2];
    processNum.push(added);
  }
  console.log(processNum.join(" + "))
  console.log(processNum[n]);
}else if(n==0){
  console.log("0");
  console.log(processNum[n]);
}else{
  console.log(processNum.join(" + "))
  console.log(processNum[n]);
}

```
