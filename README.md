# LForm

**LForm** - A remarkably magical form and input maker tool for Laravel.

[![Build Status](https://travis-ci.org/LuissobrinhoInc/LForm.svg?branch=master)](https://travis-ci.org/LuissobrinhoInc/LForm)
[![Maintainability](https://api.codeclimate.com/v1/badges/8c00a046fec32d8b8ac7/maintainability)](https://codeclimate.com/github/LuissobrinhoInc/LForm/maintainability)
[![Packagist](https://img.shields.io/packagist/dt/luissobrinho/formmaker.svg)](https://packagist.org/packages/luissobrinho/formmaker)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://packagist.org/packages/luissobrinho/formmaker)

The LForm package provides a set of tools for generating HTML forms with as little as 1 line of code. Don't want to write boring HTML, neither do we. The LForm will generate error containers, all fields defined by either the table or object column types, or if you prefer to have more control define a config. In the case that you want to write more than 1 line of code, LForm comes with the InputMaker service as well. With the InputMaker you can create any form of input, including html for Eloquent relationships.

##### Author(s):
* [Luis Eduardo Altino](https://github.com/luissobrinho) ([ads.luis.sobrinho@gmail.com](mailto:ads.luis.sobrinho@gmail.com))

## Requirements

1. PHP 7+
2. OpenSSL

## Compatability and Support

| Laravel Version | Package Tag | Supported |
|-----------------|-------------|-----------|
| 5.4.x - 7.x | 1.3.x | yes |

### Installation

Start a new Laravel project:
```php
composer create-project laravel/laravel your-project-name
```

Then run the following to add LForm
```php
composer require "luissobrinho/formmaker"
```

Time to publish those assets!
```php
php artisan vendor:publish --provider="Luissobrinho\LForm\LFormProvider"
```

## License
LForm is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

### Bug Reporting and Feature Requests
Please add as many details as possible regarding submission of issues and feature requests

### Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
