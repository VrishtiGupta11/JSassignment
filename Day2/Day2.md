<div align="center"
   <h1>Day 2 Notes</h1>
</div>

---
### `Nested for loop` 
`Ex-1.` 
```
* * * * *  
* * * * *  
* * * * *  
* * * * *  
* * * * *  
* * * * *  
```
```
for(i=0;i<6;i++)
{
  let str = ""
  for(j=0;i<5;j++)
  {
    str += "* "
  }
  console.log(str)
}
```

`Ex-2.`
```
*  
* *  
* * *  
* * * *   
* * * * *  
```
```
for(r=0; r<5; r++)
{
  s = ""
  for(c=0; c<=r;c++)
  {
    s += "* "
  }
  console.log(s)
}
```

`Ex-3.`
```
        *
      * *
    * * *
  * * * *
* * * * *
```
```
for(r=5;r>=1;r--)
{
  s=""
  for(c=r-1;c>=1;c--)
  {
    s += "  "
  }
  for(i=6-r;i>=1;i--)
  {
    s += "* "
  }
  console.log(s)
}
```
