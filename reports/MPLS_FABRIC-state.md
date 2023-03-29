
# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 91 | 90 | 1 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| P-01 |  19 | 19 | 0 | - |
| P-02 |  22 | 22 | 0 | - |
| PE-01 |  12 | 12 | 0 | - |
| PE-02 |  15 | 15 | 0 | - |
| PE-03 |  11 | 11 | 0 | - |
| PE-04 |  12 | 11 | 1 | Interface State |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  6 | 6 | 0 |
| Interface State |  27 | 26 | 1 |
| LLDP Topology |  18 | 18 | 0 |
| IP Reachability |  18 | 18 | 0 |
| BGP |  22 | 22 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 27 | PE-04 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5/1 -  | FAIL | interface status: down - line protocol status: down |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | P-01 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 2 | P-02 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 3 | PE-01 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 4 | PE-02 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 5 | PE-03 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 6 | PE-04 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 7 | P-01 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1/1 - P2P_LINK_TO_PE-01_Ethernet1/1 | PASS |  |
| 8 | P-01 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2/1 - P2P_LINK_TO_PE-02_Ethernet50/1 | PASS |  |
| 9 | P-01 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet25/1 - P2P_LINK_TO_P-02_Ethernet25/1 | PASS |  |
| 10 | P-01 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet26/1 - P2P_LINK_TO_PE-03_Ethernet55/1 | PASS |  |
| 11 | P-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1/1 - P2P_LINK_TO_PE-04_Ethernet1/1 | PASS |  |
| 12 | P-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2/1 - P2P_LINK_TO_PE-04_Ethernet2/1 | PASS |  |
| 13 | P-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4/1 - P2P_LINK_TO_PE-03_Ethernet50/1 | PASS |  |
| 14 | P-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet25/1 - P2P_LINK_TO_P-01_Ethernet25/1 | PASS |  |
| 15 | P-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet26/1 - P2P_LINK_TO_PE-02_Ethernet55/1 | PASS |  |
| 16 | PE-01 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1/1 - P2P_LINK_TO_P-01_Ethernet1/1 | PASS |  |
| 17 | PE-01 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2/1 - P2P_LINK_TO_PE-02_Ethernet49/1 | PASS |  |
| 18 | PE-01 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5/1 -  | PASS |  |
| 19 | PE-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet49/1 - P2P_LINK_TO_PE-01_Ethernet2/1 | PASS |  |
| 20 | PE-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet50/1 - P2P_LINK_TO_P-01_Ethernet2/1 | PASS |  |
| 21 | PE-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet55/1 - P2P_LINK_TO_P-02_Ethernet26/1 | PASS |  |
| 22 | PE-02 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet52/1 -  | PASS |  |
| 23 | PE-03 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet50/1 - P2P_LINK_TO_P-02_Ethernet4/1 | PASS |  |
| 24 | PE-03 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet55/1 - P2P_LINK_TO_P-01_Ethernet26/1 | PASS |  |
| 25 | PE-04 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1/1 - P2P_LINK_TO_P-02_Ethernet1/1 | PASS |  |
| 26 | PE-04 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2/1 - P2P_LINK_TO_P-02_Ethernet2/1 | PASS |  |
| 27 | PE-04 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5/1 -  | FAIL | interface status: down - line protocol status: down |
| 28 | P-01 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - Overlay_Peering | PASS |  |
| 29 | P-02 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - Overlay_Peering | PASS |  |
| 30 | PE-01 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - Overlay_Peering | PASS |  |
| 31 | PE-02 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - Overlay_Peering | PASS |  |
| 32 | PE-03 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - Overlay_Peering | PASS |  |
| 33 | PE-04 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - Overlay_Peering | PASS |  |
| 34 | P-01 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1/1 - remote: PE-01_Ethernet1/1 | PASS |  |
| 35 | P-01 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2/1 - remote: PE-02_Ethernet50/1 | PASS |  |
| 36 | P-01 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet25/1 - remote: P-02_Ethernet25/1 | PASS |  |
| 37 | P-01 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet26/1 - remote: PE-03_Ethernet55/1 | PASS |  |
| 38 | P-02 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1/1 - remote: PE-04_Ethernet1/1 | PASS |  |
| 39 | P-02 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2/1 - remote: PE-04_Ethernet2/1 | PASS |  |
| 40 | P-02 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4/1 - remote: PE-03_Ethernet50/1 | PASS |  |
| 41 | P-02 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet25/1 - remote: P-01_Ethernet25/1 | PASS |  |
| 42 | P-02 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet26/1 - remote: PE-02_Ethernet55/1 | PASS |  |
| 43 | PE-01 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1/1 - remote: P-01_Ethernet1/1 | PASS |  |
| 44 | PE-01 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2/1 - remote: PE-02_Ethernet49/1 | PASS |  |
| 45 | PE-02 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet49/1 - remote: PE-01_Ethernet2/1 | PASS |  |
| 46 | PE-02 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet50/1 - remote: P-01_Ethernet2/1 | PASS |  |
| 47 | PE-02 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet55/1 - remote: P-02_Ethernet26/1 | PASS |  |
| 48 | PE-03 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet50/1 - remote: P-02_Ethernet4/1 | PASS |  |
| 49 | PE-03 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet55/1 - remote: P-01_Ethernet26/1 | PASS |  |
| 50 | PE-04 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1/1 - remote: P-02_Ethernet1/1 | PASS |  |
| 51 | PE-04 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2/1 - remote: P-02_Ethernet2/1 | PASS |  |
| 52 | P-01 | IP Reachability | ip reachability test p2p links | Source: P-01_Ethernet1/1 - Destination: PE-01_Ethernet1/1 | PASS |  |
| 53 | P-01 | IP Reachability | ip reachability test p2p links | Source: P-01_Ethernet2/1 - Destination: PE-02_Ethernet50/1 | PASS |  |
| 54 | P-01 | IP Reachability | ip reachability test p2p links | Source: P-01_Ethernet25/1 - Destination: P-02_Ethernet25/1 | PASS |  |
| 55 | P-01 | IP Reachability | ip reachability test p2p links | Source: P-01_Ethernet26/1 - Destination: PE-03_Ethernet55/1 | PASS |  |
| 56 | P-02 | IP Reachability | ip reachability test p2p links | Source: P-02_Ethernet1/1 - Destination: PE-04_Ethernet1/1 | PASS |  |
| 57 | P-02 | IP Reachability | ip reachability test p2p links | Source: P-02_Ethernet2/1 - Destination: PE-04_Ethernet2/1 | PASS |  |
| 58 | P-02 | IP Reachability | ip reachability test p2p links | Source: P-02_Ethernet4/1 - Destination: PE-03_Ethernet50/1 | PASS |  |
| 59 | P-02 | IP Reachability | ip reachability test p2p links | Source: P-02_Ethernet25/1 - Destination: P-01_Ethernet25/1 | PASS |  |
| 60 | P-02 | IP Reachability | ip reachability test p2p links | Source: P-02_Ethernet26/1 - Destination: PE-02_Ethernet55/1 | PASS |  |
| 61 | PE-01 | IP Reachability | ip reachability test p2p links | Source: PE-01_Ethernet1/1 - Destination: P-01_Ethernet1/1 | PASS |  |
| 62 | PE-01 | IP Reachability | ip reachability test p2p links | Source: PE-01_Ethernet2/1 - Destination: PE-02_Ethernet49/1 | PASS |  |
| 63 | PE-02 | IP Reachability | ip reachability test p2p links | Source: PE-02_Ethernet49/1 - Destination: PE-01_Ethernet2/1 | PASS |  |
| 64 | PE-02 | IP Reachability | ip reachability test p2p links | Source: PE-02_Ethernet50/1 - Destination: P-01_Ethernet2/1 | PASS |  |
| 65 | PE-02 | IP Reachability | ip reachability test p2p links | Source: PE-02_Ethernet55/1 - Destination: P-02_Ethernet26/1 | PASS |  |
| 66 | PE-03 | IP Reachability | ip reachability test p2p links | Source: PE-03_Ethernet50/1 - Destination: P-02_Ethernet4/1 | PASS |  |
| 67 | PE-03 | IP Reachability | ip reachability test p2p links | Source: PE-03_Ethernet55/1 - Destination: P-01_Ethernet26/1 | PASS |  |
| 68 | PE-04 | IP Reachability | ip reachability test p2p links | Source: PE-04_Ethernet1/1 - Destination: P-02_Ethernet1/1 | PASS |  |
| 69 | PE-04 | IP Reachability | ip reachability test p2p links | Source: PE-04_Ethernet2/1 - Destination: P-02_Ethernet2/1 | PASS |  |
| 70 | P-01 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 71 | P-02 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 72 | PE-01 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 73 | PE-02 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 74 | PE-03 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 75 | PE-04 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 76 | P-01 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.1 | PASS |  |
| 77 | P-01 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.2 | PASS |  |
| 78 | P-01 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.3 | PASS |  |
| 79 | P-01 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.4 | PASS |  |
| 80 | P-02 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.1 | PASS |  |
| 81 | P-02 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.2 | PASS |  |
| 82 | P-02 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.3 | PASS |  |
| 83 | P-02 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.4 | PASS |  |
| 84 | PE-01 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.11 | PASS |  |
| 85 | PE-01 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.12 | PASS |  |
| 86 | PE-02 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.11 | PASS |  |
| 87 | PE-02 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.12 | PASS |  |
| 88 | PE-03 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.11 | PASS |  |
| 89 | PE-03 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.12 | PASS |  |
| 90 | PE-04 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.11 | PASS |  |
| 91 | PE-04 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 100.70.0.12 | PASS |  |
