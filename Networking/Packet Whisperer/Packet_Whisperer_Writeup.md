## Packet Whisperer: 75 Points

### Challenge Description: Our blue team intercepted a network capture file. It contains unencrypted HTTP traffic. While skimming through it, analysts believe someone accidentally exposed their login credentials in plain text. Review the PCAP to find the password that the user logged in with.

1. Opened Wireshark
2. Open login.pcap file
3. In filter put in “http contains “login”" in Wireshark
4. Look at information that was returned
5. Opened "HTML form URL Encoded: application/x-www-form-urlencoded"
6. Looked at "Form item" and found flag in password - flag: C1{maybe_TLS_would_be_nice}
