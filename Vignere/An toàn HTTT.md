# An toàn HTTT
Chuẩn bị
--------

bản mã: “HopLopNgayThuNam”

Khóa “bimat”

Biến đổi hết các ký tự chữ to ở bản mã thành chữ bé sau đó đánh số cho từng ký tự A → Z tương đương với các số từ 0→25. 

Khóa được lặp lại sao cho bằng với độ dài bản rõ

Ta có dãy sau

A = {7, 14, 15, 11, 14, 15, 13, 6, 0, 24, 19, 7, 20, 13, 0, 12}

B = {1, 8, 12, 0, 19, 1, 8, 12, 0, 19, 1, 8, 12, 0, 19, 1}

Mã hóa
------

Ta định nghĩa hàm f(x) như sau:

\\(f(X, Y) = (x+y)\\bmod{26}\\)

Như vậy f(A, B) = {8, 22, 1, 11, 7, 16, 21, 18, 0, 17, 20, 15, 6, 13, 19, 13}

Biến đổi thành chữ sẽ là: "iwblhqvsarupgntn"

Giải mã
-------

Biến đỏi bản mã ở trước thành số, ta có:

C = {8, 22, 1, 11, 7, 16, 21, 18, 0, 17, 20, 15, 6, 13, 19, 13}

Ta định nghĩa hàm g(x) như sau:

\\(g(X, Y) = (X - Y) \\bmod26\\)

\\(g(f(X, Y), Y) = X\\)

Với X là bản mã còn Y là khóa

Như vậy g(Z, Y) = {7, 14, 15, 11, 14, 15, 13, 6, 0, 24, 19, 7, 20, 13, 0, 12}

Biến đỏi thành chữ ta sẽ được: “hoplopngaythunam” là bản rõ ban đầu.