# Drupal 8 training website.

Drupal 8 training website built on Lando.

## Dependencies
* Docker
* Lando
* Composer

## Installation

```bash
composer composer install
```

## Usage

```bash
lando start
```

### Import database
```bash
lando db-import
```

### Export database
```bash
lando db-export
```

### Import configuration
```bash
lando drush cim
```

### Export configuration
```bash
lando drush cex
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)