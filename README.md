# Microsoft 365 E3 & E5 — Conditional Access Controls Map

An interactive, single-page reference mapping all conditional access policy components across Microsoft 365 E3 and E5 licenses. Designed for identity architects, security engineers, and IT administrators who need a clear visual breakdown of what Conditional Access can do at each license tier.

---

## Features

- **8 tabbed views** for navigating the full Conditional Access landscape:
  1. **Policy Flow** — End-to-end IF/THEN pipeline (Signals → Conditions → Decision → Grant Controls → Session Controls)
  2. **Signals & Conditions** — All assignment targets, network locations, device filters, and risk conditions
  3. **Grant Controls** — Every available access control (MFA, compliant device, auth strength, terms of use, etc.)
  4. **Session Controls** — Sign-in frequency, persistent browser, app-enforced restrictions, CA App Control, token protection
  5. **Identity Protection** — Full risk detection catalog (real-time vs. offline) powered by Entra ID P2
  6. **Interactive Flowchart** — Clickable, animated pipeline showing how a sign-in travels through policy evaluation
  7. **Recommended Policies** — Microsoft-aligned baseline policy templates for both E3 and E5 deployments
  8. **E3 vs E5 Comparison** — Side-by-side table of every Conditional Access feature with license tier mapping
- **Dark / light mode** toggle
- **Color-coded license tiers**: green = E3 / Entra ID P1, amber = E5 / Entra ID P2, purple = separate add-on
- **Responsive and mobile-friendly** layout
- **Self-contained single HTML file** — no build step, no dependencies, no server required

---

## License Tiers

| Tier | What's Included |
|------|----------------|
| **E3** (green) | Entra ID P1 — all static Conditional Access conditions and controls: MFA, compliant device, named locations, approved client apps, app protection policies, sign-in frequency, persistent browser, continuous access evaluation |
| **E5** (amber) | Entra ID P2 + Microsoft Defender for Cloud Apps + Microsoft Purview — adds risk-based conditions (sign-in risk, user risk, service principal risk), real-time session proxy (CA App Control), Identity Protection risk detections, password change grant control, and insider risk integration |
| **Add-on** (purple) | Capabilities requiring a separate license beyond M365 E3/E5, such as Global Secure Access (Microsoft Entra Internet/Private Access) or Workload Identities Premium |

---

## Sources

- [Conditional Access Overview — Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview)
- [Grant Controls in Conditional Access — Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/conditional-access/concept-conditional-access-grant)
- [Session Controls in Conditional Access — Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/conditional-access/concept-conditional-access-session)
- [Conditions in Conditional Access — Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/conditional-access/concept-conditional-access-conditions)
- [Risk Detections — Microsoft Entra ID Protection](https://learn.microsoft.com/en-us/entra/id-protection/concept-identity-protection-risks)
- [Conditional Access App Control (Defender for Cloud Apps) — Microsoft Learn](https://learn.microsoft.com/en-us/defender-cloud-apps/proxy-intro-aad)
- [Microsoft Entra Pricing](https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing)

---

## Usage

Download `index.html` and open it in any modern browser. No internet connection required after the initial font load (Google Fonts). All logic, styles, and content are embedded in the single file.

---

*Created with [Perplexity Computer](https://www.perplexity.ai/computer)*
