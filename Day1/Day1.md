<div align="center">
  <h1>Day 1 Notes</h1>
</div>

### `Printing On Console`
```
console.log("Hello, World!");
```
### `Variable Declaration using let keyword`
```
let name = 'Vrishti Gupta'
console.log('Vrishti')
```
### `Mathematical operations`
```
let a = 10
let b = 3
console.log(a+b)
console.log(a-b)
console.log(a*b)
console.log(a/b)
console.log(a%b)
```

### `Relational Operations`
```
e = 10
f = 10
c = e==f
a = e>f
console.log(c)
console.log(a)
```

### `Conditional Statement`
#### To check whether no. is positive, negative or zero
```
a = -10
if(a>0)
{
  console.log("Its a positive number")
}
else if(a<0)
{
  console.log("Its a negative number")
}
else
{
  console.log("Its a negative number")
}
```

#### Leap Year
```
a = 2001
if(a%4 == 0)
{
  if(a%100 == 0)
  {
    if(a%400 == 0)
    {
      console.log("Leap Year")
    }
    else
    {
      console.log("Not a Leap Year")
    }
  }
  else
  {
    console.log("Leap Year")
  }
}
else
  {
    console.log("Not a Leap Year")  
  }
```
### `Loop`
```
for(i=0;i<5;i++)
{
  console.log(i)
}
```
```
for(i=0;i<5;i++)
{
  console.log('*')
}
```
### `Assignment Question`
```
str = ""
for(i=0;i<5;i++)
{
  str += '* '
}
console.log(str)
```
