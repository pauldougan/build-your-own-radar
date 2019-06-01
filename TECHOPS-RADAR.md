# GDS TechOps Radar

examples

- [gds-radar.csv](https://gist.github.com/pauldougan/4514cda8655be3ad26d5b8cf511920cf/) [raw](https://gist.githubusercontent.com/pauldougan/4514cda8655be3ad26d5b8cf511920cf/raw/bdd0d7cd6ac554ba19a64efbd67b12c11986c2cd/gds-radar.csv)
- https://radar.cloudapps.digital
- https://radar.cloudapps.digital/?sheetId=https://gist.githubusercontent.com/pauldougan/4514cda8655be3ad26d5b8cf511920cf/raw/bdd0d7cd6ac554ba19a64efbd67b12c11986c2cd/gds-radar.csv

The application is hosted on [GOV.UK PaaS](https://cloud.service.gov.uk) using the Cloud Foundry Docker support

```
cf login -a https://api.cloud.service.gov.uk -sso
cf t -o gds-techarchs -s sandbox  
cf push radar --docker-image wwwthoughtworks/build-your-own-radar
open https://radar.cloudapps.digital
```
