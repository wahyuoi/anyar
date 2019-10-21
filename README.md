## ANYAR


Simple tools to detect file changes on 
[kubernetes/website](https://github.com/kubernetes/website)

### How to run

`./anyar $WEBSITE_REPO`

with `$WEBSITE_REPO` contains absolute path to root directory of 
kubernetes website repository


### Notes!

- currently on POC phase
- lot of hardcoded parameters, e.g. source and destination language, time range to check
- no filter for duplicate entry
- no actionables for each entry