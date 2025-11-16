# 📖 Day 7 – Cleanup Drills on Tricky Concepts & Confidence Boost

**Date:** Nov 15, 2025  

---

### 🧩 Topics Covered
- Completed a **15-question mixed-difficulty exam** focused on:
  - **Pharming vs DNS poisoning vs ARP poisoning**
  - **WPA3 vs MAC filtering**
  - **NAC posture checks** (device health)
  - **Forward proxy vs IPsec tunnels**
  - **Email authentication** (SPF, DKIM, DMARC)
- Completed a **10-question targeted cleanup drill** on:
  - Pharming & DNS behavior
  - NAC health checks
  - WPA3 vs MAC filtering
  - Forward proxy use cases
  - SPF vs DKIM vs DMARC distinctions

---

### 💡 Key Takeaways
- Scored **12/15 (80%)** on the mixed exam and **9/10 (90%)** on the cleanup set, showing strong retention and rapid correction of previously weak areas.
- Solidified understanding of:
  - **Pharming**: HOSTS file / local resolution tampering, can persist across DNS/cache/network changes.  
  - **DNS poisoning**: tampering with DNS servers, often fixed by changing servers or flushing cache.  
  - **ARP poisoning**: LAN-level MAC/IP impersonation for on-path attacks.
  - **WPA3** as the *real* fix when MAC filtering fails on Wi-Fi (MAC filtering is easily bypassed).
  - **NAC health checks**: blocking devices with missing patches / outdated AV as a **health posture** failure.
  - **Forward proxy** for inspecting **outbound** web traffic vs. **IPsec** for encrypted tunnels without inspection.
  - **SPF vs DKIM vs DMARC**:
    - SPF = which servers can send mail  
    - DKIM = cryptographic signature of the message  
    - DMARC = policy enforcement if SPF/DKIM fail
- Only remaining “gotcha” on today’s sets was one tricky phrasing around pharming vs DNS poisoning, which is now clearly understood.

---

### 🧠 Reflection
Today was all about **polishing the sharp edges**, not relearning the basics.

These weren’t broad concept drills — they were laser-focused on:
- Email security records
- Name resolution attacks
- Wireless security hardening
- NAC behavior
- Web traffic filtering

The scores (80% then 90%) on question sets built specifically from my weak spots show that I’m not just memorizing answers — I’m actually internalizing how CompTIA expects me to **differentiate similar-sounding concepts under pressure.**

This kind of targeted refinement is exactly what will prevent “silly misses” on exam day.

---

### 📊 Total Questions Completed Today
**25 questions**  
- 15-question mixed weak-area exam  
- 10-question focused cleanup drill  

---

### 🎯 Action Plan for Tomorrow
- Do a **20–30 question mixed-domain exam** combining:
  - Attack chain stages  
  - Cloud/IAM (CMK, CASB, federation, NAC)  
  - Governance/compliance (PCI, PIA, NIST CSF, risk appetite)  
  - Network and wireless security (WPA3, proxies, VPNs, segmentation)
- Optionally run another **Professor Messer PDF pull** (20–30 random A/B/C questions) to stay aligned with his style.
- Continue logging daily progress in GitHub to show consistent, deliberate prep toward Security+.
