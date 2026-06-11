# System Code Base

## About Module

Foundation module for the SystemCode Magento 2 suite. Registers the shared **System Code** tab in the admin configuration and provides the common dependency used by all other extensions in this package.

Install this module first. It does not add storefront features on its own.

### How to install

#### ✓ Install by Composer (recommended)
```
composer require systemcode/base
php bin/magento module:enable SystemCode_Base
php bin/magento setup:upgrade
```

#### ✓ Install Manually
- Copy module to folder `app/code/SystemCode/Base` and run commands:
```
php bin/magento module:enable SystemCode_Base
php bin/magento setup:di:compile
php bin/magento setup:upgrade
```

### License
OSL-3.0

### Authors
* [Eduardo Diogo Dias](https://github.com/eduardoddias)


---


## Sobre o Módulo

Módulo base da suíte SystemCode para Magento 2. Registra a aba compartilhada **System Code** na configuração do admin e fornece a dependência comum usada por todas as outras extensões deste pacote.

Instale este módulo primeiro. Ele não adiciona funcionalidades na loja por si só.

### Como Instalar

#### ✓ Instalação via Composer (recomendado)
```
composer require systemcode/base
php bin/magento module:enable SystemCode_Base
php bin/magento setup:upgrade
```

#### ✓ Instalação Manual
- Copie o módulo para `app/code/SystemCode/Base` e execute:
```
php bin/magento module:enable SystemCode_Base
php bin/magento setup:di:compile
php bin/magento setup:upgrade
```

### Licença
OSL-3.0

### Autores
* [Eduardo Diogo Dias](https://github.com/eduardoddias)
