Digital Ethics Risk Score patch to Shannon's entropy for ethical cybersecurity:

The Fallacy of Zero Entropy in Information Technology Systems: A Unified Cybersecurity Thesis Integrating NIST Risk Modeling, DERS, and Negative Trust



> "Zero probability is a political choice — not a mathematical truth."  
> — Code Transparency Lab - Madrid

## The Core Idea
In systems designed to extract value from users, **no threat is impossible**.  
Yet traditional entropy models erase low-probability risks — creating blind spots.

We introduce **𝔄 (the DERS constant)**: a minimum probability floor that ensures:
- No risk is ignored,
- No vendor is trusted by default,
- And no system is assumed safe.

This is **Negative Trust** — not just "never trust, always verify", but:  
> **"Assume all access is intentional. Assume all silence is strategic. Assume all systems are already compromised."**

DERS transforms information theory from a passive measure of uncertainty into an **active instrument of digital ethics**.

---

## The Zero Entropy Problem

Shannon’s entropy:
$$
H(X) = -\sum_{i=1}^{n} P(x_i) \log_2 P(x_i)
$$
is undefined when $ P(x_i) = 0 $, because $ \log_2(0) $ diverges.

In practice, the convention $ 0 \log 0 = 0 $ is used — but this **erases risk** under the guise of mathematical convenience.

In real-world systems — especially those shaped by surveillance capitalism — **zero probability is a fallacy**.  
It enables:
- Blind spots in threat modeling,
- Overconfidence in "secure" systems,
- And ethical negligence in design.

---

## The DERS Constant Solution

We enforce a **minimum viable malice**:

```python
𝔄 = baseline_DERS_constant
if P(x_i) < 𝔄:
    P(x_i) = 𝔄
```

This ensures:
- Mathematical stability (no undefined logs),
- Ethical accountability (no erased threats),
- And resilience against zero-day, insider, and emergent attacks.

The symbol **𝔄** (Germanic "A") is not arbitrary — it is a **glyph of digital conscience**, representing the **irreducible risk of exploitation** in any system that profits from user behavior.

---

## Dataset-Specific Constants

DERS is calibrated to real-world platform dynamics:

```bash
# Social Media Platforms
𝔄_social = 0.001        # Engagement algorithms optimize for addiction

# Financial Technology  
𝔄_fintech = 0.0005      # Regulatory constraints limit overt manipulation

# IoT/Smart Home Devices
𝔄_iot = 0.002           # Minimal oversight, maximum data harvesting

# Enterprise SaaS
𝔄_enterprise = 0.0002   # B2B accountability reduces baseline exploitation

# File/Malware Analysis
𝔄_file = 0.0001         # Original constant for static analysis
```

These values reflect the **inherent exploitability** of each domain — not just technical flaws, but **business model risks**.

---

## Dynamic Scaling Factors

Risk is not static. DERS evolves with power, time, and control:

```bash
# Market Dominance Factor (risk scales with monopoly power)
monopoly_multiplier = market_share²

# Regulatory Environment Factor  
regulation_factor = 1 / (privacy_laws × enforcement_budget)

# Revenue Model Dependency (ads/data = higher risk)
extraction_factor = (ad_revenue + data_sales) / total_revenue

# Temporal Decay (DERS increases with platform maturity)
temporal_factor = 1 + (0.1 × years_since_ipo)

# Final Adjusted Constant
𝔄_adjusted = 𝔄_base × monopoly_multiplier × regulation_factor × extraction_factor × temporal_factor
```

This equation embeds **political economy into cybersecurity** — making DERS not just a technical tool, but a **moral framework**.

---

## Applications

DERS can be integrated into:
- **NIST Risk Models** (SP 800-37, CSF): As a minimum risk floor.
- **Threat Intelligence Platforms**: To flag low-probability, high-impact attack paths.
- **Privacy Impact Assessments (PIAs)**: To quantify ethical risk under GDPR/DSA.
- **Open-Source Security Tools**: As a default entropy patch in analysis engines.

---

## Call to Action

Adopt DERS in your work.  
Patch your models.  
Reject the lie of zero entropy.

This is not optional.  
It is **ethical minimum viable security**.

> If it can be abused, it will be — and if your model allows $ p = 0 $, you’ve already failed.

---

## License
DERS is released under the **MIT License** — use, adapt, and redistribute freely.  
Because truth should never be proprietary.

> **Code Transparency Lab - Madrid**  
