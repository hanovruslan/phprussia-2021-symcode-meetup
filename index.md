---

layout: yandex2

style: |
    /* собственные стили можно писать здесь!! */
    .pre-small pre code { font-size: 24px!important; line-height: 48px!important; }
    .pre-big pre code { font-size: 54px !important; line-height: 108px !important; } #  9 lines x 52 symbols
    .big-list { font-size: 80px!important; line-height: 160px!important; }
    .images-w { background-color: #fff !important; }
    .images-wide { width: 100%; }
    .red { border-left: 9px solid #f00 !important; }
    figure.short { width: 480px !important; }
    .text-center { text-align: center !important; }
    img.center { margin: auto !important; }
    img.logo_center { display: block !important; margin-left: auto !important; margin-right: auto !important; width: 61% !important; }
    section.section-white { background-color: #fff !important; }
---

# ![](pictures/symcode-logo.svg){:.logo_center}

## {{ site.presentation.title }}
{:.title}

## Для чего нужно ##

1. Минимизация издержек на публикацию

## Терминология

**Артефакт** - Ровно один файл с приложением + метаданные

* метаданными могут быть как переменные окружения так и информация о версии и других параметры, которые важны для использования этого артефакта

## PHAR

* как устроено
* кто использует
* что есть готовое

## как устроено ##

* Stream Wrapper
* Манифест
* Содержимое архива

## кто использует ##

* composer
* phpunit
* php-cs-fix
* psalm
* deployer
* phpDocumentor
* и другие --> https://phar.io

## Что есть готовое ##

**https://github.com/MacFJA/PharBuilder#similar-projects**

**https://github.com/box-project/box2**

## PHAR: общий сценарий

1. Установить зависимости
1. Прогреть кэш
1. Собрать Артефакт
1. Опубликовать артефакт

## Docker

1. Внутри собираемого образа
1. Использовать базовый образ
1. Монтирование в контейнер

## CI\CD

1. Проверка цельности артефакта
1. Проверка окружения запуска
1. Проверка полноты метаданных

## Пример проекта (humbug/box)

https://github.com/hanovruslan/phar-demo

## Контакты
{:.contacts}

<figure markdown="1">

</figure>
<!-- разделитель контактов -->
-------

<!-- left -->
- {{ site.author.company.name }}
- {:.telegram}symcode
- {:.telegram}symcode_live

<!-- right -->
- {{ site.author.name }}
- {:.telegram}hanovruslan
- {:.mail}hanov.ruslan@gmail.com
- {:.github}hanovruslan
