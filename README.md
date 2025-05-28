# Document-cyberdefender-network-analysis-exfiltration-lab
###  CASE - This lab simulates a scenario where an accountant receives a malicious invoice email. As a SOC analyst, I performed detailed packet analysis using tools like Wireshark and virus Total to trace data exfiltration attempts, identify Indicators of Compromise, and understand attacker behavior, enhancing my incident response and threat hunting skills.

![Screenshot (45)](https://github.com/user-attachments/assets/30573fcb-acfa-408e-bd4b-21fe81f28fe0)


## Objective 
### Using CyberDefenders.io to gain real-world SOC experience by analyzing a malicious network PCAP file. The investigation involves identifying suspicious activity, detecting data exfiltration, and understanding attacker behavior to strengthen my skills in network forensics and incident response.


### Exporting PCAP file in wireshark.
![Screenshot (13)](https://github.com/user-attachments/assets/04c1119f-bca7-4eea-8af9-936f0b985ec1)


### Duration of capture {capture file properties}.

![Screenshot (14)](https://github.com/user-attachments/assets/6bdee027-a5be-4a76-a669-53cdedf7dc20)

### Sorting top talkers for ipv4 from bytes.

![Screenshot (16)](https://github.com/user-attachments/assets/fcac6ed5-bedf-4f91-b7ef-aefee5909886)

### Following HTTP stream on external IP to find out conversation between our internal IP  


![Screenshot (18)](https://github.com/user-attachments/assets/2b546da3-28d6-47e9-bc04-6ba94b76c483)


### Filtering SMTP traffic to get some information.


![Screenshot (19)](https://github.com/user-attachments/assets/030dcd29-ad16-4ec4-ac72-b1a06f2ff42f)

### Decoding {base64} information using cyber chef tool.

#### Decoding username

![Screenshot (20)](https://github.com/user-attachments/assets/0a365328-24d6-4016-9f88-c6bc6a833b6d)

#### Decoding password

![Screenshot (21)](https://github.com/user-attachments/assets/00b4eb1d-61be-4e46-9cf0-ef459f67c553)

#### Decoding subject

![Screenshot (22)](https://github.com/user-attachments/assets/af9d950e-a496-4184-868f-ba6b2001ebeb)
e
#### Decodinng content
![Screenshot (23)](https://github.com/user-attachments/assets/22dd75f6-c497-4f01-86e3-e2b293f08dc4)

![Screenshot (24)](https://github.com/user-attachments/assets/dda1ea53-a85b-4f68-afc1-151d5d885056)

![Screenshot (25)](https://github.com/user-attachments/assets/07d141cb-b62d-4717-aea5-6934cb12a799)



### Exporting file which we found in the beginning - proforma-invoice.com

![Screenshot (27)](https://github.com/user-attachments/assets/00706e67-c782-47ab-b297-777b33691f44)


#### Performing OSINT on the file we exported

![Screenshot (28)](https://github.com/user-attachments/assets/50d197f3-4355-4465-acee-2ad2703b8d6c)

- 57 antivirus flagged that file as malicious
![Screenshot (29)](https://github.com/user-attachments/assets/872072b5-a4c9-4ea4-9abb-818186526a3f)


## Skills Learned

- Interpreted PCAP files using tools like Wireshark and virus total to identify malicious communication and suspicious patterns.
- Simulated the role of a SOC Analyst by responding to a phishing attack scenario, including threat detection and mitigation.
- Extracted and documented IOCs such as IP addresses, domains, and file hashes used in the attack.
- Used platforms like VirusTotal and cyber chef to enrich data and confirm malicious activity.
- Analyzed phishing email behavior and its impact on the network, tracing malware activity initiated via a malicious download link.

## Conclusion

### Through this CyberDefenders lab, I gained practical experience in investigating real-world cyber attacks. I analyzed a malicious PCAP file using tools like Wireshark and virus total to detect suspicious network activity caused by a phishing email. This helped me improve my skills in network security and threat detection. It was a valuable hands-on experience that prepared me for real SOC work.


![Screenshot (50)](https://github.com/user-attachments/assets/50d979e5-0fea-416b-b3a4-44dbe2920805)






