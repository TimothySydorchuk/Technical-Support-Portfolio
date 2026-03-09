# Case 1 – Internet Connectivity Issue

## Issue Summary
User Cannot Access Internet.

## User Report
User reports that websites are not loading in the browser. The browser displays a "No Internet Connection" message.

## Initial Analysis
Possible causes:

- Network adapter disabled
- Incorrect IP configuration
- DNS misconfiguration
- Gateway not reachable
- VPN interfering with network connection

## Troubleshooting Steps
1. Checked network adapter status in system settings.
2. Verified IP configuration using "ipconfig".
3. Tested connectivity to default gateway using "ping".
4. Tested external connectivity with "ping 8.8.8.8".
5. Checked DNS resolution using "nslookup google.com".
6. Restarted network adapter and cleared DNS cache.

## Resolution
Internet connectivity was restored after restarting the network adapter and flushing the DNS cache.

## Status
Resolved.
