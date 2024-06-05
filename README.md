# Crash Detector
This is a Linux-based tool that helps continuously detect the PID of the process you want to monitor and check if a crash has occurred.

Using Crash Detector, you can easily determine if a crash has occurred during fuzzing.

## usage
```
syntax: ./pid_detector.sh <process name list>
example: ./pid_detector.sh "bluetooth|bsa_server"
```