# Dependable
A set of bash scripts used for getting an overview of your dependencies.


## Execution

1. Store create a config file
2. Install
    1. jq
    2. xmlstarlet
4. Run `$ ./dependable`, it will execute the following scripts:
    1. Download all Java repositories
    2. Extract all dependencies
    3. Rearrange the data so it's grouped by dependencies

