# Ruby Cheatsheet 


## Basics of Ruby 

- In Ruby, a variable is a place to store values of almost any type including Integer, Boolean, String, Array, and Hashes.
```
var = 92
```
**When doing arithmetic with two integers in Ruby, the result will always be an integer.**
```
12/3
                ==> Both give the same answer
12/3.0
```

## Number Types Conversion

```
# To convert an integer to a float:
18.to_f   #=> 18.0

# To convert a float to an integer:
12.0.to_i #=> 12
11.9.to_i #=> 11
```

## Use Put and Print to display the text in the console

## The general syntax of an if statement :
```

if 1 < 2
  puts "Jump and go"
end

=================

if that_is == true
  puts "yay"
else
  puts "Nay!"
end

```
## <=> (spaceship operator) returns the following:
```
-1 if the value on the left is less than the value on the right;
0 if the value on the left is equal to the value on the right; and
1 if the value on the left is greater than the value on the right.
```

## Unless statements
- An unless statement works in the opposite way as an if statement: it only processes the code in the block if the expression evaluates to false. There isn’t much more to it.

## ternary operator

```
syntax is conditional statement ? <execute if true> : <execute if false>
```


