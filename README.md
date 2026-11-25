Hi, I'm Jaguarmayan

Detection engineering and SOC work, mostly built in a home lab and published so
the next person does not have to start from zero.

What I work with: Wazuh · threat-intelligence feeds · CDB and Sigma
detection content · Python · Docker · Kali / Proxmox

What I'm building

OpenIOCCollector —
~155,000 deduplicated indicators of compromise rebuilt from six public feeds
every night, published as checksummed Wazuh CDB lists with a staleness guard,
a 90-day trend and an in-browser lookup.

live dashboard ·
source ·
API manifest

How I think about detections

A feed is only as useful as the pipeline around it. If a list can silently
shrink, a broken upstream blinds your rules and nobody notices for a week. Most
of my work is the unglamorous part: provenance on every indicator, a guard that
refuses to publish a bad day, checksums the manager verifies, and a page that
will not claim "today" when the data is from Tuesday.

Elsewhere: jaguarmayan8.github.io/OpenIOCCollector
