# Phòng phát triển phần mềm

[← README tổng quan](../../README.md) · [Nguồn Notion](https://app.notion.com/p/3aae07453fa9816ba5c0f6ebf7ef10e7)

| Thiết bị | IP |
| --- | --- |
| `SW-DEV-DIST` | `10.10.100.32` |
| `SW-DEV-01` | `10.10.100.33` |
| `SW-DEV-02` | `10.10.100.34` |
| `SRV-DEV` | `10.10.40.10` |
| Printer DEV | `10.10.40.20` |

| Hạng mục | Giá trị |
| --- | --- |
| VLAN | `40` — `SOFTWARE_DEV` |
| Mạng/Gateway | `10.10.40.0/24` / `10.10.40.1` |
| Uplink CORE | `CORE-SW01 Gi1/0/7` |
| Thiết bị đầu xa | `SW-DEV-DIST Gi0/1` |
| VLAN cho phép | `40,100,999` |
| Native VLAN | `999` |
