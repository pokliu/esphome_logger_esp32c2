# ESPHOME logger for esp32c2

---
Refer to: [External Component](https://esphome.io/components/external_components)

## Locally usage:
- Clone repository to local storage:
``` sh
cd ~/.esphome/external_components
git clone {This repository url} logger
```
- Add external components configration in yaml file:
``` yaml
external_components:
  - source: 
      type: local
      path: .esphome/external_components
    components:
      - logger
```