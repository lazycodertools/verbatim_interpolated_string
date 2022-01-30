# Verbatim Interpolated String Extension For Visual Studio

A tiny extension that turns a string literal into verbatim @"" or interpolated string $"" as you type. 

### **@** is added when: 

* You type single backslash + space
* You type double quotes + space
* Paste a string with backslashes into an empty string

### **@** is not added when: 

* The edited string contains an escaped character, such as '\n'. 

### **$** is added when:

* You type {}_ (consecutive curly braces followed by a space)
* You type {_} (add a space between consecutive curly braces)

## Supported versions

2017, 2019, 2022
