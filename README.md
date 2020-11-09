# Openethereum Config Generator

[![Build Status](https://travis-ci.org/dev-nodes/openethereum-config-generator.svg?branch=master)](https://travis-ci.org/dev-nodes/openethereum-config-generator)

See demo at: [Openethereum Config Generator](https://dev-nodes.github.io/openethereum-config-generator)

## Development

To update the list of fields, run `npm run generate-data`. This will parse the command-line options and configuration fields [from the openethereum repo](https://github.com/openethereum/openethereum/blob/master/parity/cli/mod.rs), apply the manual overwrites and extra information of `src/data.extra.json` and save the result into `src/data.compiled.json`, which is the file used by Openethereum Config Generator.
