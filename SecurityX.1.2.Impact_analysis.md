---
id: 5slfs4op6d7udce4ejbrid8
title: Impact_analysis
desc: ''
updated: 1716780183512
created: 1716084642302
---
Governance, Risk, and Compliance


Given a set of organizational security requirements, perform risk
management activities.

A business continuity and a disaster recovery plan should be built using information from a business impact analysis. BIA is an analysis aimed at identifying a organizations exposure to sudden lost of critical business functions and resources. This often happens due to an accident, disaster, emergency or threat. Some solution that you would explore here is redundant network connections, clustering, fault tolerance using raid, and facilities management.

Some key terms that you will encounter here are;

- Mean time to repair, MTTR
  - average time required to fixed a failed component or a device to restore it to production status.

- Mean time between failures MTBF
  - amount of time between one failure and the next.

- RTO/RPO
  - Recovery point objective, rpo is how far you can roll back in time, maximum allowed amount of data lost, measure in time from last backup to failure
  - Recovery time objective, RTO is how long it takes to restore from an incident until normal operations are restored.

- Single point of failure
  - single point of failure is a single part of a system that when it stops working, everything stops working. Avoid these if you can.

## Extreme but plausible scenarios

When planning include stuff that might be a once in a lifetime occurrence, be it the 100 year flood or something else. It's better to have a plan before hand than trying to build the plane as your are flying it.
