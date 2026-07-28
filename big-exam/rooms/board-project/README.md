# Phòng Board/Project

[← README tổng quan](../../README.md) · [Nguồn Notion](https://app.notion.com/p/3aae07453fa9816ba5c0f6ebf7ef10e7)

| Hạng mục | Giá trị |
| --- | --- |
| Switch | `SW-BOARD-01` |
| IP quản trị | `10.10.100.12` |
| VLAN người dùng | `10` — `BOARD_PROJECT` |
| Mạng/Gateway | `10.10.10.0/24` / `10.10.10.1` |
| Uplink CORE | `CORE-SW01 Gi1/0/3` |
| Cổng uplink switch | `SW-BOARD-01 Gi0/1` |
| VLAN cho phép | `10,100,140,999` |
| Native VLAN | `999` |

## Trạng thái

- [x] DHCP và inter-VLAN hoạt động.
- [x] VLAN 140 đã được chuẩn bị cho IP Phone.
