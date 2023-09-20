# WRITING GOOD DOCUMENTATION
## STEP 1: USING CODEBLOCKS
CodeBlocks in markdown makes it *very easy* to tech people to **copy, paste and share**.
A good __cloud Engineer__ uses codeblocks whenever possible.
Because it allows other people to copy, paste their code to replicate or research issues.

```
# Define a recursive function to calculate factorial
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Get user input for the number
print "Enter a number: "
number = gets.chomp.to_i

# Calculate and display the factorial
if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```
- when you can attempt to syntax highlighting to your codeblocks.
```ruby
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Get user input for the number
print "Enter a number: "
number = gets.chomp.to_i

# Calculate and display the factorial
if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```
- Make note of where the backtick keyboard key is located.
- It should appear above the tab key, 
- but it may vary based on your keyboard layout.
-  Add an Image. !()[]
-  resize the image use html
![backtick](asserts/backtick.JPG)


- Good cloud Engineers use codeblocks for both code and error that appear on the console.Error in the console should be always in the bash.
   
```bash
Traceback (most recent call last):
        1: from (irb):1
NameError (undefined local variable or method `undefined_variable' for main:Object)
```
> Here is an example:

## Step 3: Use Github flavored Markdown Task Lists
Markdown extends Markdown to have a list where you check off items [<sup>[1]</sup>](#external-references)

- [X] Finish step 1.
- [ ] Finish step 2.
- [X] Finish step 3.

## Step 4: Use Emojis (optional)
GitHub Flavored Markdown (GFM) supports Emojis shortcodes
Here are some examples:
| Name | Shortcode | Emoji |
| --- | --- | --- |
| cloud | `:cloud:` | :cloud: |
| --- | --- | --- |
| cloud with lightning | `:cloud_with_lightning` | 🌩️ |

## Step 5: How to create a Table
You can use the following markdown format to create the tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| cloud | `:cloud:` | :cloud: |
| --- | --- | --- |
| cloud with lightning | `:cloud_with_lightning` | 🌩️ |
```
Github extends the functionality of markdown tables to provide more alignment and table cell formating options. [<sup>[2]</sup>](#external-references)
![pipechar](asserts/pipechar.JPG)


## External References
- [GitHub Flavored Markdown Spec](//github.github.com/gfm/)   
- [Basic writing and formatting syntax(Github Flavored markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) [<sup>[1]</sup>](#external-references)
- [GFM Emojis](https://github.com/markdown-templates/markdown-emojis)
- [GFM Tables(With Extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
