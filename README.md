<html>
  <body>
  	<div>
  		<h1>BÀI 7: HTML VÀ CẤU TRÚC TRANG WEB</h1>
  		<h2>LUYỆN TẬP</h2>
  		<hr>
  		<h3>Luyện tập 1: Tìm ví dụ về phần tử HTML không thể lồng, tức là không thể có quan hệ cha con trong cây thông tin của trang web.</h3> 
  		<p>_Các thẻ như h1, h2, h3, p,... không thể lồng </p>
        <p>_Các thẻ như b, u, i, em, strong,...cũng không thể lồng </p>
        <h3>Luyện tập 2: Chọn một văn bản đơn giản soạn thảo tệp HTML để hiển thị nội dung văn bản đó. Vẽ cây thông tin các phần tử HTML của trang web vừa soạn thảo.</h3>
        <p>< !DOCTYPE html ></p>
        <p>< html></p>
        <p>  < head></p>
        <p>    < meta charset="utf-8" ></p>
        <p>    < title>Luyện tập Bài 2< /title></p>
        <p>  < /head></p>
        <p>  < body></p>
        <p>    < h3 align="center">Ca dao Việt Nam< /h3></p>
        <p>    < p align="center"></p>
        <p>    Trong đầm gì đẹp bằng sen< br></p>
        <p>    Lá xanh bông trắng lại chen nhụy vàng< br></p>
        <p>    Nhụy vàng bông trắng lá< br></p>
        <p>    Gần bùn mà chẳng hôi tanh mùi bùn</p>
        <p>    < /p></p>
        <p>  < /body></p>
        <p>< /html></p>
        <h2>VẬN DỤNG</h2>
        <hr>
        <h3>Vận dụng 1: Em hãy tìm trên mạng các trang web hỗ trợ soạn thảo HTML trực tuyến.</h3>
        <p>Một số trang web phổ biến cung cấp các công cụ soạn thảo HTML trực tuyến:</p>
        <p>JSFiddle (https://jsfiddle.net/).</p>
        <p>CodePen US Bin (https://jsbin.com/).</p>
        <p>Repl.it (https://replit.com/).</p>
        <h3>Vận dụng 2: Sử dụng phần mềm soạn thảo HTML và soạn thảo trang web có nội dung như Hình 7.7. Lưu ý rằng thẻ < img> với tính tăng thể hiện ảnh trên trang web có cú pháp: < img src = "tên tệp ảnh">,trong đó “tên tệp ảnh” chính là đường dẫn của tệp hình ảnh cần đưa lên trang.</h3>
        <p>< !DOCTYPE html></p>
        <p>< html></p>
        <p>  < head></p>
        <p>    < meta charset="utf-8"></p>
        <p>    < title>Lịch sử phát triển HTML< /title></p>
        <p>  < /head></p>
        <p>  < body></p>
        <p>     < h1>< strong>Lịch sử phát triển HTML</ strong>< /h1></p>
        <p>     < p>Các chuẩn HTML của trang web hiện nay được nhà vật lý Tim Berners-Lee đưa ra lần đầu tiên vào những năm 1990 của thế kỷ XX tại trung tâm vật lý hạt nhân CERN.< /p></p>
        <p>     < p>Ý tưởng ban đầu của Berners-Lee là muốn thiết lập một chuẩn chung để thể hiện và chia sẻ các văn bản có thể trao đổi bên trong cơ quan CERN.< /p></p>
        <p>     < p>Hình ảnh sau là sơ đồ thông tin mà Tim Berners-Lee đưa ra lần đầu tiên để minh họa cho ý tưởng của mình. Trong sơ đồ này lần đầu tiên xuất hiện cụm từ “hypertext” (siêu văn bản).< /p></p>
        <p>     <!-- Bạn cần thay thế 'đường_dẫn_đến_hình_ảnh_của_bạn' bằng đường dẫn thực tế hoặc URL của hình ảnh mà bạn muốn chèn -->
        <p>     < img src="đường_dẫn_đến_hình_ảnh" alt="Sơ đồ Hypertext của Tim Berners-Lee" style="max-width: 100%; height: auto;"></p>
        <p>     < p>Phiên bản đầu tiên của HTML được thiết lập vào cuối năm 1991 mang tên “các thẻ HTML” văn bản này do chính Tim Berners-Lee biên soạn.</ p></p>
        <p>     < p>Từ đó các phiên bản tiếp theo của HTML lần lượt ra đời cùng với sự phát triển của công nghệ internet.< /p></p>
        <p>     < p>Phiên bản hiện tại là HTML5, ra đời năm 2014.< /p></p>
        <p>  < /body></p>
        <p>< /html></p>
    </div>
  </body>
</html>
<html>
  <body>
  	<div>
  		<h1>BÀI 8: ĐỊNH DẠNG VĂN </h1>
  		<h2>LUYỆN TẬP</h2>
  		<hr>
  		<h3>Luyện tập 1: Hãy sửa lại phần tử sau để làm nổi bật ý chính của câu: < p> thẻ strong vào thẻ em được sử dụng để nhấn mạnh vào nội dung trong phần tử. Thẻ B chỉ có tác dụng in đậm văn bản < p></h3> 
  		<p>Ý  chính của câu là làm nổi bật sự khác nhau về ý nghĩa của 3 thẻ. Do vậy nên đặt thêm định dạng kiểu chữ hoặc chỉnh màu nổi bật cho các tên thẻ và hai từ "nội dung" và "in đậm".</p>
      <p>< p> Thẻ < b>< span style="color:red">strong< /span>< /b> và thẻ < b>< span style="color:red">em< /span>< /b> được sử dụng để nhấn mạnh vào < b>< span style="color:blue">nội dung< /span>< /b>trong phần tử. </p>
      <P>Thẻ < b>< span style="color:red">b< /span>< /b> chỉ có tác dụng < b>< span style="color: blue">in đậm< /span>< /b> văn bản.< /p></P>
      <h3>Luyện tập 2: Trình bày đoạn văn bản sau bằng mã HTML:</h3>
      <p>< p>INTERNET TỐC ĐỘ CAO< /p></p>
      <p>< p>< i>Dịch vụ Internet tốc độ cao là dịch vụ Internet cáp quang chất lượng cao, ổn định, giá cả hợp lí.< /i>< /p></p>
      <p>< p>< strong>Các tính năng nổi bật:< /strong>< /p> </p>
      <p>< p>Tốc độ siêu cao từ 150 MBps trở lên< /p></p>
      <p>< p>Lắp đặt nhanh chóng trong 24h< /p></p>
      <p>< p>Phù hợp với cá nhân/Hộ gia đình< /p></p>
      <p>< p>Tặng Modem 2 băng tần< /p></p>
      <p>< p>Miễn phí lắp đặt< /p></p>
      <p>< p>Hỗ trợ 24/7< /p></p>
      <h2>VẬN DỤNG</h2>
      <hr>
      <h3>Vận dụng 1: Hãy chỉ ra các bước cần thực hiện để sử dụng một màu cụ thể trong bức ảnh làm màu cho tiêu đề một bài thơ.</h3>
      <p>Các bước cần thực hiện:</p>
      <p>• Bước 1. Mở ảnh bằng phần mềm có chức năng chỉnh sửa (GIMP,
Paint, ...)</p>
      <p>• Bước 2. Sử dụng công cụ Color Picker và nháy chuột vào vị trí muốn lấy màu</p>
      <p>• Bước 3. Nháy chuột vào màu mới được chọn để xem giá trị RGB của màu</p>
      <p>• Bước 4. Sử dụng giá trị RGB của màu đã chọn để thiết lập màu cho tiêu đề bài thơ bằng đặc tính color trong thuộc tính style</p>
      <h3>Vận dụng 2: Hãy đưa ra các định dạng một đoạn văn bản để được kết quả như sau:</h3>
      <img src="images/vandung2.png"></p>  
      <p>< p style="font-size:150%" ></p>
      <p>0< sup>0< sup>0< sup>0< sup>0< /sup>0< /sup>0< /sup>0< /sup></p>
      <p>0< sup>0< sup>0< sup>0< sup>0< /sup>0< /sup>0< /sup>0< /sup></p>
      <p>0< sup>0< sup>0< sup>0< sup>0< /sup>0< /sup>0< /sup>0< /sup></p>
      <p>0< sup>0< sup>0< sup>0< sup>0< /sup>0< /sup>0< /sup>0< /sup>< /p></p>
        <p>  < /body></p>
        <p>< /html></p>
    </div>
  </body>
</html>
