# Ruby Variables
In Ruby, a variable is a place to store values of almost any type including Integer, Boolean, String, Array, and Hashes.

Each variable has its own name which cannot begin with a capital letter or a number and we use the equal sign for assigning a value to that variable.

The variable declaration does not require that you mention a specific data type.

The following program declares myvar variable and assigns the value 48.
```ruby:
myVar = 48
```

# Puts and print command
Puts and print commands can be used to display text in the console.

```ruby:  
print "Hello"
puts "This is written in a new line"
print "Still printing"

```

# Numeric data types in Ruby
In Ruby, the Numeric data type represents numbers including integers and floats.

```ruby: 
x = 1 #int
y = 1.2 #float
```


# Arithmetic operations in Ruby
In Ruby, we can use arithmetic operators to evaluate mathematical expressions. The most common Ruby arithmetic operators are addition (+), subtraction (-), division(/), multiplication(*), exponentiation(**) and modulo(%).

```ruby:  
print 1+3 # Addition: output 4
 
print 1-2 # Subtraction: output -1
 
print 9/3 # Division: output 3
 
print 2*3 # Multiplication: output 6
 
print 2**3 # Exponentiation: output 8
 
print 16%9 # Modulo: output 7
```
  




# Ruby Object Methods
In Ruby, methods are built-in abilities of objects. To access an object’s methods, you need to call it using a . and the method name.
```ruby:  
var = "ruby"
 
# Method to get the length of a string
print var.length # 4
 
# Method to get the string reversed
print var.reverse # ybur
 
# Method to conver all letters to uppercase
print var.upcase # RUBY

```

# Strings in Ruby
Strings in Ruby are a sequence of characters enclosed by single quotation marks (‘’) or double quotation marks (“”).


```ruby: 
# String 1
s1 = 'I am a single string!'
 
# String 2
s2 = "I am a double string!"

```

# Boolean Data Types in Ruby
In Ruby, in order to represent values of truth about specific statements, we use Boolean variables. Boolean variables values are either true or false.

```ruby: 
# Boolean true variable
year2021 = true
 
# Boolean false variable
year2020 = false

```
# Ruby .upcase and .downcase Methods
Ruby strings have an .upcase and a .downcase method used to change their case. .upcase returns a version of the string in all uppercase, and .downcase returns a version in all lowercase.
```ruby: 
puts "ruby".upcase
# RUBY
 
puts "RUBY".downcase
# ruby

```

# Ruby string interpolation
In Ruby, string interpolation is used to insert the result of Ruby code into a string.

```ruby: 
age = 30
 
print "Hi, my name is Ruby, and I am #{age} years old"
# "Hi, my name is Ruby, and I am 30 years old"

```

