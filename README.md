# Hello world docket action test

This action prints "HEllo World or "Hello" + the name of a person to greet to the log.

## Inputs

## 'who-to-greet'

**Required** The name of the person to greet.

## Outputs

## 'time'

The time we greeted you.

## Example usage

uses: actions/doctest@v2
with:
  who-to-greet: 'Mona the Octocat'
