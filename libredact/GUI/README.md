bca-redtools: GUI master files
------------------------------

# Creating / updating the main window

A full QtCreator project is located in UI/bca-redtools-gui. The only relevant file in this
project is "redactwindow.ui", which is included here for convenient reference. Do not modify
redactwindow.ui by hand! It should only be modified using QtCreator / Qt5.

# Generating RedactWindow.py

The RedactWindow.py file was automatically created from redactwindow.ui using the following command:

* pyuic5 -x mainwindow.ui -o MainWindow.py

# Control code

All control and execution code should be placed in RedactGUI.py. RedactGUI.py can be executed
as follows:

* python3 RedactGUI.py 

# Dependency notes:

All of the necessary tools to create and edit PyQT5 projects can be installed using:

* sudo apt-get install qtcreator pyqt5-dev-tools qt5-default

in Ubuntu 14.04LTS and Ubuntu 16.04LTS.