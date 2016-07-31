#cool-retro-term

##Description
cool-retro-term is a terminal emulator which mimics the look and feel of the old cathode tube screens.
It has been designed to be eye-candy, customizable, and reasonably lightweight.

It uses the QML port of qtermwidget (Konsole) developed by me: https://github.com/Swordfish90/qmltermwidget .

This terminal emulator works under Linux and OSX and requires Qt 5.2 or higher.

##Screenshots
![Image](<http://i.imgur.com/I6wq1cC.png>)
![Image](<http://i.imgur.com/12EqlpL.png>)
![Image](<http://i.imgur.com/Lx0acQz.jpg>)

##Get cool-retro-term
You can either build cool-retro-term yourself (see below) or walk the easy way and install one of these packages:

##Build instructions (Linux)

##Dependencies
Make sure to install these first.

---

**Ubuntu 14.04**

    sudo apt-get install build-essential qmlscene qt5-qmake qt5-default qtdeclarative5-dev qtdeclarative5-controls-plugin qtdeclarative5-qtquick2-plugin libqt5qml-graphicaleffects qtdeclarative5-dialogs-plugin qtdeclarative5-localstorage-plugin qtdeclarative5-window-plugin

---

###Compile
Once you installed all dependencies (Qt is installed and in your path) you need to compile and run the application: 

```bash
# Get it from GitHub
git clone --recursive https://github.com/Swordfish90/cool-retro-term.git

# Build it
cd cool-retro-term

# Compile (Fedora and OpenSUSE user should use qmake-qt5 instead of qmake)
qmake && make

# Have fun!
./cool-retro-term
```


##Donations
My friend Filippo Scognamiglio made this project in his spare time because he love what he is doing. If you are enjoying it and you want to buy he a soda click [here](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=flscogna%40gmail%2ecom&lc=IT&item_name=Filippo%20Scognamiglio&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted) .

You can also add "bounties" on your favourite issues. More information on the [Bountysource](https://www.bountysource.com/teams/crt/issues) page.
