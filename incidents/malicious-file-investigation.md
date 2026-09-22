# Malicious File Investigation

## Incident Overview

This investigation involved analyzing a suspicious file hash after an organization's intrusion detection system generated an alert.

### Incident Classification

- **Incident Type:** Malicious file attachment
- **Threat Actor:** Unknown malicious actor
- **Organization:** Financial services company
- **Initial Vector:** Email attachment
- **Detection:** Intrusion detection system
- **Investigation Tool:** VirusTotal
- **Response Phase:** Detection and Analysis

---

## The 5 W's

### Who
An unknown malicious actor.

### What
An email sent to an employee contained a malicious file attachment.

SHA-256 hash:

```
54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b
```

### Where
An employee's computer at a financial services company.

### When
At 1:20 p.m., when the organization's SOC received an alert after the intrusion detection system detected the file.

### Why
The employee was able to download and execute a malicious file attachment delivered through email.

---

## Investigation

VirusTotal was used to investigate the suspicious file hash and determine whether the indicator had been reported as malicious.

The hash was reported as malicious.

The investigation represented the Detection and Analysis phase of incident response. The objective was to determine whether the security alert represented a genuine threat.

---

## Preventative Considerations

The original investigation raised the question of whether security awareness training should be improved so employees are more careful with email attachments and links.

---

## Analyst Takeaway

The investigation demonstrates the use of a file hash as an indicator of compromise and the importance of validating security alerts before determining the appropriate response.