# mongoDB_install
Installing and setting up MongoDB

MongoDB is a fantastic, internationally used database system. We will be using it through our second unit.

In our terminal, enter the commands


```
brew install mongodb mongodb-community

```

If linux/ubunto users are getting any permission errors, simply add the Sudo (Super User Do) command before

```

sudo apt brew install mongo mongodb-community

```

When the installation is complete, run the command

```

brew services list

```

This will show you a number of behind-the-scenes programs running on your computer. MongoDB and MongoCommunity should be there with "started" in green.
If you are getting a Red or Yellow message instead, run the command

```
brew serives restart
```

and then run the command list afterwards.
