# OpenEth testConfig Generator


## work in progress

To update the list of fields, run `npm run generate-data`. This will parse the command-line options and configuration fields [from the parity repo](https://github.com/paritytech/parity/blob/master/parity/cli/mod.rs), apply the manual overwrites and extra information of `src/data.extra.json` and save the result into `src/data.compiled.json`, which is the file used by Parity Config Generator.
