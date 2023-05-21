# Wazuh Synology DSM decoder and rules

Wazuh Decoder and Rule for syslog sent from Synology's Log Center.

## Installation

### Wazuh

1. Set `remote` syslog settings in Local configuration.
2. Import decoder and rule from this repository.
3. Restart Wazuh Manager.

### Synology

1. Install Log Center Package.
2. Set `Log Sending` in Log Center to send syslog to Wazuh in a format using `BSD (RFC 3164)`.

## Reference

- [remote - Local configuration (ossec.conf) · Wazuh documentation](https://documentation.wazuh.com/current/user-manual/reference/ossec-conf/remote.html)
- [Log Sending | Log Center - Synology Knowledge Center](https://kb.synology.com/en-us/DSM/help/LogCenter/logcenter_client?version=7)

