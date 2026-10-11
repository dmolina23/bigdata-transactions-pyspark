# Data

| File | Description |
|---|---|
| `bankdataset_sample.csv` | Random sample of 10,000 rows (seed 42) of the transactions file. Same format as the full file: `;` separator, columns `Date;Domain;Location;Value;Transaction_count;Key`. |
| `paises.csv` | 46 countries with `ID;País;Impuestos_Locales;Situación_de_Crisis`. Converted to UTF-8 from the file provided by the course. |
| `bankdataset.csv` | **Not included.** The full file (1,004,480 rows, about 42 MB) was provided by the course and I have not checked its license. To reproduce the results in `results/` exactly, copy it to this folder with that name. The notebook uses it automatically when present. |

Both datasets are synthetic. The locations are Indian cities that the assignment maps to fictional "countries", and the country attributes (local taxes, crisis flag) are invented.
