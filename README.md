# Fixmycode

Fixmycode is a command-line tool that helps to fix syntax errors and bugs in Python code using GPT-3 language model.

## Install

To use Fixmycode, you first need to install Node.js on your system. To do so, open your terminal and run the following command:

```sh 
sudo apt install nodejs
```
## Usage

After installing Node.js, you can install the @johannlai/gptcli package globally using npm by running the following command

```sh 
npm install -g @johannlai/gptcli
```
To use Fixmycode, first, clone this repository on your local machine using the following command:
Change your working directory to the fixmycode directory:
Then, copy the fixmycode file to your /usr/bin directory using the following command:

```sh
git clone https://github.com/mrprohack/fixmycode
cd fixmycode && cp fixmycode /usr/bin/fixmycode
```
Now you can use fixmycode command to fix your Python code. For example, if you have a Python file named test.py that you want to fix, run the following command:

```sh 
fixmycode test.py
```

The tool will try to fix any syntax errors or bugs in your Python code using GPT-3 language model and provide you with the fixed code.

That's it! You can now use Fixmycode to fix your Python code quickly and easily.
