# Demo
https://github.com/rozehnal/environment-parameters

## Run
``composer run-script build --no-interaction -- --env=prod``

## How to use it in your deploy process

```
    git clone https://github.com/rozehnal/environment-parameters-test
    cd ./environment-parameters-test
    composer update
    composer run-script build --no-interaction -- --env=prod
    
    //integreate content of the build folder into your project
    
    rm -rf ./environment-parameters-test
```
