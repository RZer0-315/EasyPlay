# JSONBin Schema & Merge Policy
## Schema
- Document shape …
- Key fields: 
"Users" [
  {
    "id": 
    "name":
    "venues"[
      {"id": , "name"...etc}, {more}
    ]
    "shows"[
      {"id": , "name"...etc}, {more}
    ]
  },
  {more}
]
## Examples
PUT payload (truncated): …
Result (truncated): …
## Merge Policy
- Per-record versioning when domain warrants it