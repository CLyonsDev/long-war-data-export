# Long War data export

This repository has the data export of The Long War Index, https://longwarindex.app/. The data export is a set of JSON files. The files hold the game data of the rules.

The Data Export page of the website has the same files in one zip archive: https://longwarindex.app/data_export/

## Updates

When the website gets new data, this repository gets the same files in a new commit. The commit history shows the changes between two versions of the data.

## Contents

The folder `data/v5/` holds version 5 of the export format. Each subfolder holds one type of data. The file `schema.json` in each subfolder gives the structure of the other files in that subfolder.

The file `data/v5/factions/index.json` lists the factions and the data files of each faction. Each path in this file starts at the root of this repository.

## Use in a program

To read one file, use its raw URL. Example:

https://raw.githubusercontent.com/CLyonsDev/long-war-data-export/main/data/v5/factions/index.json

## Licence

The data has the CC0 1.0 licence. Read the file `LICENSE`. You can use the data for all purposes. An attribution to The Long War Index is welcome, but it is not necessary.
