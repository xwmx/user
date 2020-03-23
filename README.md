```
'##::::'##::'######::'########:'########::
 ##:::: ##:'##... ##: ##.....:: ##.... ##:
 ##:::: ##: ##:::..:: ##::::::: ##:::: ##:
 ##:::: ##:. ######:: ######::: ########::
 ##:::: ##::..... ##: ##...:::: ##.. ##:::
 ##:::: ##:'##::: ##: ##::::::: ##::. ##::
. #######::. ######:: ########: ##:::. ##:
:.......::::......:::........::..:::::..::
```

# user cli

`user` is a command line interface for common macOS user account operations,
like fast user switching, listing users, and displaying the user login window.

## Installation

### Homebrew

To install with [Homebrew](http://brew.sh/):

```bash
brew install xwmx/taps/user
```

### npm

To install with [npm](https://www.npmjs.com/package/user-cli):

```bash
npm install --global user-cli
```

### bpkg

To install with [bpkg](http://www.bpkg.io/):

```bash
bpkg install xwmx/user
```

### Manual

To install manually, simply add the `user` script to your `$PATH`. If
you already have a `~/bin` directory, you can use the following command:

```bash
curl -L https://raw.github.com/xwmx/user/master/user \
  -o ~/bin/user && chmod +x ~/bin/user
```

## Usage

```
Usage:
  user list
  user login <username>
  user logout [--force]
  user window
  user -h | --help
  user --version

Subcommands:
  list    List login user user.
  login   Log in as the specified user, aka "Fast User Switching."
  logout  Log out the current user.
  window  Go to the login window without logging out.

Options:
  -h --help  Display this help information.
  --version  Display version information.
  --force    Suppress confirmation prompt.
```
