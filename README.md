# with-env

Use the `with-env` command and keep all your configuration in `.env` files in the current directory from the start of your project!

## Usage

Create a .env file with some config:

```bash
    cat "CONFIG_VALUE=example" > .env
```

Now when you run:

```bash
    with-env bin/run
```

it is equivalent to running:

```bash
    CONFIG_VALUE=example bin/run
```
## Installation

There are 2 ways of installing the `with-env` command.

### MacOS

```bash
    brew install with-env
```

### Manual

```bash
    git clone git@github.com:thekashifmalik/with-env.git
    cd with-env
    ln -s $PWD/with-env /usr/local/bin/with-env
```

