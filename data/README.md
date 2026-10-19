# SMS data

Place the input file here as **`spam.csv`**. Input data is not included in this repository.

The study uses the **SMS Spam Collection** attributed to the UCI Machine Learning Repository in the report. The notebook expects a CSV export with these headers:

| Column | Content |
|:---|:---|
| `v1` | Message label: `ham` or `spam` |
| `v2` | SMS message text |

Other columns are discarded. Text is read with `stringsAsFactors = FALSE` and converted from Latin-1 to UTF-8.

The original UCI distribution is not necessarily supplied in this CSV layout. If using its tab-separated label/message file, convert it to a properly quoted CSV with the headers above before rendering. The original CSV export used to produce the committed PDF is not archived here, so identical source records and encoding must be checked when reproducing its results.
