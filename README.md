# fake-time-jshell

Opens jshell (java11) with faked current date

Image is using this lib: https://github.com/wolfcw/libfaketime
## How to use
```sh
docker build -t devnevaan/fake-time-jshell .
```
Date you want to be set need to be declared as environment variable FAKETIME:
```sh
docker run -it -e FAKETIME="2021-01-05 10:10:10" devnevaan/fake-time-jshell
```