## class SecurityCheckpoint

### Attributes:
   * `name` (string)
   * `total_open_lines` (integer)
   * `pre_check_available` (boolean)
   * `threat_status` (string)
   * `officers` (array)


### Methods:
   * `open_line(officer_name)` (adds 1 to `total_open_lines` and adds the argument passed into the method to the `officers` array)
   * `switch_officer(officer_in, officer_out)` (updates `officers` array to add the first argument passed to the method and remove the second argument passed to the method)
   * `close_pre_check` (updates `pre_check_available` to `false`)
   * `report_threat` (updates `threat_status` to "high")
