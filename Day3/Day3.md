```
for(r=1;r<=5;r++)
{
  str = ""
  for(c=1;c<=r;c++)
  {
    str += "* "    
  }
  console.log(str)
}
```
```
for(r=1;r<=5;r++)
{
  str = ""
  for(s=1;s<=5-r;s++)
  {
    str += "  "    
  }
  for(c=1;c<=r;c++)
  {
    str += "* "
  }
  console.log(str)
}
```
```
a = 2
z = a++
console.log(z, a)
y = 2
x = ++y
console.log(y, x)

a = 2
z = a++ + ++a + a-- + --a
console.log(z, a)
```
z = 2 + 4 + 4 + 2
a = 2
```
for(i=1;i<=5;i++)
{
  console.log(i)
}
```
```
i=1
while(i<=5)
{
  console.log(i)
  i++
}
```
```
i=1
do {
  console.log(i)
  i++
} while (i<=5);
```

Strings and Arrays
```
s = "Vrishti"
for(i=0;i<s.length;i++)
{
  console.log(s[i])
}
console.log(s.substring(0,3))
```
