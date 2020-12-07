## html

Convert the data to an elegant HTML table (with line numbers!).

<form action="/csv/html/" method="GET" class="form">
  <input type="text" name="url" value="" placeholder="Post your URL here" style="width: 100%" />
  <button type="submit">Go &raquo;</button>
</form>
<br />

### Usage

    html

You can also highlight lines by their line numbers:

    html/?url=...#L10

### Examples

S&P 500 companies:

[/csv/html/?url=https://raw.githubusercontent.com/datasets/s-and-p-companies-financials/c9f83a9c/data/constituents-financials.csv](/csv/html/?url=https://raw.githubusercontent.com/datasets/s-and-p-companies-financials/c9f83a9c/data/constituents-financials.csv)

Highlight a line:

[/csv/html/?url=https://raw.githubusercontent.com/datasets/s-and-p-companies-financials/c9f83a9c/data/constituents-financials.csv#L110](/csv/html/?url=https://raw.githubusercontent.com/datasets/s-and-p-companies-financials/c9f83a9c/data/constituents-financials.csv#L110)

