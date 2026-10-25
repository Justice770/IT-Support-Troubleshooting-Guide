Practical Lab 2: Network Connectivity Testing

1. Objective

Investigate basic network connectivity on a Windows 10 computer using Command Prompt and the ping utility.

2. Environment

- Operating system: Windows 10
- Tools: Command Prompt, ipconfig, ping
- Test type: Basic network connectivity investigation

3. IP Configuration

- IPv4 address: Confirmed assigned
- Default gateway: Present

The exact IP configuration values were not included in this report.

4. Tests Performed

Test 1: Local TCP/IP Stack

Command:
"ping 127.0.0.1"

Result: Successful.

Interpretation: The local TCP/IP networking stack responded to the loopback test.

Test 2: Default Gateway

Command:
"ping <default-gateway-address>"

Result: Successful.

Interpretation: The computer could communicate with its configured default gateway.

Test 3: Public IP Connectivity

Command:
"ping 1.1.1.1"

Result: Successful.

Interpretation: The computer could reach the tested public IP address using ICMP ping at the time of testing.

5. Overall Findings

All three ping tests were successful. An IPv4 address was assigned, and a default gateway was present.

The results indicate that basic local and external IP connectivity was working during this test.

6. Troubleshooting Actions

No configuration changes were necessary because all three tests succeeded.

7. Skills Practised

- Windows Command Prompt
- Basic IP configuration inspection
- IPv4 addressing concepts
- Default gateway identification
- Ping testing
- Interpreting network connectivity results
- Technical documentation

8. Next Steps

In a future exercise, investigate DNS resolution, compare IP connectivity with website access, and learn how to interpret common network errors.
