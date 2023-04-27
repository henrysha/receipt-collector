# Receipt Collector

for those who need to submit billing receipts to their company for the subscription service,
this Receipt Collector will save your time!

## Prerequisite
- node

## How To

download or clone this repository, or fork as you wish.

create `cypress.env.json` at the root of the directory, and fill the file with your credentials as below

```json
{
  "NETFLIX_ID": <YOUR-NETFLIX-ID>,
  "NETFLIX_PW": <YOUR-NETFLIX-PASSWORD>,
}
```

install dependencies using

```bash
npm install
```

then, run the npm script as you need, or run
`npm run cypress:open` and execute the script on the Cypress GUI

## Supported Services
- Netflix
