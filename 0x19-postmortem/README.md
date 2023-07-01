# Postmortem

How to write an Incident Report, also referred to as a Postmortem. This postmortem follows the guidelines used closely by google engineers to file reports. The report is made up of five parts, an issue summary, a timeline, root cause analysis, resolution and recovery, and finally, corrective and preventative measures. Below are these parts in detail.

### Issue Summary

- short summary (5 sentences)
- list the duration along with start and end times (include timezone)
- state the impact (most user requests resulted in 500 errors, at peak 100%)
- end with root cause

### Timeline

- list the timezone
- covers the outage duration
- when outage started
- when staff was alerted
- actions, events, …
- when was service restored

### Root Cause

- give a detailed explanation of event
- do not sugarcoat

### Resolution and recovery

- give detailed explanation of measures taken (includes times)

### Corrective and Preventative Measures

- itemized list of ways to prevent it from happening again
- what can we do better next time?