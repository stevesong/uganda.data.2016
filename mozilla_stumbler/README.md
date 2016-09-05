# Extract from Mozilla Stumbler database


* Stumbler database downloaded on 3 September 2016
* Uganda data extracted using csvkit tools

```bash
csvgrep -c mcc -r "641" cell_towers.csv > uganda_cell_towers.csv
```
