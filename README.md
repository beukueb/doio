# doio
Programming language DO[io]

This is a hobby project of creating a programming language. I avoid saying a 'new programming language', as that really does not matter. Just like it is not important to make a new Linux distro, when you go through all the Linux From Scratch steps, making a programming language does not have to have as an end a new programming language. It is the journey that counts not the destination. Heck, at some level all programming languages are just the same, translating text from one language into something that ends up being assembly code.

It is just fun thinking about how you would organize your language if it was up to you. In this text it is up to me.

## Design

### Name

DO[io]: in the end any programming language is a tool to let the computer 'do' something, with some 'i'nput resulting in some 'o'utput. It would be dangerous calling your language just 'DO' because then google would not know what to 'do' when you ask for 'do documentation', as such to avoid language: DO[io] aka doio.

### Mission and vision

Why 'DO'? A lot of languages try to focus on a core concept. For one language everything might be an object, for other languages everythin is a list including the source code. For this language everything is a function (at least at the language level). And the last line of any function is its value, which could, but does not have to be, another function. What do I want from my language:

- easy, less is more syntax
- international syntax, plug in internationalization for language key-words
- typed variables
- io: in and out json (typed)
- compiled but also interpretable

### hello world example

    world_function
        print hello world
        
    world_function

### The road ahead

Using flex, bison and LLVM to mix this all together. Reading up on programming language design.
