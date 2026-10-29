# Phần 1: 3 hậu quả của "Thảm họa dữ liệu truyền thống"
- Mất dữ liệu vĩnh viễn: Ghi đè file (Ctrl+S) trên máy cá nhân khi đang lỗi khiến đoạn code quan trọng mất trắng.

- Nhầm lẫn phiên bản: Gửi file thủ công (v1, v2_final) qua Zalo dễ làm nhóm dùng nhầm code cũ.

- Phụ thuộc một điểm (SPOF): Tiến độ phụ thuộc hoàn toàn vào máy của Nam; máy hỏng hoặc xóa nhầm là cả đội tắc nghẽn.

# Phần 2: Đề xuất quy trình Hybrid Workflow (1-click khôi phục)
- Đưa code lên Cloud / GitHub: Quản lý mã nguồn tập trung thay vì chỉ lưu ổ D:\.

- Đồng bộ hóa workspace: Lưu trữ dữ liệu chung trên đám mây nhóm (Google Drive / Cloud Workspace).

- Tận dụng Version History: Sử dụng lịch sử phiên bản để quay lại trạng thái code trước khi lỗi chỉ với 1-click.