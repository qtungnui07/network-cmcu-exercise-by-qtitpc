# Phòng R&D

[← README tổng quan](../../README.md) · [Nguồn Notion](https://app.notion.com/p/3aae07453fa9816ba5c0f6ebf7ef10e7)

| Thiết bị | IP |
| --- | --- |
| `SW-RD-DIST` | `10.10.100.21` |
| `SW-RD-01` | `10.10.100.22` |
| `SW-RD-02` | `10.10.100.23` |
| `SRV-RD` | `10.10.20.10` |
| Printer R&D | `10.10.20.20` |

| Hạng mục | Giá trị |
| --- | --- |
| VLAN | `20` — `RD` |
| Mạng/Gateway | `10.10.20.0/24` / `10.10.20.1` |
| Uplink CORE | `CORE-SW01 Gi1/0/4` |
| Thiết bị đầu xa | `SW-RD-DIST` |
| VLAN cho phép | `20,100,999` |
| Native VLAN | `999` |
