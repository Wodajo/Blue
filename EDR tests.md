### [ESET](https://www.eset.com/pl/business/download/eset-protect/#all-in-one)
application or service (on VM) for managing end-point hosts security
There might be colisions with `Wireshark`'s `pcap`
It needs `java` to run

setup.exe -> select what you want:
	Microsoft SQL Server Express - baza danych laczaca dane z End-pointow
		Credentials for server, ports and TLS Cetificate
	ESET PROTECT Server
	Mobile Device Connector
		hostname and ports
	ESET Management Agent
	Apache Tomcat
	ESET PROTECT Webconsole
	Rogue Detection Sensor
	Apache HTTP Proxy

[It works babeee (under your IP, here 10.2.0.2 due to VPN loopback for DNS leak protection)](https://10.2.0.2/era)

Buissness login is mail address...
Uses hostnams - what if hostname changes?

Static group - groups with not-variable stats like Windows, Linux, full disk encrypted
Dynamic group - e.g. problematic, not activated sec. product -> can update automatically & can use rules (like "if sth new in problematic group - alert and run command x")