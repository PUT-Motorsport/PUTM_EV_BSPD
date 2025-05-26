# Tested Cases:

Pulse (2 seconds) of trigger state on all inputs individually, while the rest of inputs was in a trigger state

Pulse on 2 inputs of trigger state, while the 3rd was in static trigger state

Synchronous pulse of trigger state on all inputs

Asynchronous rise to trigger state on all inputs (in all combinations of order), with synchronous fall to "neutral" state

Static trigger state on all inputs together

Static trigger on 1 input, while the rest was in neutral state

Static trigger on two inputs while the last was in neutral state

DC Sweep of all inputs individually, while the rest was in trigger state

DC Sweep -||-, while the rest was in neutral state

<500ms pulse on all inputs individually, while the rest was in trigger state

<500ms pulse on two inputs while the last was in neutral state

## All cases above work as intended. (On my machine atleast)
