# Child Mind State Detection

## Project Overview

The project involves analyzing a dataset with 500 multi-day accelerometer recordings, annotated with sleep onset and wake-up events. The task is to detect these events based on accelerometer data.

### Guidelines for Sleep Detection

- Sleep defined as longest inactivity period while the watch is worn.
- Single sleep period must be at least 30 mins.
- Activity bouts < 30 consecutive mins can interrupt sleep.
- No sleep events unless watch worn.
- Longest sleep window recorded.
- If no valid sleep window, no event recorded.
- One window assigned per night.

### Features in Data

- `anglez` - Z-angle derived from accelerometer components.
- `enmo` - Euclidean Norm Minus One of accelerometer signals.
