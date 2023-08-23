# Recruiting Test

Creation of a simple browser application to display statistical data.

The statistical data should be loaded from the provided web API and displayed in an appealing way (please be creativ, technically and visually). The data sets are from two different Christmas campaigns (`wichtel` and `nussknacker`) from different years `2021` and `2022`. The `session` and `lead` statistics of each campaign must be loaded separately. Also use the provided Flying Spoon logo somewhere.
For the sake of simplicity, authentication is carried out by just using an API key.

Example requests for loading the statistical data and the logo can be found [here (Postman)](https://www.postman.com/flying-spoon/workspace/flying-spoon-recruitment/folder/3249689-d3989e0c-2a6a-460c-b44f-2117770ecd44).

The data is available in the following aggregations:
  - hourly (only for a period of max. 24 hours starting from the start time of the aggregation)
  - daily (default)
  - weekly
  - monthly
  - total

Furthermore, the period can be limited by a start time `from` and end time `to`. The start time is necessary when you requesting the data in a hourly aggregation, otherwise it will always return the first 24 hours of the campaign. All time values are UNIX timestamps.

If you have any questions please don't hesitate and contact me `c.bieber@flyingspoon.de`, software development is teamwork.

By default we are using Angular and Bootstrap, but you are free to choose a different framework and/or librarys.

To access (CORS) the API from your development environment, please tell me `c.bieber@flyingspoon.de` if necessary, your URL under which you are developing the application (with Angular in the standard configuration it is http://localhost:4200 or http://127.0.0.1:4200 - these URLs are already eligible).

Please use this repository for backup and exchange of your work. Also use this file `README.md` to explain the steps to deploy your application.

Host: `playground.flyingspoon.de`

API-Key: `3e395b443af8d0d90daa3500e4bebde5434fb600fbe107f6110eb4d10887347e`
