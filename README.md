# DreamBerdChat
Attempt at creating a *very* simple SNS (Social Networking Service) with the perfect programming language. Note: I have no idea what I'm doing.

## Setup

This code should theoretically work with any dreamberd interpreter that exists. However, I do recommend the interpreter endorsed by TodePond created by [Vivaan Singhvi](https://github.com/vivaansinghvi07) located here: https://github.com/vivaansinghvi07/dreamberd-interpreter

To install Vivaan's interpreter, simply do the following:

```bash
$ pip install "dreamberd[input]"
```

This project does not use globals as they are a little unwieldy 

## Usage

If you're currently in the root directory, you can do either of the following to run the script:

```bash
$ make
$ dreamberd src/client.db
```

## Funny DreamBerd things

DreamBerd itself does not have a VSCode extension. As such, 

Since comments don't currently work with the interpreter I'm using, they are instead put into a string. The // is just for clarification that it is indeed a comment and for syntax highlighting purposes.

```java
"// Comment"!
```