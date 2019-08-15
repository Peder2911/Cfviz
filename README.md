# Compose Cfviz

A convenience-repo that can be used to oneline-setup a server for showing
shiny-apps, a postgres database, and a database custodian that keeps the
database updated from a data file directory.

The ./srv directory contains two folders: data and apps.  Shiny apps go in
apps, while .csv and .xlsx file go in data. The data files are pushed to the
Postgres database for use in the apps.
