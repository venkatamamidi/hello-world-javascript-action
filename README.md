# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## `hex-color-code-for-name`

**Optional** The HEX code color for the name when greeting. Default `"C0FFEE"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: venkatamamidi/hello-world-javascript-action@v1.11
with:
  who-to-greet: 'Simba the Octocat'