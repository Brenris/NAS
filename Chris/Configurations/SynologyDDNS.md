# Synology DDNS

## Setup

- Control Panel
- External Access
- DDNS
- Add
  - Service Provider: Synology
  - Hostname: cotto.synology.me
    - Use whatever available hostname you can under the synology.me domain
  - Email: Should be auto-populated
  - Heartbeat: Enabled
    - Left enabled, Synology will send alerts when the DDNS is down
  - External IP: Use whatever it has filled in for the actual external IP
  - Test Connection
    - Status should return `Normal` if your hostname hasn't been taken
  - Check the box
  - OK