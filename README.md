# openwrt-domain-list

Personal categorized domain lists for OpenWrt routing, filtering and policy-based networking.

## Structure

```txt
lists/
└── mylist.src
```

## Format

Lists use a simple plain-text format:

```txt
// Category
example.com
subdomain.example.com
```

Comments start with `//`.

## Use Cases

- OpenWrt domain routing
- nftables/ipset generation
- Policy-based routing
- Tailscale split-routing
- Ad/tracker filtering
- Service grouping
- Gaming/service-specific routing

## Example Categories

- Development / Programming
- Minecraft / GTNH
- Dota 2
- Media / Streaming
- Infrastructure / Networking

## Notes

This repository is intentionally minimal and designed to be machine-readable.
