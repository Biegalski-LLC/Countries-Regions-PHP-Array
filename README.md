# Countries-Regions-PHP-Array
An array of countries and their associated regions (states, provinces, counties, etc..).

Help add to it!

## Associated Data
The primary use for this is to seed databases and have relational data. For example, if you have a `countries` table and a `regions` table. You can seed all of the data from a single file and maintain relationships.

## Format


```
'{CountryAbbreviation}' => [
    'country_name' => '{CountryName}',
    'region_type' => '{State/Provinces/Counties/etc...}',
    'regions' => [
        '{Abbreviation}' => '{Name}'
    ]
]
```
