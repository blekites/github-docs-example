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
<img width="200" src="https://github.com/blekites/github-docs-example/assets/145223303/b344059c-b5fb-4a6c-81d4-149cd438777c" />


