# Data Center

[← README tổng quan](../../README.md) · [Nguồn Notion](https://app.notion.com/p/3aae07453fa9816ba5c0f6ebf7ef10e7)

| Thiết bị | IP |
| --- | --- |
| `SW-DC-01` | `10.10.100.20` |
| `SRV-DHCP-DNS` | `10.10.90.10` |
| `SRV-WEB` | `10.10.90.20` |
| `SRV-FILE` | `10.10.90.30` |
| `SRV-DATABASE` | `10.10.90.40` |
| `SRV-MAIL` | `10.10.90.50` |
| `SRV-BACKUP` | `10.10.90.60` |
| Printer Data Center | `10.10.90.70` |
| PC Admin Data Center | `10.10.50.20` |

## Kết nối

| Hạng mục | Giá trị |
| --- | --- |
| Uplink CORE | `CORE-SW01 Gi1/0/2` |
| Cổng uplink switch | `SW-DC-01 Gi1/0/1` |
| VLAN cho phép | `50,90,100,999` |
| Native VLAN | `999` |
