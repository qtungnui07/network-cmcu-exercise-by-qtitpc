# Phòng mạng trung tâm — NOC

[← README tổng quan](../../README.md) · [Nguồn Notion](https://app.notion.com/p/3aae07453fa9816ba5c0f6ebf7ef10e7)

| Hạng mục | Giá trị |
| --- | --- |
| Switch | `SW-NOC-01` |
| IP quản trị | `10.10.100.11` |
| VLAN người dùng | `50` — `IT_NOC` |
| VLAN quản trị | `100` — `MANAGEMENT` |
| Uplink CORE | `CORE-SW01 Gi1/0/12` |
| Cổng uplink switch | `SW-NOC-01 Gi0/1` |
| VLAN cho phép | `50,100,999` |
| Native VLAN | `999` |

## Trạng thái

- [x] Trunk hoạt động.
- [x] IP quản trị hoạt động.
- [x] Kết nối tới gateway và ASA inside thành công.
