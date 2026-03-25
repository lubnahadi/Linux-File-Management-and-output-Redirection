# Linux-File-Management-and-output-Redirection

## Project description
Hands on Linux project demonstrating file management and output redirection using Fedora. This project includes creating files , listing them, and redirecting command output and errors.

## Skills used
- Linux command line
- File management
- Output redirection
- Basic troubleshooting

## Step 1 , Created sample files
```bash touch sample1 sample2 sample3```
## Step 2 , Varified files were created
```bash ls```
## Step 3 , Listed specific files
```bash ls sample1 sample2 sample3 > ls.out```
## Step 4 , Redirected output to a file 
```bash ls sample1 sample2 sample3 > ls.out```
## Step 5 , Viewed contents of output file 
```bash cat ls.out```
## Step 6 , Redirected both output and errors
```bash ls sample1 sample2 sample3 > ls.out 2>&1```
## Step 7 , Sent output to /dev/null
```bash ls sample1 sample2 sample3 > /dev/null```
