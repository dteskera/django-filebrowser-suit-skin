# Use django-filebrowser within django-suit

## About
This package overrides django-filebrowser tamplates and some js files to enable usage of filebrowser within django-suit admin.

Javascript file thats been replaced enables usage of filbrowser within TinyMCE 4 as is (without the need of including other javascript files).

## Installation
pip install -e git+git://github.com/dteskera/django-filebrowser-suit-skin.git#egg=django-filebrowser-suit-skin


## Configuration
Add app filebrowser-suit before app filebrowser in your INSTALLED_APPS list

    INSTALLED_APPS = [  
        ...  
        'filebrowser-suit',  
        'filebrowser',  
        'suit',  
        ...  ,  
    ]
