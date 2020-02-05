# GDS TechOps Radar

https://radar.cloudapps.digital

| data | radar | description |
|------|-------|-------------|
| [gds-radar.csv](https://gist.githubusercontent.com/pauldougan/4514cda8655be3ad26d5b8cf511920cf/raw/bdd0d7cd6ac554ba19a64efbd67b12c11986c2cd/gds-radar.csv) | radar | an example based on a sample to show how the radar works |


The application is hosted on [GOV.UK PaaS](https://cloud.london.service.gov.uk) using the Cloud Foundry Docker support.

```
cf login --sso 
cf t -o gds-techarchs -s sandbox 
cf push radar
```
