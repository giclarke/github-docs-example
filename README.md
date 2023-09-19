# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for technical people to **copy, paste and share** code.
A good Cloud Engineer uses Codeblocks whenever possible.

This allows others to copy and paste their code in order  to replicate or research issues.


- In order to create codeblocks in markdown, you need to use three bacticts (`)
- Not to be confused with the quotation mark (')

```
# Define a recursive function to calculate the factorial of a number
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Get user input for the number
number = int(input("Enter a number: "))

# Calculate and display the factorial
if number < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(number)
    print(f"The factorial of {number} is {result}.")
```

- When you can, you should attempt to apply syntax highlighting to your codeblocks

```python
# Define a recursive function to calculate the factorial of a number
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Get user input for the number
number = int(input("Enter a number: "))

# Calculate and display the factorial
if number < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(number)
    print(f"The factorial of {number} is {result}.")

```
- Make note of where the backtick keyboard key is located.
- It usually appears above the Tab key, but it may vary based on your keyboard type.

<img width="200px" src="assets/Backtick-Image.gif" />


Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  File "example.py", line 2, in <module>
    print(undefined_variable)
NameError: name 'undefined_variable' is not defined
```

> Here is an example of using a codeblock for an erroe that occurred in bash.

## Step 2 - How to take screen shots

A screen shot is when you capture a part of your screen from your laptop, desktop or phone.

This is not to be confusted with taking a photo with your phone.

![A photo with your phone](assets/Phone-Photo.gif)


## Step 3 - Use GitHub Flavored Markdown Task Lists

GitHub extends Markdown to have a list where you can check off items.<sup>[1]</sup>

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| -------- | ------- | ------- |
| Cloud | `:cloud:` | :cloud: | 
| Smiling Face | `:smile:` | :smile: |
| Thumbs Up | `:thumbsup:` | :thumbsup: |

## Step 5 - How To Create A Table

You can use the following markdown format to create tables:

```markdown
| Name | Shortcode | Emoji |
| -------- | ------- | ------- |
| Cloud | `:cloud:` | :cloud: | 
| Smiling Face | `:smile:` | :smile: |
| Thumbs Up | `:thumbsup:` | :thumbsup: |

```
GitHub extends the functionality of Markdown tables to provide more aligment and table cell formatting options. [<sup>[2]</sup>](#references)

- Make note of where the pipe keyboard key is located.
- It usually appears above the return or enter key, but it may vary based on your keyboard type.
  
![Photo of the pipe character on our keyboard](assets/Pipe-Image.gif)


## References
[GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 

[Basic Writing & Formatting Syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)

[GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>

[GFM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)

[GFM - Tables (with extentions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
