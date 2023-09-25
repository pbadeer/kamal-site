---
title: Rebooting Traefik
---

# Rebooting Traefik

If you make changes to Traefik args or labels, you'll need to reboot with:

`kamal traefik reboot`

In production, reboot the Traefik containers one by one with a slower but safer approach, using a rolling reboot:

`kamal traefik reboot --rolling`