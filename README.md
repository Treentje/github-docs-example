# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very* easy for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation(')
  
```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate and print the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

- When you can you should attempt to apply syntax hightlighting to your codeblocks

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate and print the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

- Make not of where the backtick button is located.
- It should appear above the tab key, but may vary based on your keyboard layout.

![DSC_6705](https://github.com/Treentje/github-docs-example/assets/57364053/c1db1b76-9793-4efa-afbe-6d77c271a2cc)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  2: from /usr/bin/irb:23:in `<main>'
  1: from (irb):1
RuntimeErrpr: This is a custom error message
```

> Here is an example of using a codeblock for an error that appears in bash.

## References

 - [Github Flavoured Markdown Specs](https://github.github.com/gfm/)
 - [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
