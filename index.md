# Some help from Leon

## Description
{{ site.description }}

##  LNAV Configuration files for VMware Workspace ONE log files

I've done some work to create log parsers for [lnav](https://lnav.org/) to make it easier to read the VMware Workspace ONE log files.

Follow the directions on the [lnav website](https://lnav.org/) to install lnav on your system.

Once you have lnav installed, you can download the log format files from the [lnav](https://github.com/leonvmw/leonvmw.github.io/tree/main/lnav) directory in this repository.
Then add the log parsers to your lnav configuration directory using the following commands:
```bash
lnav -i -W someLogParser.json
```

If you find that there are VMware Workspace ONE logs which are not parsed correctly, please open an issue here with a sample or two and I'll try to update the log parsers.
