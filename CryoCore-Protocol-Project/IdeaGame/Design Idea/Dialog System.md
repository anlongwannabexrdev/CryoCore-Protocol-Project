### **1. Loại Dialog System**

#### a. **Branching Dialog System (Hệ thống hội thoại phân nhánh)** (Ưu tiên lựa chọn này) 

Người chơi có thể chọn các tùy chọn khác nhau trong hội thoại, dẫn đến các phản hồi hoặc kết quả khác nhau. Điều này phù hợp để:

- Thể hiện lựa chọn đạo đức (moral choices).
- Tạo cảm giác nhập vai sâu sắc hơn.
- Mở khóa hoặc đóng lại các nhánh câu chuyện tùy vào hành động của người chơi.

 **Note Link Ink Unity Integration trên Unity Asset Store:** https://assetstore.unity.com/packages/tools/integration/ink-integration-for-unity-60055 
#### b. **Linear Dialog System (Hệ thống hội thoại tuyến tính)**

Các hội thoại diễn ra theo một trình tự cố định, thường dùng trong các phân đoạn cốt truyện quan trọng hoặc khi cần truyền tải nội dung chính xác.

#### c. **Dynamic Dialog System (Hệ thống hội thoại động)**

Hội thoại thay đổi dựa trên hành động hoặc tiến trình của người chơi:

- NPC phản ứng dựa trên trang bị hiện tại của người chơi.
- Các đoạn hội thoại bị khóa hoặc mở ra tùy thuộc vào các nhiệm vụ đã hoàn thành.

#### d. **Environmental Dialog (Hội thoại môi trường)**

Các đoạn hội thoại được kích hoạt khi người chơi tương tác với môi trường (nhặt đồ, phát hiện thông tin, v.v.).

---

### **2. Yếu tố Thiết Kế Hội Thoại**

#### a. **Cách Hiển Thị Hội Thoại**

- **Subtitle System**: Hiển thị lời thoại dưới dạng văn bản trên màn hình hoặc khu vực VR HUD.
- **Interactive 3D Bubbles**: Hội thoại xuất hiện dưới dạng bong bóng trong không gian VR, gần nhân vật hoặc đối tượng đang nói.
- **Holographic Interface**: Một màn hình ảo hiển thị hội thoại, mang phong cách Sci-Fi.

#### b. **Voice Acting vs. Text-Only**

- **Voice Acting**: Tạo cảm giác sống động hơn, nhưng cần đầu tư thêm vào sản xuất âm thanh.
- **Text-Only**: Tiết kiệm hơn, nhưng có thể kết hợp với hiệu ứng âm thanh để tạo cảm xúc.

#### c. **Chọn Phong Cách Ngôn Ngữ**

- **Kỹ thuật và bí ẩn**: Dùng cho các NPC liên quan đến HBS hoặc Syndraks, thể hiện sự khoa học và xa lạ.
- **Đời thường và mạnh mẽ**: Dùng cho các thành viên kháng chiến, thể hiện sự quyết liệt và gần gũi.
- **Triết lý hoặc khó hiểu**: Dùng cho các NPC ngoài hành tinh hoặc các máy móc có AI tiên tiến.

---

### **3. Gợi Ý Kịch Bản Hội Thoại**

#### a. **NPC Resistance Leader**

**Ngữ cảnh**: Zowie gặp thủ lĩnh của The Last Dawn để xin gia nhập.

- NPC: _"Chúng tôi không tin bất cứ ai từng làm việc cho HBS. Hãy chứng minh sự trung thành của anh trước khi bàn chuyện hợp tác."_
- Tùy chọn:
    - **1**: _"Tôi sẵn sàng làm bất cứ điều gì để sửa chữa sai lầm của mình."_
        - **Phản hồi**: _"Tốt, chúng tôi có một nhiệm vụ mà anh có thể làm ngay..."_
    - **2**: _"Tôi không cần chứng minh gì cả. Cứ xem hành động của tôi thì biết."_
        - **Phản hồi**: _"Thái độ của anh không giúp được gì. Đừng phí thời gian của chúng tôi."_
    - **3**: _[Im lặng]_
        - **Phản hồi**: _"...Tôi đoán anh cần thời gian để quyết định. Quay lại khi anh sẵn sàng."_

#### b. **AI Syndrak Terminal**

**Ngữ cảnh**: Zowie hack một hệ thống của Syndrak và AI trong đó bắt đầu hội thoại.

- **AI**: _"Bạn không được phép truy cập. Xác nhận mã sinh trắc học."_
- Tùy chọn:
    - **1**: _"Chỉ cần cho tôi thông tin, tôi không muốn phá hủy bạn."_
        - **Phản hồi**: _"Dữ liệu đã được bảo vệ. Kích hoạt chế độ tự hủy trong 10 giây."_
    - **2**: _[Sử dụng mã giả]_
        - **Phản hồi**: _"Mã hợp lệ. Truy cập dữ liệu đang được mở khóa..."_
    - **3**: _[Hack hệ thống một cách thô bạo]_
        - **Phản hồi**: _"Cảnh báo: Hệ thống an ninh đang được kích hoạt."_ (Kích hoạt cuộc tấn công bảo vệ).

#### c. **Alien Syndrak NPC**

**Ngữ cảnh**: Một NPC Syndrak bị giam giữ, đưa ra thông tin để đổi lấy tự do.

- NPC: _"Ta có thể cung cấp thông tin về tổ của chúng ta. Nhưng đổi lại, ta muốn tự do."_
- Tùy chọn:
    - **1**: _"Hãy nói trước. Tự do của ngươi sẽ phụ thuộc vào giá trị thông tin."_
        - **Phản hồi**: _"Thông minh đấy, con người. Đây là tất cả những gì ta biết..."_
    - **2**: _"Tại sao ta phải tin ngươi?"_
        - **Phản hồi**: _"Ta không có lựa chọn nào khác, và ngươi cũng vậy."_
    - **3**: _"Ngươi không có quyền đòi hỏi."_
        - **Phản hồi**: _"Vậy thì hãy giết ta đi, và mãi mãi mất thông tin này."_

- Có 3 [[Ending]] chính xuôi theo mạch của câu chuyện