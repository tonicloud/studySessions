<img src="http://www.skylabcoders.com/images/403/default.png" alt="Skylab" style="width:200px;height:45px;">

## Methods

http://www.w3schools.com/JS/js_functions.asp

*Simple JS Methods for example.*

```
var today, someday, text;
today = new Date();
someday = new Date();
someday.setFullYear(2100, 0, 14);

if (someday > today) {
    text = "Today is before January 14, 2100.";
} else {
    text = "Today is after January 14, 2100.";
}
console.log(text)

```
:angry: This exercises only can be do with **METHODS**

---


### Strings
a) Hello again! I don't remember you'r name, you can tell me again please?
Write your name and count how much letters have
```
console.log(myName) // My Name has 4 letters 
```

b) In what position is you'r first lastname??
```
console.log(myString)// Your first last name is on position 5
```
 
c) Now, show for console **ONLY** your nane 
```
console.log(myString) // My Name is Tony 
```
 
d) Now, your second lastname 
```
console.log(myString) // My lastname is Stark
```
 
e) Now, replace your *name* for "Mr/Ms" and show the lastname as same 
```
console.log(myNewString) // Hello, Mr. Stark 
```
 
f) Now, select your first lastname and converts to Upper Case
```
console.log(mySelection) // my lastname is STARK
```

g) Now, add one message in other string var and join to other name string, show it for console
```
something = myNameVar + "is awesome"
console.log(something) \\ "Tony is awesome"

```

h) Now, you can select the first letters of your lastnames and show they?
```
console.log(myFirstLastnameLetters) // S.Y
```

i) Convert your name to array, saparated elements by "/"
```
console.log(myName) // T/O/N/Y
```

j) Catch your lastname and show every letter separated by "|"
```
console.log(myLastName) // S|T|A|R|K
```


### Numbers
a) What time is it? Converts it to string and show it for console
```
console.log(myString + myNumberStringify) // I'ts 10.34 of morning
```

b) What time is it exactly? Show it without the minutes.
```
console.log(myString) // It's around 10 of morning
```

c) Now, try to convert your hour var with minutes to entire number without minutes and show it
```
console.log(parse...(10.34)) // 10!
```

d) We can do a calculator, so let's do it! first, do a sum with two numbers
```
console.log(sum) //The sum of 7+3 is 10
```

d1) Add the rest...
```
console.log(sum + rest) // The sum and rest of 7 and 3 is 10 and 4 
```

d2) And the multicity
```
console.log(sum + rest + mult) // 10, 4 and 21
```

d3) Finally, the division
```
console.log(sum + rest + mult + div) // 10, 4, 21 and 2.3
```

d4) Now, try to execute a multiplicity like 10 * "hour", what value is returned?
```
console.log(10*"hour") // ....?!
```

e) Don't worry, we can catch this error, you can controle it with **if conditional**?
```
console.log(10*"hour") // You can't do this operation!
```

f) With other conditional, returns other operation
```
console.log(10) // I return the same value...
```

### Dates

a) Hey! You can tell me what year we are?!
*Declare a object Date using var d = new Date();*
*This objects contains all information about date, and of course, the methods that we can use for this exercises.*
```
console.log(d) // We are in 2016
```

b) Sorry... I lost the memory... In what day of weekend?
```
console.log(d) // Itchhh... Wake up! We are living in day 3!
```

c) You can tell me the number of seconds between your birthday to now?
```
console.log(a) // 19827379 seconds since my birthday
```

d) And days? 
```
console.log(b) // 50098 days
```

e) You can do a comparator between one date and now? Show a message if one date is before or after 10 June, 1986
```
now = new Date();
someday = new Date();
someday.set....(1986, 5, 10)
console.log(...) // Today is after someday
```

f) You can do other comparator... only with years? Do multiple comparators and sshow the messages
```
console.log(...)
// 1987 is before now
// 2980 is after now
// 2016 is now!
// 1098 is before now
// This is not a year...
```


---

## Free Challenge!! 

=> You can do a person comparator? Specify the name, age, city and birthday using methods for get the info. Specify 5 persons and do some comparations betwheen they and show some messages.
```

// Silvia, who have 15 years is older than David, who id 34 years
// If Silvia was 20 years older, David would be younger than Silvia
// But the younger of they is Alex, who is 3 years old
// The older is Ferran, who is 90 years old, and between he and Alex are 87 years difference!

```



