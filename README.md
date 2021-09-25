## fork from [Practicalli Spacemacs (develop) configuration](https://github.com/practicalli/spacemacs.d)
This GitHub repository contains my version of the current configuration to support the [Practicalli Spacemacs book](https://practicalli.github.io/spacemacs).  It contains the layers recommended for use for enhanced Clojure development experience as well as numerous tweaks for general [Spacemacs](https://github.com/syl20bnr/spacemacs/) usage.  

### Requirements: Spacemacs Develop, Emacs 27 

## Recommended Command Line tools
There are several [command line tools that should be installed](https://practicalli.github.io/spacemacs/before-you-start/recommended-command-line-tools.html) to support the use of the Practicalli Spacemacs configuration.

## Using the original configuration directly
Visit GitHub and fork the practicalli/spacemacs.d repository.  A fork is recommended so you can add your own customisations and save them to your own repository.

In a terminal window, use git clone to copy your fork to your computer.

```git clone git@github.com:practicalli/spacemacs.d.git ~/.spacemacs.d```

If you are happy to use my Spacemacs configuration as it is, then remove your `~/.spacemacs` file and start Emacs.

## Use that configuration as an example
Clone this repository and review the configurations I have chosen, not everything may be to your preferred way of working.

The recommended approach is to use a diff tool, such as `ediff` in Emacs, `SPC D f` in Spacemacs, to compare my configuration with your own existing configuration.

## The main configuration file
The file `.spacemacs.d/init.el` is read by Spacemacs if the `.spacemacs` file does not exist.  You can used either file as your main Spacemacs configuration file (but obviously not both at the same time).  In this repository, the `.spacemacs` file is a symbolic link to `.spacemacs/init.el`.

## Getting help
Obviously the best place to start looking for help is the [Practicalli repo](https://github.com/practicalli/spacemacs.d)] or the [Practicalli Book](https://practicalli.github.io/spacemacs).

