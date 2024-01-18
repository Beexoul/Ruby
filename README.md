# Ruby
Ruby is a dynamic, object-oriented programming language that emphasizes simplicity and productivity. It was designed and developed by Yukihiro "Matz" Matsumoto in the mid-1990s. Ruby is known for its elegant syntax, which is easy to read and write, and its focus on developer happiness.

#### Here are some key features of the Ruby programming language:

1. **Dynamic Typing:** Ruby is dynamically typed, meaning that the type of a variable is determined at runtime.

2. **Object-Oriented:** Everything in Ruby is an object, including numbers and functions. It follows the object-oriented programming paradigm.

3. **Garbage Collection:** Ruby has automatic memory management through a garbage collector, which helps developers avoid manual memory allocation and deallocation.

4. **Interpreted Language:** Ruby is primarily interpreted rather than compiled, which allows for quick and flexible development.

5. **Open Source:** Ruby is an open-source language, and its interpreter is available under the Ruby License, which is a free and open software license.

6. **Gems:** RubyGems is the package manager for Ruby, providing a convenient way to distribute and install libraries (gems) developed by the community.

7. **Rails Framework:** Ruby on Rails (or just Rails) is a web application framework written in Ruby. It follows the Model-View-Controller (MVC) architecture and is known for its convention over configuration principle, enabling developers to write less code to achieve more.

8. **Blocks and Closures:** Ruby has a powerful feature called blocks, which are chunks of code that can be passed around as arguments to methods. Closures, which are essentially blocks of code that can be associated with a surrounding lexical scope, are also supported.

### Some Basic Programs :

1. **Hello World**
   ```ruby
   puts "Hello World!"
   ```

2. **Variables and Data Types**
   ```ruby
   name = "John"
   age = 25
   height = 5.9
   puts "#{name}, #{age}, #{height}"
   ```

3. **Simple Calculator**
   ```ruby
   print "Enter first number: "
   num1 = gets.chomp.to_f
   print "Enter second number: "
   num2 = gets.chomp.to_f
   result = num1 + num2
   puts "Sum: #{result}"
   ```

4. **Conditional Statement**
   ```ruby
   print "Enter a number: "
   num = gets.chomp.to_i
   if num.even?
       puts "Even"
   else
       puts "Odd"
   end
   ```

5. **Loop (Print Numbers 1 to 5)**
   ```ruby
   (1..5).each { |i| puts i }
   ```
