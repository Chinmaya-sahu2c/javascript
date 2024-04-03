Primitive Datatype

Primitve data types are the most basic data types. They are directly stored in the memory. They are immutable. it includes : 

1-->Number: used to store decimal as well as floating point numbers. 
eg. let num = 10 let num1 = 12.3 let n = 123; n = 12.345;

2-->String: Used to store a sequence of characters.Anything which is enclosed within single or double quotes is considered as string. 
eg. let str = "Hello"; let str2 = 'Single quotes are ok too'; let phrase = can embed another ${str};

3-->Boolean: it basically contains two types of values, which is true or false. eg. let isAdmin = false eg. let isUser = true let nameFieldChecked = true; // yes, name field is checked let ageFieldChecked = false;

4-->null: it signifies absence of a value or placeholder for an object that doesn't exist. eg. let a = null

5-->Undefined: when a variable is declared but hasn't been assigned a value then it is called undefined. eg. let firstName = Undefined eg. let name; let age; alert(age); // shows "undefined"

6-->BigInt: it is used it decimal numbers with larger size. eg. let num = BigInt(1334899983342) const bigInt = 1234567890123456789012345678901234567890n;

7-->Symbol: returns a unique symbol or identifier. 
eg. let s = Symbol("hello"); const sym1 = Symbol(); const sym2 = Symbol("foo");

In conditional statements we have 

1--> if-else syntax:-->if 
if(condition){ 
    
    //Operation 
   
    }else{ 
        
        //Operation 
    }

eg. if (year == 2015) { 
    alert( "That's correct!" );
    alert( "You're so smart!" ); 
    }

2--> if-else syntax: if(condition){ 
   
    //Operation 
    
    }else{ 
        
        //Operation 
    }

eg. let year = prompt('In which year was the ECMAScript-2015 specification published?', ''); 
if (year == 2015) { 
    alert( 'You guessed it right!' ); 
    } else { 
        alert( 'How can you be so wrong?' ); // any value except 2015 
    }

23--> if-else if-else syntax: if(condition){ 
    
    //Operation 
    
    }else if(condition){
        
         //Operation
         
          } . else if . else if . else if 
          
          else{ 
            
            //Operation 
            
        }


eg. let year = prompt('In which year was the ECMAScript-2015 specification published?', ''); 

if (year < 2015) { 
    alert( 'Too early...' ); 
    } else if (year > 2015) { 
        alert( 'Too late' );
        } else { 
            alert( 'Exactly!' ); 
            }

3-->Switch syntax: let x 
switch(x){ 
    case value: //operation 
    break; 
    case value: //operation 
    break; case value: //operation 
    break; 
    default: //Operation
}

eg. let num1 = Number(prompt("Enter 1st number")); 
    let num2 = Number(prompt("Enter 2nd number")); 
    let Operation = prompt("Enter a operation (+, -, *, /, %)");

switch(Operation){ 
    case '+': console.log(${num1}${Operation}${num2} = ${num1+num2}); 
             break; 
    case '-': console.log(${num1}${Operation}${num2} = ${num1-num2}); 
            break; 
    case '*': console.log(${num1}${Operation}${num2} = ${num1*num2}); 
            break; 
    case '/': console.log(${num1}${Operation}${num2} = ${num1/num2}); 
            break;
    case '%': console.log(${num1}${Operation}${num2} = ${num1%num2}); 
            break; 
    default: console.log("Opeation doesn't exist, Please enter a valid operation");
}
                              or
let a=parseInt(prompt('Enter First number: '));
let b=parseInt(prompt('Enter second number: '));
let c=prompt('Enter a operator +,-,*,/');
let output;
switch(c){
case '+':output=a+b;
         console.log(output);
	break;
case '-':output=a-b;
         console.log(output);
	break;
case '*':output=a*b;
         console.log(output);
	break;
case '/':output=a/b;
         console.log(output);
	break;
default:console.log("Opeation doesn't exist, Please enter a valid operation");
}
