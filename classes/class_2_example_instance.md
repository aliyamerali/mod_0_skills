## class DIA Level 5 North

### Attributes:
   ```ruby
   `name = "Level 5 North"`
   `total_open_lines = 3`
   `pre_check_available = true`
   `threat_status = "low"`
   `officers = ["Ann Perkins", "Ron Swanson", "Leslie Knope"]`
   ```

### Methods:
| Method      | Result      |
|:----------- |:----------- |
| `open_line("Tom Haverford")` | `total_open_lines = 4` and `officers = ["Ann Perkins", "Ron Swanson", "Leslie Knope", "Tom Haverford"]` |
| `switch_officer("Donna Meagle", "Ron Swanson")` | officers = ["Ann Perkins", "Leslie Knope", "Tom Haverford", "Donna Meagle"]` |
| `close_pre_check` | `pre_check_available = false` |
| `report_threat` | `threat_status = "high"` |
