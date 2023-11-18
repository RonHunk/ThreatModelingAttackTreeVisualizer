# ThreatModelingKillChainVisualizer
Using MS Threat Modeling tool and IDS/SIEM/EDR threat intelligent to visualize the kill chain for the application or infrastructure

Traditional threat modeling analysis is typically performed during the Secure SDLC design phase and is often limited to identifying known threats and vulnerabilities that map to assets such as web applications, business transaction APIs, and data.

But how about protecting against unknown-unknown threat attacks, such as APT and Lateral Movement? It’s important to note that these types of attacks are becoming increasingly sophisticated. 
Using the existing MS threat modeling tool, we still can decompose the use case, enumerate the attack tree with known-known. With this good foundation, we can leverage some reliable source of threat intelligence, plus your own cloud IDS/EDR/XDR/SIEM threat intelligent signal as input to the existing threat modeling. With new feed, this model/code can automatically re-analyze the attack tree and re-assess the threat modeling report. 

With the reliable source of threat intelligence and your cloud signal feed, this model/code also can draw the kill chain given the good foundation of existing threat model data.

In addition, this model/code can use updated threat modeling assessment result to feed into the ISO 27005 risk assessment template/questionnaire and automatically re-assess the application and infrastructure risk.
![image](https://github.com/RonHunk/ThreatModelingKillChainVisualizer/assets/35714750/e3d16218-7330-4e72-b2f1-9886ce109ef7)
