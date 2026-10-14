# Stopwatch Timing Behavior

Use elapsed-time calculations rather than assuming each interval callback fires exactly on schedule. Pause should record the current elapsed duration; resume should establish a new start reference. Reset should clear both elapsed time and laps. Repeated start actions must not create multiple active timers.