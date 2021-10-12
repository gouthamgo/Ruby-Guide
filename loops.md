# Loops in Ruby


## Loop
- The loop **loop**  is Ruby’s loop is an infinite loop that will keep going unless you use the break command. 
```
i = 0
loop do
  puts "i is #{i}"
  i += 1
  break if i == 10
end
```

## While
- A while loop is similar to the loop loop except that you declare the condition that will break out of the loop up front.
```
i = 0
while i < 10 do
 puts "i is #{i}"
 i += 1
end
```

## Until

- The until loop is the opposite of the while loop. 
- A while loop continues for as long as the condition is true, whereas an until loop continues for as long as the condition is false

## Ranges

-Ruby lets us use something called a range to define an interval. 
- give Ruby the starting value, the ending value, and whether we want the range to be inclusive or exclusive.

```
(1..5)      # inclusive range: 1, 2, 3, 4, 5
(1...5)     # exclusive range: 1, 2, 3, 4

```

## For

- A for loop is used to iterate through a collection of information such as an array or range. 


```
for i in 0..5
  puts "#{i} zombies incoming!"
end
```


## Times 

```
5.times do
  puts "Hello, world!"
end

```
## Upto & Downto

- The Ruby methods #upto and #downto do exactly what you’d think they do from their names. 
- You can use these methods to iterate from a starting number either up to or down to another number, respectively.

```

5.upto(10) {|num| print "#{num} " }     #=> 5 6 7 8 9 10

10.downto(5) {|num| print "#{num} " }   #=> 10 9 8 7 6 5


```
