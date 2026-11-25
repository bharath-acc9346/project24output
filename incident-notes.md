# Project 24: Manual Chaos Test

Date: 25-Nov-2026

Service Tested: nginx

Objective:
Validate recovery after manual service failure.

Actions:
1. Verified nginx service was running.
2. Stopped nginx using sudo systemctl stop nginx.
3. Confirmed service entered inactive state.
4. Restarted nginx using sudo systemctl start nginx.
5. Verified service returned to active state.

Result:
PASS

Conclusion:
The service recovered successfully after manual intervention.
