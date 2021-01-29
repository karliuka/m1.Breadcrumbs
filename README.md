# Magento Breadcrumbs

Add breadcrumbs to any page.

## Compatibility

Magento CE(EE) 1.6.x, 1.7.x, 1.8.x, 1.9.x

OpenMage LTS 19.4.x

[Breadcrumbs from Magento2](https://github.com/karliuka/m2.Breadcrumbs)

#### Install via Composer

1. Go to installation folder

2. Enter following commands to install module:

    ```bash
    composer require faonni/magento-breadcrumbs
    ```
   Wait while dependencies are updated.

#### Manual Installation

1. Download the corresponding [latest version](https://github.com/karliuka/m1.Breadcrumbs/archive/1.2.0.zip)

2. Copy the unzip content to the {Magento root} folder

## Usage

### Configuration

*The module does not need configuration *.

### Frontend

<img alt="Magento Breadcrumbs" src="https://karliuka.github.io/m1/breadcrumbs/login.png" style="width:100%"/>

## Uninstall

Pleace, create backup so you can recover the data at a later time.



#### Uninstall via Composer

1. Go to installation folder

2. Enter following commands to remove:

    ```bash
    composer remove faonni/magento-breadcrumbs
    ```
#### Manual Uninstall

1. Remove the folder {Magento root}/app/code/community/Faonni/Breadcrumbs
2. Remove the folder {Magento root}/app/design/frontend/base/default/template/faonni/breadcrumbs
3. Remove the file {Magento root}/app/design/frontend/base/default/layout/faonni/breadcrumbs.xml
4. Remove the file {Magento root}/app/etc/modules/Faonni_Breadcrumbs.xml
