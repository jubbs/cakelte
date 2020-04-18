# CakeLTE Plugin: AdminLTE plugin for CakePHP

## Installation

You can install this plugin into your CakePHP application using [composer](https://getcomposer.org).

The recommended way to install composer packages is:
```
composer require arodu/cake-lte
```
## Usage

setLayout into AppController.php
```php
  $this->viewBuilder()
    ->setClassName('CakeLTE.CakeLTE')
    ->setLayout('CakeLTE.starter');
```

Create code from bake
```bash
bin/cake bake all --theme CakeLTE Model
```

## Credits
AdminLTE Bootstrap Admin Dashboard Template [https://adminlte.io/](https://adminlte.io/)
