# Spacer Configuration for StarExec

Place `z3` binary under `bin` folder, zip top level directory (`Spacer4`), upload to StarExec

## Configuration

Current three configurations are provided. They differ in how they manage obligation queue.

Additional configuration should be created for Quic3 and GSpacer.

Currently, all configuration disable all pre-processing (mainly `inline` and
`slice`). These probably should be enabled for CHC-COMP since we do not control the input.


## Contributors
  * Arie Gurfinkel
  * Hari Govind
