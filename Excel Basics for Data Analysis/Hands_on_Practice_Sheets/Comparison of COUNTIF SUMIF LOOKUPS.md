| **Function** | **Purpose** | **Syntax** | **Example** | **Comparison** |
|--------------|-------------|------------|-------------|----------------|
| **COUNTIFS** | Counts cells based on multiple criteria | `COUNTIFS(criteria_range1, criteria1, [criteria_range2, criteria2], ...)` | `=COUNTIFS(B2:B6, "North", C2:C6, ">500")` | Handles multiple criteria |
| **COUNTIF**  | Counts cells based on a single criterion | `COUNTIF(criteria_range, criteria)` | `=COUNTIF(B2:B6, "North")` | Handles a single criterion |
| **SUMIFS**   | Sums cells based on multiple criteria | `SUMIFS(sum_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)` | `=SUMIFS(C2:C6, B2:B6, "North", C2:C6, ">500")` | Handles multiple criteria |
| **SUMIF**    | Sums cells based on a single criterion | `SUMIF(criteria_range, criteria, sum_range)` | `=SUMIF(B2:B6, "North", C2:C6)` | Handles a single criterion |
| **XLOOKUP**  | Searches a range and returns a match | `XLOOKUP(lookup_value, lookup_array, return_array, [if_not_found], [match_mode], [search_mode])` | `=XLOOKUP("Cherry", B2:B5, C2:C5)` | Flexible, handles both vertical and horizontal lookups, better error handling |
| **VLOOKUP**  | Searches vertically and returns a match | `VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])` | `=VLOOKUP("Cherry", B2:C5, 2, FALSE)` | Searches vertically, left to right only |
| **HLOOKUP**  | Searches horizontally and returns a match | `HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])` | `=HLOOKUP("Cherry", B1:D2, 2, FALSE)` | Searches horizontally, top to bottom only |
