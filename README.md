## fork from [Practicalli Spacemacs (develop) configuration](https://github.com/practicalli/spacemacs.d)
This GitHub repository contains my version of the current configuration to support the excellent [Practicalli Spacemacs book](https://practicalli.github.io/spacemacs).  This configuration contains the layers recommended for use for enhanced Clojure development experience as well as numerous tweaks for general [Spacemacs](https://github.com/syl20bnr/spacemacs/) usage. 

So-far my modifications involve simply removing a lot of enhancements that I haven't learned how to use yet. I'm also figuring out how to manage a fork in Github.

### Requirements: Spacemacs Develop, Emacs 27 

## Recommended Command Line tools
There are several [command line tools that should be installed](https://practicalli.github.io/spacemacs/before-you-start/recommended-command-line-tools.html) to support the use of the Practicalli Spacemacs configuration.

## Use the Practicalli configuration as an example
Clone the [Practicalli repository](https://github.com/practicalli/spacemacs.d) and review the configurations the author has chosen, not everything may be to your preferred way of working.

The recommended approach is to use a diff tool, such as `ediff` in Emacs, `SPC D f` in Spacemacs, to compare their configuration with your own existing configuration.

## Creating your own variation
Visit GitHub and fork the [practicalli/spacemacs.d repository](https://github.com/practicalli/spacemacs.d).  A fork is recommended if you want to add your own customisations and save them to your own repository.

After creating the fork, in a terminal window, use git clone to copy your fork to your computer. In my case (Windows) this was:

```git clone https://github.com/<yourname>/spacemacs.d.git ./.spacemacs.d```

If you are happy to use the Practicalli Spacemacs configuration as it is, then remove your `~/.spacemacs` file and start Emacs.

## The main configuration file
The file `.spacemacs.d/init.el` is read by Spacemacs if the `.spacemacs` file does not exist.  You can used either file as your main Spacemacs configuration file (but obviously not both at the same time).  In this repository, the `.spacemacs` file is a symbolic link to `.spacemacs/init.el`.

## Getting help
Obviously the best place to start looking for help is the [Practicalli repo](https://github.com/practicalli/spacemacs.d) or the [Practicalli Book](https://practicalli.github.io/spacemacs).

