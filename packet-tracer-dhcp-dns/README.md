# DHCP & DNS Protocols (Packet Tracer)

A simple Cisco Packet Tracer lab that demonstrates **DHCP server configuration** and **DNS name resolution**.

## Files
- `dhcp-dns-protocols.pkz` — Packet Tracer project (open with Packet Tracer 8.x or newer).

## How to Open
1. Open **Cisco Packet Tracer**.
2. `File → Open...` and select `dhcp-dns-protocols.pkz`.
   - If your Packet Tracer cannot open `.pkz`, extract it first (it's a zipped PT project) and open the `.pkt` inside.
3. If the file does not open, update Packet Tracer to a newer 8.x version.

## What This Lab Shows
- DHCP pool, default gateway, and DNS server configuration.
- PC client obtaining IP via DHCP.
- Name resolution test (e.g., `ping hostname`) via DNS.

## Verification
- On router/switch: `show ip dhcp binding`, `show running-config`.
- On PC (Desktop → Command Prompt): `ipconfig /all`, `ping 8.8.8.8`, `ping example.com`.

## Notes
- GitHub has a 100 MB per-file limit; use **Git LFS** if your `.pkz/.pkt` exceeds that.
- Tested with Packet Tracer 8.x.
