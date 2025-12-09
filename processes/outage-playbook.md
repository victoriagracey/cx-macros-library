# Service Outage Playbook (System-Neutral)

A structured guide for identifying, communicating, and managing outages or degraded performance issues. This playbook ensures consistency, reduces customer anxiety, and keeps internal teams aligned during time-sensitive incidents.

---

## 🚨 1. Identifying a Potential Outage

### Signs of an outage:
- Multiple customers reporting the same issue  
- Internal tools failing or loading slowly  
- Error rates suddenly increasing  
- Reports across social media  
- Team members experiencing it directly  

### First steps:
1. Attempt to reproduce the issue internally  
2. Check internal monitoring tools (if available)  
3. Check status pages  
4. Ask teammates if they see the same behaviour  
5. Tag/notify engineering or on-call staff if confirmed  

---

## 🧩 2. Classifying Severity Levels

### **SEV 1 — Major Outage**
- Critical features fully down  
- Majority of customers affected  
- Payments, logins, core workflow broken  
- Requires immediate cross-team action  

### **SEV 2 — Partial Outage / Major Degradation**
- Important features partially failing  
- Significant number of customers affected  
- Workarounds may exist  

### **SEV 3 — Minor Issue**
- Small subset of customers affected  
- Intermittent errors  
- Low business impact  

Clear severity helps set the right expectations for updates.

---

## 📣 3. Internal Communication Template

> **Internal Alert – Potential Outage**  
> - Issue: {brief description}  
> - Impact: {who/what is affected}  
> - Severity: {SEV1/SEV2/SEV3}  
> - First noticed: {time}  
> - Reproduced internally: Yes/No  
> - Teams notified: {engineering/on-call/etc}  
> - Next update: {timeframe}  

Short, factual, and easy to scan.

---

## 🗣️ 4. Customer-Facing Message – Initial Acknowledgement

> Thanks for reaching out — we're aware that some customers are experiencing issues with **{feature}** right now.  
>
> Our team is investigating, and we’ll share updates as soon as we have them.  
> Thanks for your patience while we work on this 💜

Keep it calm, simple, and reassuring.

---

## 🔄 5. Customer Update – In Progress (Keep It Short)

> Quick update: our team is still working on fixing the issue with **{feature}**.  
> We’ll share more news within **{timeframe}**, even if nothing has changed yet.  
>
> Thanks again for bearing with us.

Customers value **predictable update intervals**.

---

## ✅ 6. Resolution Message – Issue Fixed

> Good news — the issue affecting **{feature}** has now been resolved.  
>
> Everything should be working normally again. If you’re still having trouble, try {step}, and let us know if anything persists.  
>
> Thanks so much for your patience while we sorted this.

---

## ⚙️ 7. Recommended Customer Support Steps During an Outage

- Avoid deep troubleshooting — it wastes time  
- Avoid blaming the customer  
- Set clear expectations  
- Link to the status page (if applicable)  
- Use consistent wording across all agents  
- Provide workarounds when possible  
- Keep tone warm and human  

---

## 🧭 8. Social Media Outage Template (short form)

> We’re aware of an issue affecting **{feature}** and our team is on it.  
> Updates soon — thank you for your patience 💜

Perfect for X/Twitter, Facebook, Instagram.

---

## 🔧 9. When to Escalate Internally

Escalate if:
- Issue is reproducible and high impact  
- Outage affects payments or logins  
- Users report data loss  
- Social media volume spikes suddenly  
- Customer sentiment turns highly negative  
- Any security concern is mentioned  

---

## 📝 10. Post-Outage Checklist (Internal)

After resolution:
- Confirm stability across devices  
- Update internal teams  
- Close incident channel/ticket  
- Send final customer update  
- Tag conversations for tracking  
- Note any customers needing follow-up  
- Document lessons learned  

---

## 🔍 11. Optional: Post-Mortem Summary Template

> **Incident Summary:** {brief summary}  
> **Root Cause:** {if known}  
> **Fix Applied:** {what was done}  
> **Time to Resolution:** {duration}  
> **Next Steps:** {preventative measures}  
>
> **Notes:** Include anything that may help future incidents.

This shows you understand true Support Ops behaviour.

