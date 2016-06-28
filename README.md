[a]: https://github.com/stylemistake/bash-task-runner
[b]: https://github.com/kswedberg/jquery-tmbundle

# Bash Task Runner Bundle for TextMate #

This is a rudimentary bundle for using [Bash Task Runner][a] within TextMate. When you have a project open in TextMate that has `runnerfile.sh` in its root it allows you to run the its default task or select from a list of available tasks and run that. These commands are available from the `Bundles -> Bash Task Runner` menu or by simply pressing `^⇧R`.

## Installation <sup id="a1">[1](#f1)</sup> ##

Because this bundle runs Bash Task Runner it has the same dependencies as it does:

* bash `>=4.0`
* coreutils `>=8.0`

You may install both by typing this command into the terminal:

```bash
brew install bash coreutils
```

The quickest way to install this bundle is via the command line. If you have Git installed, you'll probably want to install with Git. With or without, you can simply copy and paste each line one by one into the Terminal instructions:

### Install with Git ###

```bash
mkdir -p "~/Library/Application Support/TextMate/Bundles"
cd "~/Library/Application Support/TextMate/Bundles"
git clone git://github.com/dustinwilson/bash-task-runner.tmbundle.git "Bash Task Runner.tmbundle"
osascript -e 'tell app "TextMate" to reload bundles'
```

### Install without Git ###

```bash
mkdir -p "~/Library/Application Support/TextMate/Bundles"
cd "~/Library/Application Support/TextMate/Bundles"
wget http://github.com/dustinwilson/bash-task-runner.tmbundle/tarball/master
tar zxf dustinwilson-bash-task-runner.tmbundle*.tar.gz
rm dustinwilson-bash-task-runner.tmbundle*.tar.gz
mv dustinwilson-bash-task-runner.tmbundle* "Bash Task Runner.tmbundle"
osascript -e 'tell app "TextMate" to reload bundles'
```

## Download ##

If you would like to avoid the command line altogether, you may download the bundle and install it:

1. Download the zip from http://github.com/dustinwilson/bash-task-runner.tmbundle/zipball/master
2. Find the zip file on your local machine (usually in your Downloads folder) and double-click to unzip it.
3. Change the filename from _dustinwilson-bash-task-runner.tmbundle-really\_long\_alpha\_numeric\_sequence_ to _Bash Task Runner.tmbundle_.
4. Double-click the _Bash Task Runner.tmbundle_ file.
5. TextMate will prompt you asking if you want to install it. Click _Yes_.

## Instructions ##

This bundle will only work if you are working within a project folder and Bash Task Runner is installed via `npm` in your project folder.

## License ##

```
Permission to copy, use, modify, sell and distribute this
software is granted. This software is provided "as is" without
express or implied warranty, and with no claim as to its
suitability for any purpose.
```

***

<ul>
 <li id="f1">Installation and download instructions largely lifted from <a href="https://github.com/kswedberg/jquery-tmbundle">https://github.com/kswedberg/jquery-tmbundle</a>. <a href="#a1">&#8617;&#xFE0E;</a></li>
</ul>
