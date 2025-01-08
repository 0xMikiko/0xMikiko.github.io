# Bug Bounty Hunting Certification

 
## JavaScript Deobfuscation

#### Code Obfuscation
- [Beautify Tools - JavaScript Obfuscator](http://beautifytools.com/javascript-obfuscator.php)

#### Running JavaScript Code
- [JSConsole](https://jsconsole.com)

#### Minifying JavaScript Code
- [JavaScript Minifier](https://javascript-minifier.com/)

#### Advanced Obfuscation
- [JavaScript Obfuscator](https://obfuscator.io)

#### Beautify JavaScript
- [Prettier Playground](https://prettier.io/playground/)

#### Deobfuscate JavaScript
- [unPacker](https://matthewfl.com/unPacker.html)

## Cross-Site Scripting (XSS)

XSS là gì?
Các ứng dụng web thường nhận mã HTML từ máy chủ và hiển thị nó trên trình duyệt. Khi ứng dụng không kiểm tra hoặc làm sạch đúng cách đầu vào của người dùng, kẻ tấn công có thể chèn mã JavaScript độc hại. Khi người dùng khác xem trang đó, mã độc sẽ được thực thi trên trình duyệt của họ.

XSS chỉ tác động lên phía client (trình duyệt) mà không trực tiếp ảnh hưởng đến máy chủ. Tuy nhiên, do mức độ phổ biến cao, XSS được xem là rủi ro trung bình, cần được phát hiện và xử lý để giảm thiểu nguy cơ.

| Loại XSS                 | Mô tả                                                                                           | Ví dụ                     |
|--|--|--|
| **Stored  XSS**  | Loại nghiêm trọng nhất, xảy ra khi dữ liệu người dùng được lưu trữ trên cơ sở dữ liệu backend và hiển thị lại. | Bài viết, bình luận       |
| **Reflected XSS**| Xảy ra khi dữ liệu người dùng được hiển thị ngay trên trang sau khi xử lý bởi server mà không lưu trữ.       | Kết quả tìm kiếm, thông báo lỗi |
| **DOM-based XSS** | Xảy ra khi dữ liệu người dùng được hiển thị trực tiếp trên trình duyệt và xử lý hoàn toàn phía client.        | Tham số HTTP, anchor tags |