# github-csv-tools
Tools for importing GitHub Issues via CSV.

Currently imports title, description, and labels.

Publish in the sake of sharing but you should use xml export in jira or use the apis
This is a fork of https://github.com/gavinr/github-csv-tools

**Be careful it's impossible to delete github issues**

there is example file JIRA.csv in `/test`

## Usage

 1. `git clone this repo`
 2. `cd into it`
 3. `npm install`
 4. `chmod +x index.js`
 5. `./index.js myFile.csv`

## Thanks

- [github package](https://www.npmjs.com/package/github)
- [nodeCSV](https://www.npmjs.com/package/csv)
- [commander](https://www.npmjs.com/package/commander)
- [co](https://www.npmjs.com/package/co)
- [Tim Patterson's Post on Atlassian.com](https://developer.atlassian.com/blog/2015/11/scripting-with-node/)
