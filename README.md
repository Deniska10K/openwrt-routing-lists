# openwrt-routing-lists

A collection of categorized routing target lists for OpenWrt and other networking tools.

Designed for:
- policy-based routing (PBR)
- split tunneling
- VPN routing
- nftables/ipset generation
- DNS-based filtering
- traffic segregation
- service-specific routing

---

## Repository Structure

```txt
lists/
├── domains/
│   ├── development.srs
│   ├── gaming.srs
│   ├── media.srs
│   └── misc.srs
│
├── subnets/
│   ├── cloudflare.srs
│   ├── tailscale.srs
│   └── custom.srs
│
├── mixed/
│   └── custom.srs
│
└── generated/
    ├── dnsmasq/
    ├── nftables/
    └── sing-box/
```

---

## File Formats

### Domain Lists

```txt
// Development / Programming
github.com
githubusercontent.com
githubcopilot.com

// Minecraft / GTNH
minecraft.net
gtnewhorizons.com
wiki.gtnewhorizons.com
```

### Subnet Lists

```txt
100.64.0.0/10
10.0.0.0/8
192.168.0.0/16
```

### Mixed Lists

```txt
github.com
1.1.1.0/24
100.64.0.0/10
```

Comments start with `//`.
