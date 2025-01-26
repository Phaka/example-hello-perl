# Hello World in Perl

A minimal "Hello, World!" implementation in Perl. Perl is a high-level, general-purpose programming language that was originally developed for text manipulation. It combines features from shell scripting, C, and other programming languages.

## Installation

### macOS
Perl comes pre-installed, but you can get the latest version with:
```bash
brew install perl
```

### Linux
Perl typically comes pre-installed on most Linux distributions. If needed:

Ubuntu/Debian:
```bash
sudo apt-get update
sudo apt-get install perl
```

Fedora/RHEL:
```bash
sudo dnf install perl
```

### Windows
Download and install Strawberry Perl from [strawberryperl.com](http://strawberryperl.com/).

## Running

Execute the script directly:
```bash
perl main.pl
```

Or make it executable and run:
```bash
chmod +x main.pl
./main.pl
```

## Code Explanation

The program includes `use strict` and `use warnings` pragmas which enable important safety features in Perl. While not strictly necessary for this simple example, they represent good Perl programming practices. The script starts with a shebang line that allows direct execution on Unix-like systems when the file is marked as executable. The `print` function outputs text, and `\n` adds a newline character at the end of the message.
