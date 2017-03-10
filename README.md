# Use django-filebrowser within django-suit

## About
This package overrides django-filebrowser templates and some js files to enable usage of filebrowser within django-suit admin.

Javascript file thats been replaced enables usage of filbrowser within TinyMCE 4 as is (without the need of including other javascript files).

## Installation
To install the package you can use the master branch like this:

    pip install -e git+git://github.com/dteskera/django-filebrowser-suit-skin.git#egg=django-filebrowser-suit-skin

Or you can used a stable version:

    pip install -e git+git://github.com/dteskera/django-filebrowser-suit-skin.git@v0.1#egg=django-filebrowser-suit-skin

Not available on the pypi at the moment.


## Configuration
Add app filebrowser-suit before app filebrowser in your INSTALLED_APPS list:

    INSTALLED_APPS = [
        ...
        'filebrowser-suit',
        'filebrowser',
        'suit',
        ...  ,
    ]
