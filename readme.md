# Arduino - Template Project

## A template project for Arduino and Arduino CLI

### Compile & Upload

Pre-made `sh` commands are available for compiling (`compile.sh`) and uploading (`upload.sh`) the code.  

- Run `chmod +x compile.sh` to make the script executable.
- Run `./compile.sh` to launch the Arduino compiler.
- Run `chmod +x upload.sh` to make the upload script executable.
- Run `./upload.sh` to launch the Arduino uploader.

Before using the commands make sure the configurations are correct.

```bash
#!/bin/bash

# ====
# Global variables
# ====

FQBN=arduino:renesas_uno:unor4wifi  # <-- Enter the desired FQBN, should be something like "arduino:renesas_uno:unor4wifi"
BUILD_PATH=build                    # <-- Enter the desired build directory path, should be somethind like "build"
```
