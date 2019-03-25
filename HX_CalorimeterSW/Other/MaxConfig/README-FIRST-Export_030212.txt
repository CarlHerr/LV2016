The mass flow measurement via frequency 

task HX_Cal2_FeqMdot was not exported, there is some issue with this task that has not been resolved
I tried correcting the conflict by changing the name (hence no r in Freq) but it did not work.

The task works in the program however.

Here are the settings:

COUNTER INPUT-> Frequency

Signal Input Range:
Max: 10k Hz
Min: 2 Hz

Starting Edge: Rising
Measurement Method: 2 Counters (Large Range)
Divisor: 32
Custom Scaling: No Scale (it is scaled in the program)

Input terminal is PFI0