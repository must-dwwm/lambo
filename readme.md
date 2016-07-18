![Lambo](https://raw.githubusercontent.com/tightenco/lambo/master/lambo.jpg)

Super-powered `laravel new` for Laravel and Valet.


![](https://raw.githubusercontent.com/tightenco/lambo/master/lambo.gif)


## Installation

```bash
composer global require tightenco/lambo
```

## Usage

Make sure `~/.composer/vendor/bin` is in your terminal's path.

```bash
lambo superApplication
```

This will `laravel new superApplication`, change into that directory, make an initial Git commit, and open your web browser to that app.

### Arguments

- `-p` or `--path` to specify where to install the application.

  ```bash
  lambo superApplication -p ~/Sites
  ```

- `-m` or `--message` to set the first commit message.

  ```bash
  lambo superApplication -m "This lambo runs fast!"
  ```

## Requirements

- Mac-only.
- Requires the [Laravel installer](https://laravel.com/docs/installation#installing-laravel) and [Laravel Valet](https://laravel.com/docs/valet) to be globally installed.

## Acknowledgements

Inspired by Taylor Otwell and Adam Wathan's work on Valet.
Name from TJ Miller, inspired by Taylor's love for the lambo.

![](https://i.imgur.com/CrS803Y.gif)
