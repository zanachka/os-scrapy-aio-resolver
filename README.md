# os_scrapy_aio_resolver

Scrapy project auto generated by [os-scrapy-cookiecutter](https://github.com/cfhamlet/os-scrapy-cookiecutter). 


## Project

This scrapy project is a python package generated by os-scrapy-cookiecutter.

You can run it as normal scrapy project with scrapy commands.

It is also a python package, the scaffolds can be used for formatting, testing, installing.

* lint
  
    ```
    sh scripts/lint.sh
    ```

* test

    ```
    sh scripts/test.sh
    ```

* install

    ```
    python setup.py install
    ```

* example

    You can run example spider:

    ```
    scrapy crawl example
    ```

* files

    ```
    .
    ├── os_scrapy_aio_resolver # scrapy project          
    │   ├── __init__.py
    │   ├── items.py
    │   ├── middlewares.py
    │   ├── pipelines.py
    │   ├── settings.py
    │   └── spiders
    │       └── __init__.py
    ├── LICENSE # license file
    ├── MANIFEST.in # setup install package file
    ├── pytest.ini # pytest config file
    ├── README.md
    ├── requirements
    │   ├── requirements-lint.txt # requirements of format tools used by scripts/lint.sh and tox
    │   ├── requirements-test.txt # requirements of test used by tox
    │   └── requirements.txt # requirements of this project
    ├── scrapy.cfg # scrapy project entrypoint file
    ├── scripts
    │   ├── test.sh # run test 
    │   └── lint.sh # format the source file
    ├── setup.cfg # setup tool config file
    ├── setup.py # setup tool 
    ├── tests
    │   ├── __init__.py
    │   └── test_scrapy_check.py # unit test with scrapy check
    └── tox.ini # tox config file
    ```

## Install

```
python setup.py install
```

## Usage

```
scrapy -h
```

## Unit Tests

```
tox
```

## License

MIT licensed.
=======
# os-scrapy-aio-resolver
