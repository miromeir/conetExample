# Examples Deliverable

# Spreadsheeet: https://docs.google.com/spreadsheets/d/13_uQLHdJweHVkILn_tiRtA942-UnUWvZMoTfKbR6-Qs/edit#gid=0
**Scenario:** a security-related task to be demonstrated. we extend each scenario to a full network using "Network Templates".

**Network Templates**: generic network segments used to extend each scenario.

**Variant**: A GNS3 File, Fully working network that extends a scenario with an arbitrary network.

### Goal:
To have 20 Variants in total.

Process of creating a variant:
1. Pick a scenario(exercise).
2. Plan a variant in GNS3. Use available network templates. *do not configure* devices, this will be done later by Elad and Miro.
3. Write an intent of what needs to be configured. for example: “Define Router FIREWALL to act as a firewall, Switch1 is in zone1 and Switch2 is in zone2”
4. Submit variant + intent to Rami for approval.
5. Devices configuration(done by Elad and Miro).
6. Upload to repository, in a folder. Each folder is named SxVy - x is a scenario number, y is a variant number. For Example: S1V1
## Available Scenarios
https://gns3vault.com/labs/security
1. [Basic Firewall Zones](https://gns3vault.com/security/basic-zone-based-firewall)
2. [Add IDS](https://gns3vault.com/security/ip-traffic-export)
3. Demo Scenario -lack of firewall between LAN and cloud
4. Configuring Unicast Reverse Path Forwarding (URPF)
5. Configuring a transparent router
