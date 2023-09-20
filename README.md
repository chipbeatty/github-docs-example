# Writing Good Documentation


## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tect people to **copy, paste, share** code. A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (```)
- Not to be confused with quotation (')

```
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}"
end
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```rb
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}"
end
```

- Make note of where the backtick button is located.
- It should appear above the tab key,
- but it may vary based on your keyboard layout.

  
![0058392-tmin-240x135](https://github.com/chipbeatty/github-docs-example/assets/81486675/97603428-0bfb-47af-a875-491bc6f67bc9)

Good cloud engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
        1: from (irb):1
NameError (undefined local variable or method `undefined_variable' for main:Object)
```

> Here is an example of using a codeblock for an error that appears in bash.
