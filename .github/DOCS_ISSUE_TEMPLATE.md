---
title: "[Translations] Include changes in #{{ payload.event.pull_request.number }}"
labels: documentation, translation
---
Update Translations to include {{ sha }}, which is 

#{{ payload.event.pull_request.number }}
#{{ github.event.pull_request.number }}
#{{ event.pull_request.number }}

- [ ] en (@felangel)
- [ ] cs (@tenhobi)
