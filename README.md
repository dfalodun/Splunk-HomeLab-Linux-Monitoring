Project Phase 1: Exploring BOTS v3 Datasets
Objective: To understand "Ground Truth" by analyzing a professional-grade dataset containing real-world attack scenarios (APT, Ransomware, and Credential Stuffing).

Tools used:
-Splunk Enterprise on Windows 11
-Boss of the SOC(BOTS) v3 dataset created by splunk used to simulate fictional company cyber events(Ransomware, brute forcing, credential stuffing)

Investigation Focus:
Before building my own pipeline, I used the BOTS v3 dataset to identify how professional analysts track lateral movement and brute-force attempts.
The key source types I analyzed were WinEventLog:Security. xmlwineventlog, and stream:http. I was able to identify failed logons with EventID:4625 and succes as EventID:4624.
