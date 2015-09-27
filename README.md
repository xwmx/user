```
                                                       **
                                                      /**
  ******    *****   *****   ******  **   ** *******  ******  ******
 //////**  **///** **///** **////**/**  /**//**///**///**/  **////
  ******* /**  // /**  // /**   /**/**  /** /**  /**  /**  //*****
 **////** /**   **/**   **/**   /**/**  /** /**  /**  /**   /////**
//********//***** //***** //****** //****** ***  /**  //**  ******
 ////////  /////   /////   //////   ////// ///   //    //  //////
```

# accounts

`accounts` is a command line / terminal tool for common OS X user account
operations, like fast user switching, listing users, and displaying the
login window.

## Installation

### Homebrew

To install with [Homebrew](http://brew.sh/):

    brew tap alphabetum/taps && brew install alphabetum/taps/accounts

### bpkg

To install with [bpkg](http://www.bpkg.io/):

    bpkg install alphabetum/accounts

### Manual

To install manually, simply add the `accounts` script to your `$PATH`. If
you already have a `~/bin` directory, you can use the following command:

    curl -L https://raw.github.com/alphabetum/accounts/master/accounts \
      -o ~/bin/accounts && chmod +x ~/bin/accounts

## Usage

```
Usage:
  accounts list
  accounts login <username>
  accounts window
  accounts -h | --help
  accounts --version

Subcommands:
  list    List login user accounts.
  login   Login as the specified user, aka "Fast User Switching."
  window  Go to the OS X login window.

Options:
  -h --help  Display this help information.
  --version  Display version information.
```
