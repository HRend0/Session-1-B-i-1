# Session-1-B-1
[Bài tập] Hệ thống Quản lý Đăng ký Môn học Đại học
Câu 1:
- Thực thể là: Sinh viên (SinhVien), Môn học (MonHoc), Giảng viên (GiangVien), Lớp học phần (LopHocPhan), Đăng ký (DangKy) - Thực thể yếu.
- Thuộc tính là: (Khóa chính = **Thuộc tính**, Khóa ngoại = _Thuộc tính_)
  + SinhVien: **mã sinh viên**, họ tên, ngày sinh, giới tính, email, khoa
  + MonHoc: **mã môn**, tên môn, số tín chỉ, khoa phụ trách
  + GiangVien: **mã giảng viên**, họ tên, học vị, email, khoa
  + LopHocPhan: **mã lớp học phần**, học kỳ, năm học, phòng học
  + DangKy: _mã sinh viên_, _mã lớp học phần_
Câu 2:
- Mối quan hệ giữa các thực thể là:
  + Giảng viên - Lớp học phần: 1 Giảng viên có thể day nhiều Lớp học phần, 1 Lớp học phần có thể có nhiều Giảng viên tham gia giảng dạy do đó đây là mối quan hệ N-N.
  + Lớp học phần - Môn học: 1 Lớp học phần chỉ thuộc duy nhất 1 Môn học, 1 Môn học lại có thể có nhiều Lớp học phần do đó đây là mối quan hệ 1-N.
  + Sinh viên - Lớp học phần (Đăng ký): 1 Sinh viên chỉ có thể đăng ký 1 lớp học phần trong học kỳ, 1 Lớp học phần có thể được nhiều Sinh viên đăng ký do đó đây là mối quan hệ 1-N.
