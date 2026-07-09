# Topology Design Decisions

## Why a Three-Tier Architecture?

A three-tier architecture was selected because it provides:

- Scalability
- Easier troubleshooting
- Improved performance
- Better fault isolation

---

## Why Dual ISPs?

Dual Internet connections provide redundancy.

If the primary ISP fails, the secondary ISP maintains Internet connectivity.

---

## Why a Layer 3 Core Switch?

The Core Switch performs:

- Inter-VLAN Routing
- High-speed forwarding
- Backbone connectivity

This improves performance compared to router-on-a-stick designs.

---

## Why Separate VLANs?

Each department operates within its own VLAN to:

- Reduce broadcast traffic
- Improve security
- Simplify management

---

## Future Expansion

The architecture supports additional floors, buildings, and branch offices without major redesign.
