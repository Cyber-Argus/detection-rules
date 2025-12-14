# Detection Engineering Methodology

## My Approach to Building Detections

### 1. Threat-Informed Detection

Every detection should map to real adversary behavior:
- Start with MITRE ATT&CK technique
- Understand how attackers use the technique
- Identify telemetry sources that capture the behavior
- Write detection logic that balances coverage vs. false positives

### 2. Detection Development Process

**Research Phase:**
1. Study the technique via blogs, malware analysis, threat reports
2. Identify what logs/telemetry capture the activity
3. Understand legitimate use cases (false positive sources)

**Writing Phase:**
1. Draft detection logic
2. Document expected true/false positives
3. Map to MITRE ATT&CK framework
4. Add references and context

**Testing Phase:**
1. Validate against known-malicious samples
2. Test against legitimate activity
3. Tune thresholds and filters
4. Document results

**Deployment Phase:**
1. Deploy to test environment
2. Monitor false positive rate
3. Iterate based on feedback
4. Promote to production when stable

### 3. Documentation Standards

Every detection includes:
- Clear description of what it detects
- MITRE ATT&CK mapping
- Detection logic explanation
- False positive analysis
- Tuning recommendations
- Testing status/results

### 4. Quality Over Quantity

I prioritize:
- Well-documented detections over large numbers
- Understanding *why* a detection works
- Operational feasibility (acceptable false positives)
- Detections that detect behavior, not just IOCs

### 5. Learning Resources

Key resources I'm using:
- "Practical Threat Detection Engineering" book
- MITRE ATT&CK framework
- SigmaHQ rule repository
- Malware analysis blogs (OALabs, malware-traffic-analysis.net)
- Detection engineering community (Twitter/X, LinkedIn, GitHub)

---

**Last Updated:** December 14, 2024
