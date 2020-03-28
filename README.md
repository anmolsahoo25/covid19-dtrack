DTrack
---

An open-source, distributed, privacy-first app for making COVID-19
tracking easier.

Overview
---
This app is an attempt to tackle one aspect of the COVID-19 issue,
i.e. tracing diagnosed people and their contacts. As noble as the
intention be, there are serious privacy issues, if not done properly,
which threaten to outweight any potential benefit of this app. Thus,
our principles for the app are - 

1. **Privacy** - data is stored locally, encrypted and in the control
of the user
2. **Distributed** - no central body should have access to all the data
3. **Open-source** - it should be possible for anyone to audit the app
4. **Safety** - only the bare minimum data required is shared, with proper
data-deletion and revocation policies

The approach
---
Traditional apps will send all user data to a central storage and compute
cases and incidences on the centralized server itself. 

![image of an app with people sending data to cloud](docs/assets/trad_app.png =512x)
