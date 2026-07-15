# SkyNet Knowledge Articles

_Created: 2026-07-15 | Org: skynet-demo-org_

| Title                                | Salesforce Link                                                      | URL Name                             | Summary                                                                         | Status |
| ------------------------------------ | -------------------------------------------------------------------- | ------------------------------------ | ------------------------------------------------------------------------------- | ------ |
| Delayed Shipment — Standard Response | [Open](https://vr1782175908523.my.salesforce.com/ka0KY000001rLc6YAE) | `delayed-shipment-standard-response` | Template response: check tracking, contact warehouse, 4-hour SLA response time  | Online |
| Damaged Package — Claims Process     | [Open](https://vr1782175908523.my.salesforce.com/ka0KY000001rLcBYAU) | `damaged-package-claims-process`     | Procedure: photo of damage, claim form submission, 3-5 business days resolution | Online |
| Missed Pickup — Escalation Steps     | [Open](https://vr1782175908523.my.salesforce.com/ka0KY000001rLcGYAU) | `missed-pickup-escalation-steps`     | Escalation: contact dispatch, re-schedule pickup within 2 hours                 | Online |

## Details (вставить вручную в поле "Details" каждого артикла)

---

### Delayed Shipment — Standard Response

```
Overview
When a customer reports a delayed shipment, follow this standard procedure to resolve the issue efficiently and maintain SLA compliance.

Steps
1. Locate the shipment in the tracking system by AWB or tracking number.
2. Check the last scan event — identify where the parcel stopped and when.
3. If the last update is older than 24 hours, escalate to the warehouse operations team immediately.
4. Contact the customer within 4 hours to acknowledge the issue and share an initial status update.
5. If in transit, provide an estimated delivery window. If held at a facility, coordinate same-day release.
6. Once delivered, close the case and send delivery confirmation to the customer.

SLA
- First response: within 4 hours
- Resolution target: within 24 hours (domestic), 48 hours (cross-emirate)
```

---

### Damaged Package — Claims Process

```
Overview
When a customer receives a damaged package, initiate the claims process promptly to ensure fair resolution and preserve the client relationship.

Steps
1. Ask the customer to provide clear photos of the damaged package and its contents.
2. Record all relevant shipment details: AWB number, delivery date, declared value.
3. Send the customer a pre-filled Damage Claim Form and request it back within 48 hours.
4. Submit the completed claim along with photos to the Claims & Insurance team.
5. Provide the customer with a claim reference number and expected timeline.
6. Follow up at the 3-day mark and confirm resolution by day 5.

Timeline
- Claim acknowledgement: within 24 hours
- Resolution: 3–5 business days
- Compensation (if approved): within 7 business days
```

---

### Missed Pickup — Escalation Steps

```
Overview
When a scheduled pickup is not collected, immediate escalation is required to minimise impact on the customer and maintain service reliability.

Steps
1. Confirm the scheduled pickup details: address, time window, contact person, and number of items.
2. Check the driver assignment and route log to identify why the pickup was missed.
3. Contact the dispatch team immediately — provide the original pickup reference and customer details.
4. Dispatch must arrange a re-pickup within 2 hours of the missed window.
5. Proactively call the customer, apologise, and confirm the new pickup time.
6. After re-pickup is confirmed, log the incident in the system and flag for quality review.

Escalation Path
- Level 1: Dispatch team (immediate)
- Level 2: Operations Manager (if re-pickup cannot be done within 2 hours)
- Level 3: Account Manager notification (for enterprise accounts)
```

---

## Record IDs

| Title                                | Record ID            |
| ------------------------------------ | -------------------- |
| Delayed Shipment — Standard Response | `ka0KY000001rLc6YAE` |
| Damaged Package — Claims Process     | `ka0KY000001rLcBYAU` |
| Missed Pickup — Escalation Steps     | `ka0KY000001rLcGYAU` |
