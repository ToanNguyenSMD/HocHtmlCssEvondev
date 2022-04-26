1. để copy nhanh 1 dòng: ấn shift+ alt + dấu mũi tên xuống
2. để di chuyển 1 dòng code: ấn alt + mũi tên lên xuống để di chuyển
3. để sửa nội dung giống, ví dụ sửa các class có tên demo thành title: chọn chữ demo, rồi chọn Ctrl + D (window) hoặc CMD + D (macbook), rồi sửa 
4.  
  - để tạo nhanh n thẻ li trong thẻ ul: gõ ul>li*n rồi nhấn tab, dấu > có nghĩa là tạo <li> là con của <ul>
  - để tạo nhanh 5 thẻ <li> với nội dung là item ở trong đó: ul>li*5{item}
  - để tạo nhanh 5 thẻ <li> với class là item ở trong đó: ul>li*5.item
  - để tạo nhanh 5 thẻ <li> với nội dung là item1 - item5: ul>li*5{item$}, dấu $ sẽ chạy từ 1 đến hết
  - để tạo nhanh 5 thẻ <li> với class là item1 - item5: ul>li*5.item$, dấu $ sẽ chạy từ 1 đến hết
5. để tạo các thể cùng cấp thì dùng đấu +. ví dụ: div+p+h2, để thêm class thì thêm .tenclass, để thêm thẻ con phía trong thì >thẻ con


bài 34 -- PHÂN BIỆT OPACITY 0, VISIBILITY HIDDEN, DISPLAY NONE
<!-- 
-opacity: 0: vẫn chiếm diện tích, có thể nhấn vô được
-visibility: hidden: vẫn chiếm diện tích, nhưng không nhấn vô được
-display: none: biến mất hoàn toàn trên trang web, k chếm diện tích, k nhấn vô được 

-->

BÀI 37 ĐỘ ƯU TIÊN CSS 
 <!-- độ ưu tiên trong css 

tags < class < ID < inline style < !important.
khi rê chuột vào các class, tag trong vscode sẽ hiển thị độ uu tiên
tags là: 0 0 1,
class là: 0 1 0,
id là: 1 0 0
nó sẽ so sánh theo cột,từ trái qua phải, gặp 1 ở cái nào thì cái đó ưu tiên hơn -->

BÀI 46 POSITION ABSULATE

 <!-- /* overlay theo chieu ngang */
  /* top: 0;
  left: 0;
  right: 0;
  width: auto; */

   /* overlay theo chieu doc */
  height: 100%;
  top: 0;
  bottom: 0;
  z-index: 1; -->

BÀI 47 POSITION FIXED
<!-- 
 khi để postion fixed thì vị trí đi theo thẻ body, tránh dùng chung fixed và transform 
  -->

BÀI 55 PSEUDO BEFORE AND AFTER
 <!--
 currentColor: lấy giá trị màu theo thuộc tính color của nó hoặc color của thằng cha chứa nó;
 
 
  -->

BÀI 65 THỰC HANH FLEX BOX

<!-- 
  để truyền số âm trong hàm calc:
  calc(-1*100px)

 -->

BÀI 70 THỰC HÀNH DROPDOWN
<!-- 
  Khi dùng flex, để 1 element dịch về bên phải thì dùng margin left: auto

 -->