# get-actions-payload-fields

This action reads certain fields from payload and return it to use in next step

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-javascript-action@v1
with:
  who-to-greet: 'Mona the Octocat'
