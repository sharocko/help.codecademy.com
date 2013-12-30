---
title: How do I install Python on my computer?
article_id: '1399161'
---
There are two versions of Python available. Please follow the instructions based on the version of Python you want. Codecademy uses Python 2.7.x.

### Windows
Python 2 or 3:
  1. Go to the [Python download page][1]
  2. Download the Python 2/3 windows installer based on your system (32 or 64 bit)
  3. Run the setup and follow all on screen instructions

For more information: [http://docs.python-guide.org/en/latest/starting/install/win/][3]

### Mac OSX (Apple)
**Note:** OSX comes with a version of Python 2 installed. It is recommended that you upgrade your version using one of the methods mentioned below.

Python 2 or 3 via installer:
  1. Go to the [Python download page][1]
  2. Download the Python 2/3 Mac OSX installer based on your system (32 or 64 bit)
  3. Run the setup and follow all on screen instructions

Python 2 via [Homebrew][2] (recommended):

```
>> brew update
>> brew install python
``` 

Python 3 via [Homebrew][2]:

```
>> brew update
>> brew install python3
```

For more information: [http://docs.python-guide.org/en/latest/starting/install/osx/][4]

### Ubuntu (Linux Debian)
Python 2 or 3 via installer:
  1. Go to the [Python download page][1]
  2. Download the Python 2/3 Linux installer based on your system
  3. Run the setup and follow all on screen instructions

In the terminal (replace x.x.x with the version of Python you want to install):

```
>> sudo apt-get install build-essential
>> sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev
>> cd ~/Downloads/
>> wget http://python.org/ftp/python/x.x.x/Python-x.x.x.tgz
>> tar -xvf Python-x.x.x.tgz
>> cd Python-x.x.x
>> ./configure
>> make
```

If you want this version of Python as the non-default version:

```
>> sudo make altinstall
```

If you want this version of Python as the default version:

```
>> sudo make install
```

For more information: [http://docs.python-guide.org/en/latest/starting/install/linux/][5]


  [1]: http://www.python.org/getit/
  [2]: http://brew.sh
  [3]: http://docs.python-guide.org/en/latest/starting/install/win/
  [4]: http://docs.python-guide.org/en/latest/starting/install/osx/
  [5]: http://docs.python-guide.org/en/latest/starting/install/linux/