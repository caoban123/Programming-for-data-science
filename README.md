# Programming for Data Science

## Giới thiệu

**Lập trình cho Khoa học dữ liệu (Programming for Data Science)** giúp người học xây dựng nền tảng lập trình và sử dụng các công cụ để giải quyết bài toán dữ liệu. Môn học kết nối kỹ năng viết chương trình với quy trình làm việc thực tế: đặt câu hỏi, thu thập dữ liệu, khám phá, tiền xử lý, phân tích và trình bày kết quả.

Repository này lưu trữ tài liệu, bài thực hành và bài tập cá nhân trong quá trình học môn học.

## Nội dung repository

| Tệp / thư mục | Nội dung |
| --- | --- |
| [`lecture/`](lecture/) | Slide bài giảng và tài liệu đồ án cuối kỳ |
| [`Data/`](Data/) | Dữ liệu CSV phục vụ bài thực hành |
| [`Lab01.ipynb`](Lab01.ipynb) | Thực hành dòng lệnh Linux, Git và dữ liệu văn bản |
| [`Homework2.ipynb`](Homework2.ipynb) | Thực hành quy trình khoa học dữ liệu bằng Python thuần |
| [`linux_assignment.docx`](linux_assignment.docx) | Tài liệu bài tập Linux |

## Mục tiêu học tập

- Sử dụng Python để xử lý dữ liệu và giải quyết các bài toán cơ bản.
- Làm việc với dòng lệnh Linux, Git và dữ liệu văn bản.
- Đọc, kiểm tra, làm sạch và tổ chức dữ liệu một cách có hệ thống.
- Vận dụng quy trình khoa học dữ liệu từ câu hỏi ban đầu đến kết quả phân tích.
- Viết mã rõ ràng, hạn chế lặp lại và kiểm tra tính đúng đắn của chương trình.
- Trình bày cách làm và kết quả bằng Jupyter Notebook, đồng thời bảo đảm khả năng tái lập.

## Các chủ đề học tập

Các chủ đề dưới đây giới thiệu định hướng học tập của repository, không thay thế đề cương chính thức của môn học.

| Chủ đề | Nội dung |
| --- | --- |
| Công cụ làm việc | Dòng lệnh Linux, Git, GitHub và Jupyter Notebook |
| Nền tảng Python | Kiểu dữ liệu, cấu trúc điều khiển, hàm và các cấu trúc dữ liệu cơ bản |
| Dữ liệu văn bản | Đọc và ghi tệp, xử lý chuỗi, làm việc với định dạng CSV |
| Quy trình khoa học dữ liệu | Đặt câu hỏi, thu thập, khám phá, tiền xử lý, kiểm tra và phân tích dữ liệu |
| Chất lượng chương trình | Tính dễ đọc, tái sử dụng mã, kiểm thử và khả năng tái lập |
| Trình bày kết quả | Giải thích phương pháp, nhận xét kết quả và nêu giới hạn của phân tích |

## Công cụ thực hành

- **Python 3**: ngôn ngữ lập trình chính.
- **Jupyter Notebook / JupyterLab**: viết mã, ghi chú và xem kết quả trong cùng một tài liệu.
- **Git và GitHub**: quản lý phiên bản và lưu trữ bài làm.
- **Terminal / môi trường Linux**: thực hành dòng lệnh và xử lý dữ liệu văn bản theo yêu cầu từng bài.

Thư viện sử dụng sẽ phụ thuộc vào yêu cầu của từng bài tập. Một số bài có thể chỉ cho phép Python thuần và các mô-đun trong thư viện chuẩn như `csv`, `datetime`, `math` và `collections`.

## Bắt đầu

Sau khi cài đặt Python 3 và Git, tải repository về máy:

```bash
git clone https://github.com/caoban123/Programming-for-data-science.git
cd Programming-for-data-science
```

Cài đặt và mở JupyterLab:

```bash
python -m pip install jupyterlab
python -m jupyterlab
```

Mở tệp `.ipynb` tương ứng trong JupyterLab và chạy các ô theo thứ tự. Giữ nguyên vị trí thư mục `Data/` để các đường dẫn tương đối trong notebook hoạt động. Đọc hướng dẫn của từng bài để chuẩn bị dữ liệu và thư viện cần thiết.

## Cách sử dụng repository

1. Đọc yêu cầu của bài thực hành hoặc bài tập trước khi viết mã.
2. Ghi lại cách tiếp cận, giả định và nhận xét bằng các ô Markdown.
3. Kiểm tra kết quả bằng các ví dụ và bộ kiểm thử được cung cấp.
4. Khởi động lại kernel và chạy toàn bộ notebook trước khi lưu hoặc nộp bài.
5. Commit những thay đổi có ý nghĩa với thông điệp mô tả rõ nội dung.

Khi bổ sung dữ liệu, sử dụng đường dẫn tương đối và loại bỏ thông tin định danh cá nhân trước khi công khai. Tài liệu và bài làm trong repository phục vụ việc học tập, ôn tập và theo dõi tiến độ cá nhân.
