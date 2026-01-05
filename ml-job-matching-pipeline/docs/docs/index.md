# Job Market Intelligence System documentation!

## Description

Data Science end-to-end project with EDA analysis on a LinkedIn Job Board set of 100K Postings

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `az storage blob upload-batch -d` to recursively sync files in `data/` up to `azure_dataset/data/`.
* `make sync_data_down` will use `az storage blob upload-batch -d` to recursively sync files from `azure_dataset/data/` to `data/`.


