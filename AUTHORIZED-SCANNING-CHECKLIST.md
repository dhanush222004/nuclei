# Authorized scanning checklist

This companion checklist is a local addition to the fork of [ProjectDiscovery's Nuclei](https://github.com/projectdiscovery/nuclei). The original project remains credited to ProjectDiscovery and its contributors. Keep the upstream MIT license and copyright notice intact.

## Before scanning

- Scan only systems you own or have written permission to test.
- Record the approved targets, excluded systems, test window and a contact person.
- Start with a staging or lab environment that holds synthetic data. Do not scan production or third-party services without separate permission.
- Pin the Nuclei version and the template versions you use, so results can be repeated.
- Choose templates on purpose. Leave out templates you do not understand, and keep scan rates low enough not to disrupt the target.

## Before sharing a finding

- Separate confirmed findings from scanner matches that still need manual validation.
- Record the target, template ID, tool and template versions, and the time of the scan.
- Recheck that the claimed impact was observed rather than assumed from a match.
- Redact secrets, tokens and personal data from logs and reports. Share sensitive details only with the asset owner or the authorized security team.

This checklist does not change how Nuclei works or claim better detection accuracy. A clean scan is not proof that a system is secure.
