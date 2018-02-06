# uniprint

A shell script to print on the IRB printers of the TU Dortmund

# Installation

Make sure, that `${HOME}/.local/bin/` exists and is part of your `$PATH`. First
download the script,

    git clone https://github.com/christofsteel/uniprint && cd uniprint

then deploy it,

    cp uniprint ${HOME}/.local/bin/

lastly copy the configfile to your home directory. Remember to add edit it according to your needs.

    cp uniprintrc.sample ${HOME}/.uniprintrc
    vim ${HOME}/.uniprintrc

# Usage

    uniprint [-U user] [-H host] [-P printer] [-\# count] [-N pages_on_paper] [-O orientation] [-K duplex] [-r range] File
    uniprint -h
