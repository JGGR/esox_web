# esox_web

## Proof-of-concept of esox_wasm usage

## Table of Contents

+ [What is this thing?](#witt)
+ [Input templates](#input_templates)
+ [Locale](#locale)
+ [Testing](#testing)

## What is this thing? <a name = "witt"></a>

This is a proof-of-concept of `esox_wasm` usage, WASM glue library for calculating the NISECI and/or HFBI index for a dataset.

## Input templates <a name = "input_templates"></a>

You can find templates for the input files in the `templates` folder.

## Testing <a name = "testing"></a>

To test `pkg/.wasm` file, run:
```sh
    python -m http.server
```
This should start a server on `http://0.0.0.0:8000` using the provided `index.hmtl`.
