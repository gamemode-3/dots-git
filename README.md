## hey, i'm dot!
### vinegar
currently working on vinegar, a wrapper language for rust.
as of today, there is a prototype interpreter that works for at least some simple scripts and lets you integrate functions and structs from rust.
in the future, there might be a full-on translator to translate the entire file to rust before compiling it with cargo. if that happens, there will be good rust-analyzer integration as well.

the purpose of this is to allow simple tasks and ones that ultimately structure an application to be done in a simple, python-like language while preserving all of rust's benefits. all performance intensive backend work should still be done in rust, at the very least with the current, interpreted version. additionally, it's a great way for me to get familiar with rust programming and parsing text.

## past projects
### thelittlethings
a really useful collection of "utils" that i needed for my projects all the time, so i bundled them up!
my personal favourite are the linked values, although they are unfortunately abismally slow.

### human programming language
a language that reads like natural language. 
i find it really enjoyable to play around with the console version, seeing it understand "three" and then "add seven" and then "print out the result". 
