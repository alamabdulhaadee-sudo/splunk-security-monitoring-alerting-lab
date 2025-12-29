# Splunk Security Monitoring & Alerting Lab















## Detection Screenshots

### DET-SSH-Bruteforce-By-IP
Detects multiple failed SSH authentication attempts originating from a single source IP, indicating a potential brute-force attack.

![SSH Bruteforce Detection](screenshots/det-ssh-bruteforce.png)

### DET-SSH-Password-Spray
Detects a single source IP attempting authentication against multiple distinct user accounts, which is characteristic of a password spray attack.

![SSH Password Spray Detection](screenshots/det-ssh-password-spray.png)

### DET-Root-Login-Attempt
Detects failed authentication attempts targeting the root account, which is considered high-risk activity.

![Root Login Attempt Detection](screenshots/det-root-login-attempt.png)

### DET-Sudo-Auth-Failure
Detects failed sudo authentication attempts that may indicate privilege escalation attempts or user error.

![Sudo Authentication Failure Detection](screenshots/det-sudo-auth-failure.png)
