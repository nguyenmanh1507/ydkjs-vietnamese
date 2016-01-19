# You Don't Know JS

---

## Preface

Tôi chắc rằng bạn đã được nhận thấy, nhưng "JS" trong title của series sách này không phải là từ viết tắt được sử dụng nguyền rủa JavaScript, _though cursing at the language's quirks is something we can probably all identify with_!

Từ những ngày đầu tiên của web, JavaScript đã trở thành công nghệ nền tảng cái mà hướng vào trải nghiệm tương tác xung quanh nội dung chúng ta tiêu thụ. Trong khi chuột nhấp nháy và pop-up thông báo phiền phức có thể là nơi JavaScript bắt đầu, gần 2 thập kỷ sau, công nghệ và khả năng của JavaScript đã phát triển nhiều lần về tầm quan trọng, và vài nghi ngờ tầm quan trọng của nó tại trái tim của nền tảng phẩn mềm hiện hữu rộng lớn nhất của thế giới: the web.

Nhưng như một ngôn ngữ, nó vĩnh viễn là mục tiêu cho rất nhiều lời chỉ trích, do một phần di sản của mình nhưng nhiều hơn là do triết lý thiết kế của nó. Ngay cả tên gọi đã gợi lên, như Brendan Eich đã nói, "đứa em khờ dại" đặt cạnh ông anh trường thành hơn "Java". Nhưng tên gọi chỉ là tại nạn về mặt chính sách và tiếp thị. Hai ngôn ngữ này rất khác nhau theo nhiều cách quan trọng. "JavaScript" liên quan tới "Java" như là "Carnival" liên quan tới "Car".

Bởi vì JavaScript mượn các khái niệm và cú pháp từ nhiều ngôn ngữ, bao gồm _proud C-style procedural roots as well as subtle, less obvious Scheme/Lisp-style functional roots_, nó cực kỳ dễ tiếp cận đối với một lượng lớn developer, kể cả với người ít kinh nghiệm lập trình. "Hello World" của JavaScript rất đơn giản và dễ dàng trở nên quen thuộc trong lần tiếp xúc đầu.

Trong khi JavaScript có thể là một trong những ngôn ngữ dễ nhất để bắt đầu, sự lập dị của nó làm cho việc làm chủ ngôn ngữ _a vastly less common occurrence_ so với nhiều ngôn ngữ khác. Nơi cần hiểu biết khá là sâu về ngôn ngữ như C hoặc C++ để viết chương trình quy mô lớn, full-scale production JavaScript có thể, và thường làm, hầu như không làm xước bề mặt của cái mà ngôn ngữ có thể làm.

Các khái niệm phức tạp cái mà bắt rễ sâu vào ngôn ngữ có xu hướng lướt bản thân chúng theo cách dường như đơn giản, như là truyền các function như callback, cái khuyến khích JavaScript developer chỉ sửa dụng ngôn ngữ như vậy và không quá lo lắng về cái xảy ra bên dưới.

Nó đồng thời là một ngôn ngữ đơn giản, dễ sử dụng có sức hấp dẫn lớn, và là một bộ sưu tập phức tạp và nhiều sắc thái của cơ chế ngôn ngữ cái mà không nghiên cứu cẩn thận sẽ không thực sự hiểu kể cả đối với các JavaScript developer nhiều kinh nghiệm.

Nằm trong các nghịch lý của JavaScript, gót chân Achilles của ngôn ngữ, thử thách chúng ta hiện nay đang giải quyết. Bởi vì JavaScript có thể được sử dụng mà không cần hiểu thực sự, hiểu biết về ngôn ngữ cũng không bao giờ đạt được.

---

## Nhiệm vụ

Nếu tại mọi điểm chúng ta gặp phải bất ngờ hoặc bực mình trong JavaScript, phản hồi của bạn la thêm nó vào blacklist, như là một thói quen để làm, bạn sẽ sớm rơi vào vỏ rỗng của sự phong phú của JavaScript.

Trong khi tập con này đã được đặt tên nổi tiếng "The Good Parts", tôi khẩn cầu bạn, người đọc, thay vào nó xem nó là "The Easy Parts", "The Safe Parts", hoặc thậm chí "The Incomplete Parts".

Series sách _You Don't Know JavaScript_ cung cấp thử thách trái ngược: học và hiểu sâu tất cả JavaScript, thậm chí "The Tough Parts".

Ở đây, chúng ta giải quyết xu hướng đứng đầu của JS developer là học "vừa đủ", không bắt bản thân họ học chính xác như thế nào và tại sao ngôn ngữ hành xử như vậy. Xa hơn, chúng ta tránh lời khuyên chung là rút lui khi con đường gập ghềnh.

Tôi không phải tự thỏa mãn, bạn cũng không nên như vậy, khi dừng lại ở một thứ gì đó _just works_, và không biết thực sự tại sao. Tôi đưa bạn vào cuộc hành trình vào con đường ít người qua lại và bao bọc tất cả cái mà JavaScript làm và có thể làm. Với kiến thức này, không công nghệ, framework, từ viết tắt phổ biến một tuần nào vượt ngoài tầm hiểu biết của bạn.

Những quyển sách này mỗi quyển nói về các phần core cụ thể của ngôn ngữ cái mà hầu hết thường bị hiểu sai hoặc hiểu chưa sâu, và đi sâu và tìm hiểu sâu sắc về chúng. Bạn nên đi xa hơn việc đọc với niềm tin vững chắc vào sự hiểu biết của bạn, không chỉ là lý thuyết, mà còn là thực hành "cái bạn cần biết".

JavaScript bạn biết lúc này có lẽ là các phần được truyền lại cho bạn bởi những người khác, những người đã bị đốt cháy bởi sự hiểu biết chưa trọn vẹn. 

---

## Tổng kết

JavaScript rất tuyệt vời. Nó dễ dàng học từng phần nhưng khó hơn nhiều khi học toàn bộ (hoặc thậm chí vừa đủ). Khi developer gặp phải bối rối, họ thường đổ lỗi cho ngôn ngữ thay vì sự thiếu kiến thức của họ. Các quyển sách này nhằm sửa điều đó, tạo cảm hứng cao cho ngôn ngữ bạn có bây giờ, và nên hiểu sâu.

Note: Nhiều ví dụ trong quyển này giả sử môi trường JavaScript engine hiện đại, như là ES6. Một vài code có thể không hoạt động như mô tả nếu chạy ở engine cũ (trước ES6).