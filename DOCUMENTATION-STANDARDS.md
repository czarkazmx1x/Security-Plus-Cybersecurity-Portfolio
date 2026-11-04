# Documentation standards

Use these standards across all projects.

1. **Scenario and scope:** State the fictional business need, owned/authorized assets, and what is outside scope.
2. **Environment:** Record tools, versions, virtual-network isolation, and sanitized topology.
3. **Procedure:** Explain reproducible numbered steps, commands, and relevant settings.
4. **Verification:** Record test ID, expected result, observed result, pass/fail, date, and evidence file.
5. **Findings:** Separate raw observation from inference; provide business impact and severity rationale.
6. **Improvements:** Explain remediation and test the same condition again.
7. **Reflection:** Explain limitations, troubleshooting, and what you would change next time.

## Evidence naming

Use descriptive filenames such as `P01-TC01-guest-to-staff-blocked.png`. Include dates and versions in reports, and use relative links from project README files.

## Publishing checklist

- [ ] Evidence is from an actual lab or clearly labeled as simulated.
- [ ] All credentials, private details, and sensitive addresses are removed.
- [ ] Images/logs support claims in the write-up.
- [ ] Failed tests are documented honestly.
- [ ] Scope and authorization are stated.
- [ ] Project status reflects actual completion.
