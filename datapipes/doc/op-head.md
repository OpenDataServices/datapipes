## head

Truncate dataset to its first rows.

### Usage

    head [[-n] COUNT]

    COUNT
        Number of rows to truncate to. If this option is
        omitted, it defaults to 10.

Note we allow you to prefix `COUNT` with `-n` to ensure compatability with standard unix `head`.

### Examples

Return the first 10 rows.

[/csv/head/?url=https://raw.githubusercontent.com/datasets/bond-yields-uk-10y/9e921283/data/annual.csv](/csv/head/?url=https://raw.githubusercontent.com/datasets/bond-yields-uk-10y/9e921283/data/annual.csv)

Return the first 20 rows.

[/csv/head 20/?url=https://raw.githubusercontent.com/datasets/bond-yields-uk-10y/9e921283/data/annual.csv](/csv/head%2020/?url=https://raw.githubusercontent.com/datasets/bond-yields-uk-10y/9e921283/data/annual.csv)

