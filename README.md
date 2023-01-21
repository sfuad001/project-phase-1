# Project-phase-1
Name: <br>
UCR Email: 

## Video Link
```
A short video demonstrating the success of your experiments with some explanation. 
Post the video link of the presentation here.
```
<< Write here >>

## Environment Setup
```
Install and set up the environment. Once done, take a screen snapshot of a successful
installation and paste it in the "screenshots" folder (e.g., run “opt -version”). 

Name the screenshot file installation.png/installation.jpg.

Also paste the content of the screenshot here.
```
<< Write here>>
## Experiments
```
Perform some experiments with a small test program you wrote. Name your program file "test.c".
Please add all files used and generated in the "code" folder. 

Try to use different file names so your experiment history would be preserved, instead of being overwritten.
```
### Basic commands
```
Learn and try the basic uses of the following commands: clang,opt,llc,lli,llvm-link,
llvm-as,llvm-dis. Format for one command is given below. Please follow that one to 
answer others.
```
**Tool:** clang <br>
**Input:** test.c <br>
**Output:** test.out <br>
**Command:** clang -o test.out test.c <br>
**Brief Description:** This command compiles a c file and generates the executable.
<br><br>
<< Please follow the format above and write the other commands here. Remove this text. >>
### Translation between code formats
```
Translate between different code formats using some of the above tools with different flags. 
i) source (.c) to binary (executable)
ii) source (.c) to objective (.o)
iii) source (.c) to machine assembly (.s)
iv) source (.c) to LLVM bitcode (.bc)
v) source (.c) to LLVM IR (.ll)
vi) LLVM IR (.ll) to LLVM bitcode (.bc)
vii) LLVM bitcode (.bc) to LLVM IR (.ll)
viii) LLVM IR (.ll) to machine assembly (.s) 
ix) interpret the LLVM IR (which directly prints the output without compilation)
Format to answer is given below:
Input Filename:
Output Filename:
Command:
```
<< Write here >>
### CFG Generation
```
Generate the CFG(s) of test.c (Tip: you may need to install graphviz and use “dot -Tpdf”)
for newer versions of LLVM, you need flag -enable-new-pm=0 for opt command
If you want to write to an output file, use -cfg-dot-filename-prefix  instead of -o

Please name the generated cfg file as "cfg" and add it to the "screenshots" folder.
```


