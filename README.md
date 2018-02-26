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


if (count==stringHalf) {
  console.log("palindrome");
}else{
  console.log("not palindrome")
}

