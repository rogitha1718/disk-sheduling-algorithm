# Experiment 13: Disk Scheduling Algorithms

## Aim
To implement and study disk scheduling algorithms (FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK) in C.

## Description
This program evaluates various disk scheduling strategies:
- **FCFS:** Serves requests in arrival order.
- **SSTF:** Serves nearest track first.
- **SCAN:** Elevator algorithm moving end-to-end.
- **C-SCAN:** Circular SCAN moving in one direction only.
- **LOOK:** Reverses direction at the last request instead of disk boundary.
- **C-LOOK:** Circular LOOK returning directly to the lowest request.

## Compilation and Execution
```bash
gcc exp13_disk_scheduling.c -o exp13
./exp13
```

## Sample Input
- Req: `8`
- Tracks: `98 183 37 122 14 124 65 67`
- Head Dir: `53 1`

## Output Image
Refer to `exp13_output.png` for the execution output screenshot.
