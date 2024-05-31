---
id: nz7voef4j31veqmzg1zyycc
title: Availability_risk_considerations
desc: ''
updated: 1716780172931
created: 1716084717019
---
Governance, Risk, and Compliance

Given a set of organizational security requirements, perform risk
management activities.

To get started lets make sure we understand the terminology around risk.
An Asset is an item of value to the organization, including stuff as data, hardware, software, or physical property.
A Risk is the probability or likelihood of a threat.
A vulnerability is a weakness in hardware or software, that may be exploited.
A threat is anything that can cause harm, loss, damage or comprise an asset.
Motivation is the reason why an activity is happening, for example a hacktivist might attack the network due to the company having opposing political views.
The source of a risk, can be internal or external, and internal risk is anything from inside the company and an external is anything outside of the company including hackers and natural disasters.

## Business continuity/disaster recovery

Business continuity is proactive, goal is to minimize risk and help ensure the business can continue to run no matter the circumstances.
Disaster recovery is a subset of business continuity that focuses on the IT systems, and is reactive, only is triggered after an incident.
Disaster recovery is a deep topic and I would recommend you do some further research into it.
There is three types of sites for disaster recovery, these are sites set up to enable a quicker recovery time. A Hot site is a fully functional data center with everything ready to go including software, hardware, people, and data. A warm side is an equipped data center that does not have the data. A cold site has just the infrastructure, but no technology until the disaster response is activated.

### Testing

Before you have a live incident, it's best to get your feet wet with some testing. Testing comes in five catagories. A Walk-Through is one of the least disruptive ways to test, you get everyone together and they walk though what actions they would take to respond to and incident. The easiest form of testing a checklist test. Y'all just read though the checklist of procedures to help determine gaps or concerns to further analyze. The tabletop exercise is closer to a real incident but combines the previous ones and allows for more discussions about the incident response. Parallel Test are when the team runs through the steps along side the disaster recovery systems and processes. This is often group with a Simulation test, in which the team goes though all of the steps, but the production system stays running. A full interruption test is the holy grail of testing, you preform a simulated disaster by downing something and testing the response of your disaster/incident recovery plan.

## Backups

There is four types of backups, note database replication is not a backup
Differential backup, includes all changes to data since the last full back up, faster after the first full back up.
Incremental Backup, includes all changes to data since the lack full, differential, or incremental backup.
Full back up, backs up all the things!

### Connected

No clue what this is about, maybe hot and cold sites talked about above?

### Disconnected

No clue what this is about, maybe hot and cold sites talked about above?
