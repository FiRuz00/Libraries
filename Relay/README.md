# Relay

```
#include "Relay.h"

Relay relay(pinOne, PinTwo);  // If you are going to use only one pin, then put NULL instead of other's number

relay.IsOnOne();  // Returns if first relay (of pair) is on

relay.SetOnOne(); // Sets first  relay to "On" state
relay.SetOffOne();  // Sets first relay to "Off" state
relay.ToggleOne();  // Switches the state of first relay

// If you want to use same functions with second relay, then just change "One" in function name to "Two"
// For example:
relay.SetOffTwo();
```
