# Các tính năng nâng cao

Chúng ta đã đi được quãng đường dài. Giờ đây, chúng ta đã học được rằng 99% các
thứ chúng ta cần để biết khi viết Rust. Trước khi chúng ta làm một project nữa
trong Chapter 20, hãy nói về một vài điều mà bạn có thể bắt gặp trong 1% thời
gian. Hãy tự do bỏ qua chương này và trở lại nó một khi bạn gặp các điều đó
trong cuộc đời, các tính năng chúng ta sẽ học để sử dụng ở đây là hữu dụng trong
các tính huống rất cụ thể. Chúng ta không muốn để các tính năng này ra ngoài,
nhưng bạn không thể tìm thấy cho mình cách bắt gặp chúng thường xuyên.

In this chapter, we're going to cover:

* Unsafe Rust: for when you need to opt out of some of Rust's guarantees and
  tell the compiler that you will be responsible for upholding the guarantees
  instead
* Advanced Lifetimes: Additional lifetime syntax for complex situations
* Advanced Traits: Associated Types, default type parameters, fully qualified
  syntax, supertraits, and the newtype pattern in relation to traits
* Advanced Types: some more about the newtype pattern, type aliases, the
  "never" type, and dynamically sized types
* Advanced Functions and Closures: function pointers and returning closures

It's a panoply of Rust features with something for everyone! Let's dive in!
