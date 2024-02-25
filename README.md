# trove-parliament-press-releases-covid

A GLAM Workbench dataset

These datasets were generated using notebooks in the [trove-government](https://github.com/GLAM-Workbench/trove-government/) repository.

For more information and documentation see the [Trove government](https://glam-workbench.net/trove-government) section of the [GLAM Workbench](https://glam-workbench.net).

## Dataset summary
- [text](https://github.com/GLAM-Workbench/trove-parliament-press-releases-covid/tree/main/text/) (directory containing 5,520 files)
- [results.csv](https://github.com/GLAM-Workbench/trove-parliament-press-releases-covid/raw/main/results.csv) (5.2 MB, text/csv)


## Dataset details

### [text](https://github.com/GLAM-Workbench/trove-parliament-press-releases-covid/tree/main/text/)

|                 |                                                                                                                                                                                                                                                                     |
|:----------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested  | 2024-02-25                                                                                                                                                                                                                                                          |
| number of files | 5,520                                                                                                                                                                                                                                                               |
| format          | directory                                                                                                                                                                                                                                                           |
| created by      | <a href='https://github.com/GLAM-Workbench/trove-government/blob/master/harvest-parliament-press-releases.ipynb'>Harvest parliament press releases from Trove</a> ([documentation](https://glam-workbench.net/trove-government/harvest-parliament-press-releases/)) |
| query           | `nuc:"APAR:PR" AND (covid OR coronavirus)`                                                                                                                                                                                                                          |



### [results.csv](https://github.com/GLAM-Workbench/trove-parliament-press-releases-covid/raw/main/results.csv)

|                |                                                                                                                                                                                                                                                                     |
|:---------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2024-02-25                                                                                                                                                                                                                                                          |
| file size      | 5.2 MB                                                                                                                                                                                                                                                              |
| format         | text/csv                                                                                                                                                                                                                                                            |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-government/blob/master/harvest-parliament-press-releases.ipynb'>Harvest parliament press releases from Trove</a> ([documentation](https://glam-workbench.net/trove-government/harvest-parliament-press-releases/)) |
| number of rows | 5523                                                                                                                                                                                                                                                                |
| query          | `nuc:"APAR:PR" AND (covid OR coronavirus)`                                                                                                                                                                                                                          |

#### Columns

| name           | type    | description                                                                                        |
|:---------------|:--------|:---------------------------------------------------------------------------------------------------|
| `title`        | string  | title of the press release, interview, or speech                                                   |
| `contributor`  | string  | names of people and organisations contributing to this item; multiple values separated by | symbol |
| `date`         | date    | date when this item was presented or published; ISO format 'YYYY-MM-DD'                            |
| `description`  | string  | usually includes the beginning of the full text content (truncated at approx 200 characters)       |
| `type`         | string  | type of resource, eg 'Press Release' or 'Speech'; multiple values separated by | symbol            |
| `format`       | string  | format of resource, usually either 'Online Text' or empty; multiple values separated by | symbol   |
| `work_type`    | string  | Trove work format, eg 'Article'; multiple values separated by | symbol                             |
| `language`     | string  | language of resource, eg 'eng'; multiple values separated by | symbol                              |
| `extent`       | string  | often includes the number of pages; multiple values separated by | symbol                          |
| `rights`       | string  | information about copyright; multiple values separated by | symbol                                 |
| `subject`      | string  | subject or topic headings; multiple values separated by | symbol                                   |
| `is_part_of`   | string  | collection containing this item; multiple values separated by | symbol                             |
| `fulltext_url` | string  | Link to the full text version in ParlInfo                                                          |
| `trove_url`    | string  | link to the version record in Trove                                                                |
| `work_id`      | integer | Trove work identifier                                                                              |
| `version_id`   | integer | Trove version identifier                                                                           |
| `hash`         | string  | SHA-1 hash value generated from the full text; useful for identifying duplicate texts              |

----
Created by [Tim Sherratt](https://timsherratt.au) for the [GLAM Workbench](https://glam-workbench.net)