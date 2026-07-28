# Khu CCTV/IoT

[← README tổng quan](../../README.md) · [Nguồn Notion](https://app.notion.com/p/3aae07453fa9816ba5c0f6ebf7ef10e7)

| Thiết bị | IP |
| --- | --- |
| `SW-SEC-01` | `10.10.100.50` |
| `SRV-CCTV` | `10.10.130.10` |
| PC monitor | `10.10.130.20` |
| Camera 1–3 | `10.10.130.101–103` |

| Hạng mục | Giá trị |
| --- | --- |
| VLAN | `130` — `CCTV_IOT` |
| Mạng/Gateway | `10.10.130.0/24` / `10.10.130.1` |
| Uplink CORE | `CORE-SW01 Gi1/0/8` |
| Thiết bị đầu xa | `SW-SEC-01` |
| VLAN cho phép | `100,130,999` |
| Native VLAN | `999` |
