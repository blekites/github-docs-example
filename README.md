# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.  
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```
- Make note of where the backtick keyboard key is located.
- It should appear above the tab key 
- But it may vary based on you keyboard layout.

<img width="200" src="https://github.com/blekites/github-docs-example/assets/145223303/b344059c-b5fb-4a6c-81d4-149cd438777c" />

Good Cloud engineers use codeblocks for both Code and Errors that appear in the console. [<sup>[1]</sup>](#external-references)

```bash
begin
  result = divide(10, 0)
  puts "Result: #{result}"
rescue ArgumentError => e
  puts "Error: #{e.message}"
end
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 2 - How to take screenshots  

A screenshot is when you capture a part of your screen from your laptop, desktop or phone.  
This is not to be confused with taking a photo with your phone.  


## Step 3 - Use Github Flavored Markdown Task Lists

- [x] Finish Step 1
- [x] Finish Step 2
- [x] Finish Step 3

Github extends Markdown to have a list where you can check off items.

## Step 4 - Use Emojis (Optional)

Github Flaored Markdown (GFM) supports Emoji shortcodes.  
Here are some examples:  

| Name | Shortcode | Emoji |  
| --- | --- | --- |  
| Cloud | `:cloud:` | ☁️: |  
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️: |

## Step 5 - How to create a table

You can use the following markdown format to create tables:  

```md
| Name | Shortcode | Emoji |  
| --- | --- | --- |  
| Cloud | `:cloud:` | ☁️: |  
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️: |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.[<sup>[2]</sup>](#external-references)  


## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>

  
