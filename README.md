## Security-principles / **[Network-Access-Control-NAC](https://github.com/sherazi1214/Network-Access-Control-NAC-/blob/main/README.md)**

## Network Devices

**English:** Network devices are hardware components that connect, manage, and secure data communication in a network.

**Urdu:** Network devices wo hardware hote hain jo data ko network ke andar connect aur manage karte hain.

## Common Devices:

**Router** → Connects different networks (Internet ↔ LAN).

**Switch** → Connects devices within a LAN.

**Hub** → Simple device, broadcasts data to all.

**Firewall** → Protects network by filtering traffic.

**Access Point** → Provides wireless connectivity.

**Gateway** → Connects networks with different protocols.

## Types of Network Monitoring Devices

**English:** Devices/tools used to monitor performance, availability, and security of a network.

**Urdu:** Monitoring devices network ki health aur security check karte hain.

## Types:

Network Analyzer / Packet Sniffer → Captures and analyzes network traffic. (e.g., Wireshark)

IDS/IPS (Intrusion Detection/Prevention Systems) → Detects or blocks suspicious activity.

SNMP-based Monitoring Devices → Track CPU, bandwidth, memory usage.

Probes / Agents → Installed to collect performance metrics.

Firewalls with Monitoring → Some firewalls include monitoring & logging.

## Decision State

**English:** Decision state refers to the condition of a network device when it must decide how to process or forward data packets (e.g., routing, switching, or dropping).

**Urdu:** Decision state wo halat hoti hai jab device (router/switch) decide karta hai k data packet ko kahan bhejna hai, block karna hai ya drop karna hai.

**Example:**

Router deciding best path using routing table.

Firewall deciding allow/deny rule.

## Device Failure Modes

**English:** Failure modes describe how a device behaves when it fails.

**Urdu:** Failure modes ka matlab hai ek device fail hone par kis tarah behave karega.

## Types:

**Fail-Open** → Device fails but keeps traffic flowing (less secure).

**Urdu:** Device fail ho jata hai lekin traffic allow karta rehta hai.

**Example:** Firewall fail → all traffic passes.

**Fail-Closed** → Device fails and blocks all traffic (more secure, but can disrupt service).

**Urdu:** Device fail ho jaye to sab kuch block ho jata hai.

**Example:** Firewall fail → no traffic passes.

**Failover Mode** → Backup device automatically takes over.

**Urdu:** Agar primary device down ho jaye to backup turant start ho jata hai.

**Degraded Mode** → Device works but with reduced performance.

**Urdu:** Device chal raha hai lekin performance slow ho jati hai.

## Quick Summary:

Network Devices = Router, Switch, Hub, Firewall, Gateway, AP.

Monitoring Devices = Packet sniffer, IDS/IPS, SNMP tools, Probes.

Decision State = Device making decision on forwarding/blocking data.

Failure Modes = Fail-Open, Fail-Closed, Failover, Degraded.
