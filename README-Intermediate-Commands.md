# Intermediate Bash Commands

This section explores intermediate-level Bash commands and concepts that extend your capabilities on the command line. These commands build upon the basics and enable you to perform more advanced tasks and operations.

## Table of Contents

1. [File and Directory Navigation](#file-and-directory-navigation)
2. [File Content Manipulation](#file-content-manipulation)
3. [Command Pipelines](#command-pipelines)
4. [File Permissions and Ownership](#file-permissions-and-ownership)
5. [Environment Variables](#environment-variables)

## File and Directory Navigation

### `find` (File and Directory Search)

The `find` command is used to search for files and directories within a directory hierarchy based on various criteria.

Example:
```bash
find /path/to/search -type f -name "*.txt"
```

### `tar` (Archive and Compression)

The `tar` command is used to create and manipulate archive files, often used in combination with compression tools like `gzip`.

Example:
```bash
tar -cvzf archive.tar.gz file1 file2
```

## File Content Manipulation

### `grep` (Search Text)

The `grep` command searches text using regular expressions, making it a powerful tool for finding patterns or words in files.

Example:
```bash
grep "pattern" file.txt
```

### `sed` (Stream Editor)

`sed` is a text-processing tool for non-interactive text transformations, such as search and replace across multiple lines.

Example:
```bash
sed 's/old-text/new-text/g' file.txt
```

## Command Pipelines

### Pipes (`|`)

Pipes allow you to chain commands together, taking the output of one command and using it as input for another.

Example:
```bash
ls -l | grep "pattern"
```

### Redirection (`>`, `>>`, `<`)

Bash supports input and output redirection. Use `>` to redirect output to a file, `>>` to append output to a file, and `<` for input redirection.

Example:
```bash
echo "Hello" > output.txt
cat < input.txt
```

## File Permissions and Ownership

### `chmod` (Change File Permissions)

The `chmod` command is used to change file permissions, specifying who can read, write, or execute a file or directory.

Example:
```bash
chmod +x script.sh
```

### `chown` (Change File Owner)

The `chown` command allows you to change the owner of a file or directory.

Example:
```bash
chown newowner:group file.txt
```

## Environment Variables

### `export` (Set Environment Variables)

Bash uses environment variables to store information about the system and user preferences. You can set and access these variables.

Example:
```bash
export MY_VARIABLE="Some Value"
echo $MY_VARIABLE
```

These intermediate Bash commands expand your command-line capabilities and are essential for performing more complex tasks. As you become more proficient with these commands, you'll be better equipped to handle advanced scripting and automation. Feel free to experiment and practice with these commands to enhance your skills.
```
