# SafeHarbor Open Source Cybersecurity Tooling
SafeHarbor is an open-source security and infrastructure tooling project that provides robust, enterprise-grade defensive capabilities for modern cloud environments. The suite includes a real-time service monitoring system with integrated alerting for SRE teams, a defensive Web Application Firewall (WAF) with advanced threat detection, and a DDoS-resistant load balancer. All tools are written in Go, emphasizing performance, reliability, and security. The monitoring system features multi-channel alerting through Slack and PagerDuty, while the WAF offers protection against common attack vectors including SQL injection and XSS. The load balancer implements sophisticated rate limiting and automatic IP blocking capabilities. These tools are designed to work together or independently, providing a comprehensive security infrastructure that can be easily integrated into existing systems. SafeHarbor maintains a strong focus on defensive security practices, making it an ideal choice for organizations prioritizing system reliability and protection.

## Directory Structure
```
github.com/Safe-Harbor-Cybersecurity/
├── security-monitor/   (Infrastructure monitoring) 
├── defense-waf/        (Web Application Firewall)
├── monitor-alert/      (Service monitoring system)
├── Linux-file-monitor/ (Linux file monitoring system)
└── load-guardian/      (DDoS-protected load balancer)
```
