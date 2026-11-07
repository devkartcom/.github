# Devkart

**Devkart Technologies LLP** builds custom software, multi-tenant SaaS platforms and MVPs,
engineered to scale from day one. We also build and run two SaaS products of our own.

## Our products

| Product | What it is |
|---|---|
| **[Supaorder](https://www.supaorder.com)** | White-label online ordering for restaurants. Orders go straight into Clover, Square or Toast, deliveries are dispatched for you, and restaurants pay a flat monthly fee instead of a commission. [Docs](https://docs.supaorder.com) |
| **[SuperApp](https://www.superapphq.com)** | A white-label multi-vertical marketplace platform: launch food delivery, retail and supermarkets on one platform. [Docs](https://docs.superapphq.com) |

## Open-source plugins

Capacitor plugins for point-of-sale printing, used in production by Supaorder and SuperApp.
They install from a git tag (`dist/` is committed), not from the npm registry.

| Package | What it does |
|---|---|
| [`@devkartcom/capacitor-star-printer`](https://github.com/devkartcom/capacitor-star-printer) | Star Micronics printers over Bluetooth, USB and LAN, via the official StarXpand SDK |
| [`@devkartcom/capacitor-tcp-print`](https://github.com/devkartcom/capacitor-tcp-print) | Raw TCP (port 9100) printing to network printers, with LAN discovery |
| [`@devkartcom/capacitor-usb-print`](https://github.com/devkartcom/capacitor-usb-print) | Raw ESC/POS printing to USB receipt printers on Android |
| [`@devkartcom/capacitor-thermal-printer`](https://github.com/devkartcom/capacitor-thermal-printer) | Bluetooth thermal printers, with Swift Package Manager support; a maintained fork of [Malik12tree/capacitor-thermal-printer](https://github.com/Malik12tree/capacitor-thermal-printer) |
| [`background-geolocation`](https://github.com/devkartcom/background-geolocation) | Background location updates for driver apps: our Capacitor 8 build of [capacitor-community/background-geolocation](https://github.com/capacitor-community/background-geolocation), kept until the official 1.3.1 release replaces it |

```sh
npm i github:devkartcom/capacitor-usb-print#v0.1.2
npx cap sync
```

## Contact

[devkart.com](https://devkart.com) · [Contact us](https://devkart.com/contact) ·
[LinkedIn](https://www.linkedin.com/company/devkart-tech) ·
[X](https://x.com/devkart_tech) ·
[YouTube](https://www.youtube.com/@Devkartcom)
