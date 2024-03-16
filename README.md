# Fire-con
Firecon, an reconnaissance automated tool, conducts scans such as Host and Port Scanning, Vulnerability and CVE Scanning, UDP Scan, and Recon on target systems. It identifies weaknesses, bolstering network security by providing valuable insights into system configurations and potential vulnerabilities.
![Screenshot 2024-03-16 221717](https://github.com/3rd3ye/Fire-con/assets/85607884/064082f1-2b69-4954-a98d-7823552b7a80)

INSTALLATION :

git clone https://github.com/3rd3ye/Fire-con.git

cd Fire-con

chmod +x Fire-con.sh

USAGE:

Help: ./Fire-con.sh -h or ./Fire-con.sh --help

Basic Scan: ./Firecon.sh -H/--host <TARGET-IP> -t/--type <TYPE>

SCAN TYPES:

Network : Shows all live hosts in the host's network (Approx 15 seconds)
Port : Shows all open ports (Approx 15 seconds)
Script : Runs a script scan on found ports (Approx 5 minutes)
Full : Runs a full range port scan, then runs a script scan on new ports (Approx 5-10 minutes)
UDP : Runs a UDP scan "requires sudo" (Approx 5 minutes)
Vulns : Runs CVE scan and nmap Vulnerabilities scan on all found ports (Approx 5-15 minutes)
Recon : Suggests a vareity of recon commands on your choice else automatically runs default(Depends)
All : Runs all the scanning methods at same time (Approx 20-30 minutes)


EXAMPLES :

Network Scan: ./Fire-con.sh -H <TARGET-IP> -t Network

Basic Port Scan: ./Fire-con.sh -H <TARGET-IP> -t Port

Script Scan: ./Fire-con.sh -H <TARGET-IP> -t Script

Full Scan: ./Fire-con.sh -H <TARGET-IP> -t Full

UDP Scan: ./Fire-con.sh -H <TARGET-IP> -t UDP

Vulns Scan: ./Fire-con.sh -H <TARGET-IP> -t Vulns

Recon: ./Fire-con.sh -H <TARGET-IP> -t Recon

All: ./Fire-con.sh -H <TARGET-IP> -t All



![Screenshot 2024-03-16 223738](https://github.com/3rd3ye/Fire-con/assets/85607884/f0184ea5-d756-4e9e-9321-a96d1cdb7a11)

![Screenshot 2024-03-16 223806](https://github.com/3rd3ye/Fire-con/assets/85607884/c248b2f1-4c98-483e-ad1a-c39c7a8df9ea)

NOTE : This recon tool is made and should be utilized for educational and research purposes.The platform and author is not responsible for indivudual user's activity and utilization.  


