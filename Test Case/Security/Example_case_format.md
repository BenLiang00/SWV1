Power on performance - System Reset on FCP

---
### Summary
```
Entrance Criteria:

The system configuration shall be set at the minimum level of supported configuration with M.2 SATA RAID enabled(latest stepping CPUx2, 1 4800MHz DIMM per socket).?Windows server?P1 OS?shall be used for boot time measurements.
```

### Precoditions
```
```


### Steps

Step | Action | Expected
----- | ------ | ------
1 | Reset system from shell environment by front panel. | System is rebooting.
2 | Check video is displayed in less than 11s, with a simple text message indicating that the system is booting. (Early video feature) | Early video display will come out within 11 seconds.
3 | Boot to Windows OS. | System boots to Windows OS.
4 | Record the boot time(Startting from system reseting on, ending at appearance of OS login screen). | The boot time of FCP is less than 100s.



### Notes


### Source

