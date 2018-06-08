# devbox

This is a long-overdue attempt at starting to capture my mac development setup.
There's not much in here yet, but I hope to progressively capture a little more
over time.

Probably mostly useful to me, but feel free to use/abuse as you see fit - however,
please note that I accept no responsibility for your usage of this code.

## Pre-requisites

On RHEL-flavor linux:

    sudo yum install -y git ansible

On Mac

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    brew install git ansible

## Running the script

    ./devbox requirements

On systems where you'll need a password for sudo (e.g. Mac), get that out of the way before running it:

    sudo -s
    exit

Go!

    ./devbox config
