# Writing Good Documentation 

## Step 1 - Using Codeblocks

Codeblocks u označavanju make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste theire code to replicate or research issues.

- In oreder to create codeblocks in markdown you need to ***use three backticks (`)***
- Not to be confused with qoutation (')

**Example git commands**
```
git status 
git add 
git commit
```

**Ruby example code**
```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial: "
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}"
end
```

# How to create a table 
| Cloud | `☁️` | ☁️ |

[Hidden Files Markdown](secret/hidden-garden.md)

## References
- [GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github

_Thank you for reading this mini bio_ `❤️`
