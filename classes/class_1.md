## class DepartingFlight

### Attributes:
   * `gate` (integer)
   * `destination` (string)
   * `passenger_list` (hash)
   * `on_time` (boolean)

### Methods:
   * `change_gate(new_gate)` (updates `gate` to match the new_gate argument passed into the method)
   * `reroute(new_destination)` (updates `destination` to match the argument passed into the method)
   * `add_passenger(seat, name)` (updates `passenger_list` to add a key/value pair with the seat and name passed into the method)
   * `delay` (updates `on_time` to `false`)
