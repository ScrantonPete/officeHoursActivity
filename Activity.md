//Without running the code, determine what the following code will output and why:

<!-- Setting a variable = 1 -->

creating a function called outer
defines var a =2
creating a function called inner
console log will be 5

var a = 1;
function outer(){
var a = 2;
function inner(){
a++;
console.log(a);
var a = 5;
}
inner();
}
outer();

NaA since variable a was not defined before the console log within the inner function
