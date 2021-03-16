# hid-example

An example hid repo

## Setup Git

YOU MUST NOT FORGET THIS ON ALL MACHINES THAT YOU COMMIT FROM OR YOU WILL NOT GET CREDIT

```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
$ git config --global core.editor emacs
```

Replace your name and chose an editor of your choice. It is up to you which one you chose. emacs is one of the bets once but you should look at our cheat sheats, alternatives are vi, vim, nano, pico and more.
Even if you use pycharm or VSCode we recommend that you also have the option to check in from the commandline


## Clone

```
# git clone https://github.com/cybertraining-dsc/hid-example.git
```

Replace the hid-example with your hid number

## commit

```
$ git commit -a
```

## Github Worst Practice and Tip

One of the worst tips that we have seen from teachers, students and on the internet is to use the 

```
git add .
```

E.g. git add all what you have in the current directory. This may introduce VERY NASTY SIDEFFECTS in case you are not careful. Lets assume you have some secret file or data in the dire, you used it and committed. There are people actively mining GitHub for such mistakes. Instead use for each file a separate git add, so you can make sure you want to add it.

```
git add filename1.py
git add filename2.py
....
```

you can also use the interactive 

```
git commit -a
```

If you see something that should not be committed exit the editor without saving.
