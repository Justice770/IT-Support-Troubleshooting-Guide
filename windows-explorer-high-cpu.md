Case Study: Investigating High CPU Usage in Windows

1. Objective

Investigate unusually high CPU usage on a Windows computer, identify the process consuming the most CPU, and test a troubleshooting action.

2. Environment

- Operating system: Windows 10
- Installed RAM: 4 GB
- Tool used: Windows Task Manager

3. Problem Observed

During the initial inspection, total CPU usage reached 100%. Windows Explorer was using 76.6% CPU.

Other observed processes included:

- Desktop Window Manager: 8.7% CPU
- Task Manager: 7.8% CPU
- System: 2.2% CPU

Initial memory usage was 61%.

4. Investigation

I opened Task Manager and examined the CPU column to identify which process was consuming the most resources.

Windows Explorer was the largest CPU consumer in the captured observation.

5. Troubleshooting Action

I restarted Windows Explorer through Task Manager.

6. Results After Troubleshooting

- Windows Explorer CPU usage: 0%
- Total CPU usage: 9%
- User-observed performance: The laptop ran faster.

7. Conclusion

After restarting Windows Explorer, CPU usage decreased significantly and the laptop's performance improved.

The troubleshooting action resolved the immediate high-CPU condition observed during this test. The original underlying cause has not been confirmed.

8. Skills Practised

- Windows Task Manager
- Process monitoring
- Basic CPU performance investigation
- Windows Explorer troubleshooting
- Before-and-after result verification
- Technical documentation

9. Evidence

A screenshot of Task Manager was captured during the initial investigation.

10. Further Investigation

If the problem returns, monitor Windows Explorer and investigate recent changes, problematic folders, extensions, or other factors that might cause high CPU usage.
