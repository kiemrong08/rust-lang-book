# Các tính năng nâng cao

Chúng ta đã đi được quãng đường dài. Giờ đây, chúng ta đã học được rằng 99% các
thứ chúng ta cần để biết khi viết Rust. Trước khi chúng ta làm một project nữa
trong Chapter 20, hãy nói về một vài điều mà bạn có thể bắt gặp trong 1% thời
gian. Hãy tự do bỏ qua chương này và trở lại nó một khi bạn gặp các điều đó
trong cuộc đời, các tính năng chúng ta sẽ học để sử dụng ở đây là hữu dụng trong
các tính huống rất cụ thể. Chúng ta không muốn để các tính năng này ra ngoài,
nhưng bạn không thể tìm thấy cho mình cách bắt gặp chúng thường xuyên.

Trong chương này, chúng ta sẽ bao gồm các kiến thức sau:

* Unsafe Rust: dùng khi bạn cần phải opt out một vài sự bảo vệ của Rust và nói
  cho compiler là bạn sẽ chịu trách nhiệm cho việc thay đổi các các bảo vệ đó.
* Advanced Lifetimes: Các cấu trúc lifetime bổ sung cho các tình huống phức tạp
* Advanced Traits: Các kiểu liên đới, các kiểu tham số mặc định, cú pháp đầy đủ,
  supertraits, và mẫu newtype liên quan tới traits
* Các kiểu nâng cao: nói thêm về mẫu newtype, type aliases, "never" type, và các
  kiểu kích cỡ động.
* Các hàm nâng cao và Closures: các con trỏ hàm và returning closures

Nó là một bộ đầy đủ các tính năng của Rust với một vài thứ cho bất cứ ai! Giờ hãy đi sâu vào nó!
