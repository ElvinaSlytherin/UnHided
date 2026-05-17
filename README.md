---
title: UnHided MediaFlow
emoji: 🎬
colorFrom: blue
colorTo: purple
sdk: docker
app_port: 7860
pinned: false
---

# UnHided
## Env Vars
```
API_PASSWORD = Yourpassword
```
### Mamma Mia
If you want to install MammaMia addon as well put also that enviroment variable
```
TRANSPORT_ROUTES = {
    "all://*.ichigotv.net": {
        "verify_ssl": false
    },
    "all://ichigotv.net": {
        "verify_ssl": false
    }
}
```
