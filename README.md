# Writing Good Documentation

## Step 1 - Useing Codeblocks.

Codeblocks in markdown make it very easy for tech people to **copy, paste and share** code.
A good _Cloud Engineer_ uses Clodeblocks whenever possible

Because it allows others to copy and paste their code to replicate or research issues.

In order to use codeblocks in markdown you need to use backticks `

```ruby
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


- Make note of where the backtick button is located.
- It should appear above the TAB key.
- But it may vary on your keyboard type.


![backtick](https://github.com/reinierengelbrecht/github-docs-example/assets/58253566/141b7052-06ab-4baa-a391-8d00d3b86210)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

> Here is an example of using codeblock for an error that appears in bash.

```bash
ZeroDivisionError: divided by 0
  from (irb):2:in `/'
  from (irb):5:in `divide_by_zero'
  from (irb):8
  from /usr/bin/irb:11:in `<main>'
```

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[1]</sup>

## References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GFM Task lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>

  
