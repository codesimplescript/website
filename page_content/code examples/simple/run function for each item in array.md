This code will send each item in an array to a function to run. Allowing you to run a function many times using the different items in an array.

```
v.animals[0]="cat"
v.animals[1]="dog"
s.array_loop("pets",v.animals)

f.pets{
  v.pet=v.function_passed[0]
  s.echo("Oh, did you know I have a v.pet?<BR>I like v.pet's.<BR>")
}
```
