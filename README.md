# Writing Good Documentation

## Step 1 - Useing Codeblocks.

Codeblocks in markdown make it very easy for tech people to **copy, paste and share** code.
A good _Cloud Engineer_ uses Clodeblocks whenever possible

Because it allows others to copy and paste their code to replicate or research issues.

In order to use codeblocks in markdown you need to use backticks `

```
class Person
  attr_accessor :name, :age, :email

  def initialize(name, age, email)
    @name = name
    @age = age
    @email = email
  end

  def introduce
    puts "Hello, my name is #{@name}, I am #{@age} years old, and you can reach me at #{email}."
  end
end

# Create a new Person object
person1 = Person.new("Alice", 30, "alice@example.com")

# Access and modify attributes
person1.age = 31

# Call the introduce method
person1.introduce
```
