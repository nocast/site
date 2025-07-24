# Try NoCast
NoCast is an open-source dekstop intelligent search bar that, based on community plugins, can help you launch apps, find files, and
many more things.

## Installation & Setup
Currently, the only way to install `nocast` is building it from source using `rustc` and `cargo`.

Here are a list of commands that, when used in order, install and setup nocast in any OS and enviroment supporting cargo and rust:
```bash
cargo install --git https://github.com/nocast/nocast.git
nocast setup
```
The previous commands to the following:
- Clone/download nocast's source code
- Enter the directory where it's been downloaded
- Compile and install the source code
- Start a setup command that finishes nocast's installation and prepares it's requirements

## Usage
As of the last version, nocast does not create an automatic keyboard shorcut for it. You should be able to create it using your
computer's settings, so you can decide which keybinding opens nocast. You have to set that keybinding to run the command `nocast`.

After configuring it, you can use the keybinding to open the app, type what you need into the search bar, and use the enter key to run
an action.

## Plugins
Plugins can be installed using the command line: 
```bash
nocast install <plugin-name-or-source>
```
and removed with the same method:
```bash
nocast remove <plugin-name>
```

You can list all the installed plugins using `nocast list`.

We are working on a repo to hold all created plugins for ease of search and installation.

## Developing plugins
This topic is worked on in the [original repository](https://github.com/nocast/nocast/blob/master/DEV.md).
