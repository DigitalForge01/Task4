# Task4
# Firewall Configuration Task

## Overview
How to configure firewall rules to block a specific port (e.g., Telnet port 23), test connectivity and then restore the original state, using **Windows GUI** method.

## Prerequisites
- **Windows**: Administrator privileges.

##  Windows (GUI - Windows Defender Firewall with Advanced Security)

1. Open firewall management:
   - Press **Win + R**, type `firewall.cpl`, press **Enter**, then click **Advanced settings**.
2. In the left pane, click **Inbound Rules**.
3. Click **New Rule…** in the right **Actions** pane.
4. Select **Port**, click **Next**.
5. Choose **TCP**, enter port **23**, click **Next**.
6. Select **Block the connection**, click **Next**.
7. Choose applicable profiles (Domain, Private, Public), click **Next**.
8. Name the rule (e.g., **Block Telnet**) and optionally add a description, then click **Finish**.
9. To disable or remove a rule: right-click on the rule → choose **Disable Rule** or **Delete**.
