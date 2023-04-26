# Fixmycode

Fixmycode is a command-line tool that helps to fix syntax errors and bugs in Python code using GPT-3 language model.

## Installation

To use Fixmycode, you first need to install Node.js on your system. To do so, open your terminal and run the following command:

```sh 
sudo apt install nodejs
```

After installing Node.js, you can install the `@johannlai/gptcli` package globally using npm by running the following command

```sh 
npm install -g @johannlai/gptcli
```
After that, clone the `fixmycode` repository from Github by running the following command:

```sh 
git clone https://github.com/mrprohack/Fixmycode
```
Change your working directory to the `fixmycode` directory:

```sh 
cd fixmycode
```
Finally, copy the `fixmycode` file to your `/usr/bin` directory using the following command:
```sh
sudo cp fixmycode /usr/bin/fixmycode
```

Now you're ready to use `fixmycode!`

## Usage

To use Fixmycode, navigate to the directory containing the Python file you want to fix and run the following command:

```sh 
fixmycode [FILENAME]
```
Replace `[FILENAME]` with the name of the Python file you want to fix. The tool will try to fix any syntax errors or bugs in your Python code using GPT-3 language model and provide you with the fixed code.

That's it! You can now use Fixmycode to fix your Python code quickly and easily. If you encounter any issues or have suggestions for improvement, feel free to open an issue on the Github repository.

