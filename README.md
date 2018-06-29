# CLI Talk - an introduction to command line interfaces

This repository contains a basic introductary talk about the history and foundations of command line interfaces. You can either read the markdown file (cli-magic.7.ronn), the HTML file or read the manpage.
To open the man page without checking out the repository simply run
```
wget -O - -o /dev/null https://raw.githubusercontent.com/asciijungle/cli-talk/master/cli-magic.7 | man /dev/stdin
```

## compiling

To compile the markdown file to the html and man representation use a tool called ronn. It's a ruby gem and can be installed using the gem tool:
```
gem install --user-install ronn
```

After that simply run `ronn cli-magic.7.ronn`.
