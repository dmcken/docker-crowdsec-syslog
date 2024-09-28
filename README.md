# Crowdsec syslog setup using Docker

Docker compose setup for crowdsec remote syslog server.

The primary contibution will be custom parsers for various network devices.
[https://docs.crowdsec.net/docs/next/parsers/intro/](Crowdsec Parsers)

## Basic

Use just the built in crowsec module [https://docs.crowdsec.net/docs/data_sources/syslog/](Crowdsec Syslog modul)

## High throughput

High throughput central syslog server. Per the crowdsec docs the built-in module isn't recommended for a high
rate of messages.

## Notes

* <https://doc.crowdsec.net/docs/next/parsers/format/>
* <https://doc.crowdsec.net/docs/next/parsers/create/>
* <https://github.com/crowdsecurity/hub/blob/master/parsers/s01-parse/a1ad/mikrotik-logs.yaml>
* <https://app.crowdsec.net/hub/author/crowdsecurity/configurations/syslog-logs>
* <https://docs.crowdsec.net/u/user_guides/cscli_explain/>
* <https://www.reddit.com/r/CrowdSec/comments/17m7t92/can_i_have_2_syslog_type_acquisitions_one_in_file/>
* <https://www.reddit.com/r/CrowdSec/comments/1cp9wdn/crowdsec_docker_whitelist_i_am_very_confused/>
* <https://www.reddit.com/r/CrowdSec/comments/12l5i6k/metrics_not_showing_sshd_logs/>
