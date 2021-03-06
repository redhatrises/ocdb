## SCAP

SCAP content for OpenShift Container Platform 3 is being developed under [ComplianceAsCode project](https://github.com/ComplianceAsCode/content). Configuration compliance with the given SCAP content can be assessed automatically using [OpenSCAP tool](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/security_hardening/scanning-the-system-for-security-compliance-and-vulnerabilities_security-hardening).

### Open Computing Information Security Profile
Available downloads:
 * Implementation Guide
   * for Master Node [HTML](/cac/guides/ssg-ocp3-guide-opencis-master.html)
   * for a Node [HTML](/cac/guides/ssg-ocp3-guide-opencis-node.html)
 * SCAP content
   * All in one DataStream: [SCAP 1.3](/cac/ssg-ocp3-ds.xml), [SCAP 1.2](/cac/ssg-ocp3-ds-1.2.xml)
   * Checklist: [XCCDF 1.2](/cac/ssg-ocp3-xccdf-1.2.xml), [XCCDF 1.1](/cac/ssg-ocp3-xccdf.xml)
     * Assessment Details: [OVAL](/cac/ssg-ocp3-oval.xml)
     * Questionnaire: [OCIL](/cac/ssg-ocp3-ocil.xml)
 * All in one remediation scripts:
   * for Master Node [Ansible Playbook](/cac/ansible/ocp3-playbook-opencis-master.yml), [Bash](/cac/bash/ocp3-script-opencis-master.sh)
   * for a Node [Ansible Playbook](/cac/ansible/ocp3-playbook-opencis-node.yml), [Bash](/cac/bash/ocp3-script-opencis-node.sh)
