MÔN HỌC: PHÁT TRIỂN ỨNG DỤNG TRÊN THIẾT BỊ DI ĐỘNG - TEE0419 <br>
BÀI TẬP LỚN:<br>
A. Viết phần mềm trên công cụ Mit App inventor ( xây dựng 1 bài toán đơn giản gồm 3 screen và button gọi sang các screen)<br>
1. Truy cập: https://appinventor.mit.edu/ và đăng nhập tài khoản<br>
2. Tạo project:<br>
  <img width="1889" height="890" alt="image" src="https://github.com/user-attachments/assets/9da22ca3-93df-4e89-ab74-159ceab595e3" /><br>
3. Thêm 2 màn hình nữa:<br>
  <img width="792" height="827" alt="image" src="https://github.com/user-attachments/assets/e70e6c03-c3cb-4a23-86f8-245c0ae5c324" /><br>
4. Tại Screen 1:<br>
  - Kéo thả thanh Label ở mục user interface bên trái vào Screen1, sửa đổi thuộc tính text trong cột Properties bên phải của Label thành nội dung cần hiển thị:<br>
    <img width="1645" height="910" alt="image" src="https://github.com/user-attachments/assets/c0328ec2-c3de-4f6f-ad76-35915610b597" /><br>
  - Kéo thả 2 button vào dưới thanh Label và sửa mục text của 2 button:<br>
    + Text button 1: "Giải toán" để chuyển sang Screen giải toán<br>
      <img width="1566" height="800" alt="image" src="https://github.com/user-attachments/assets/bc84ffd9-51d7-479f-9d9d-49e5b2d3b339" /><br>

    + Text button 2: "Xem web" để chuyển sang Screen3 sử dụng webviewer để xem trang web có sẵn<br>
     <img width="1634" height="861" alt="image" src="https://github.com/user-attachments/assets/df40942d-9aae-43f4-b493-80db1e6f88e0" /><br>

5. Tại Screen 2:<br>
   - Kéo thả 2 thanh textbox vào Screen2 và tích vào ô NumberOnly ở 2 textbox để chỉ nhập số khi tính toán:<br>
     <img width="1620" height="854" alt="image" src="https://github.com/user-attachments/assets/de1d4273-491e-49b3-ab48-cac3d67db681" /><br>
  - Kéo 1 thanh button vào dưới 2 thanh textbox để khi bấm nút sẽ thực hiện tính toán phép chia<br>
  - Kéo 1 thanh label để hiển thị kết quả:<br>
    ( Cấu trúc Screen 2):<br>
    <img width="1037" height="797" alt="image" src="https://github.com/user-attachments/assets/3c7df739-2bcb-4d8a-be28-b70da0bf08c7" /><br>

  
6. Tại Screen3:<br>
   - Kéo link kiện Webviewer vào màn hình và thêm url trang web có sẵn vào mục HomeUrl:<br>
     <img width="1918" height="854" alt="image" src="https://github.com/user-attachments/assets/547a316c-6746-451d-aba6-b9a362715332" /><br>
7. Ghép các khối Blocks logic điều hướng và tính toán:<br>
- Chuyển sang tab Block:<br>
  <img width="1619" height="868" alt="image" src="https://github.com/user-attachments/assets/263e599e-07d5-43c4-92c4-0c5c78fb0542" /><br>
  Tại Screen1:<br>
- Bấm vào Button1 ở mục bên trái tab Block --> chọn "When button1 .click do"<br>
  <img width="1919" height="919" alt="image" src="https://github.com/user-attachments/assets/b855b7d8-3fce-4f22-9de0-b1f2c217470e" /><br>
- kéo khối open another screen with screenName gắn vào bên trong khối when Button1.Click:<br>
<img width="654" height="222" alt="image" src="https://github.com/user-attachments/assets/349e326f-e89f-413d-897c-09f364ce4ac9" /><br>

- Copy khối button 1 và đổi button1 thành button2:<br>
  <img width="710" height="314" alt="image" src="https://github.com/user-attachments/assets/9c16fead-f2ea-4cb5-9387-87a9ab682ab4" /><br>
  Tại Screen2:<br>
 - Bấm vào Button1 ở cột trái, kéo khối when Button1.Click do ra màn hình:<br>
- Bấm vào Label1, tìm và kéo khối màu xanh lá: set Label1.Text to gắn vào trong sự kiện click của nút bấm<br>
- Bấm vào mục Math, kéo khối phép cộng [  ] + [  ] gắn vào đuôi của khối set Label1.Text to<br>
- Bấm vào TextBox1, kéo khối TextBox1.Text gắn vào ô trống thứ nhất của phép cộng.<br>
- Bấm vào TextBox2, kéo khối TextBox2.Text gắn vào ô trống thứ hai của phép cộng.<br>
  <img width="902" height="187" alt="image" src="https://github.com/user-attachments/assets/8193f57b-b36c-48f3-9f62-549784a88c89" /><br>

  Tại Screen3: đã gán url của trang web có sẵn nên không cần thêm block nào<br>
8. Chạy thử ứng dụng:<br>
 - Lên thanh menu trên cùng, chọn Connect -> AI Companion. Một mã QR và mã ký tự sẽ hiện ra.<br>
   <img width="1917" height="917" alt="image" src="https://github.com/user-attachments/assets/3d03fd2e-c34a-4aa2-857e-88c3c25d6924" /><br>
<img width="493" height="500" alt="image" src="https://github.com/user-attachments/assets/42b4ad97-9002-4b90-997f-989d9e048b79" /><br>
- Trên điện thoại, bạn cài ứng dụng MIT AI2 Companion (có sẵn trên CH Play/App Store).<br>
- Mở app trên điện thoại lên, chọn Scan QR Code và quét mã trên màn hình máy tính.<br>
  <img width="1920" height="2560" alt="image" src="https://github.com/user-attachments/assets/a146a607-666b-48fe-afc0-76ece63c7262" /><br>
  <img width="1920" height="2560" alt="image" src="https://github.com/user-attachments/assets/5e6b73be-7617-4e3a-acc4-ebb34258bb47" /><br>
  <img width="646" height="779" alt="image" src="https://github.com/user-attachments/assets/cb739d6e-7e3c-44d2-9e13-b20b8ddfcd69" /><br>
9. Giải thích ý nghĩa của Block:<br>
- Bản chất của việc kéo thả Block<br>
Trực quan hóa mã nguồn: Về bản chất, mỗi khối block là một "đoạn code" (như cú pháp Java, C#) đã được bao bọc dưới dạng một mảnh ghép hình học có màu sắc riêng biệt theo từng nhóm chức năng (Vòng lặp, Điều kiện, Toán học, Biến...).<br>

Ràng buộc logic vật lý: Các block được thiết kế các mấu lồi/lõm (ngàm kết nối) tương ứng với cấu trúc cú pháp của lập trình. Chúng chỉ có thể khớp chặt vào nhau khi đúng logic và đúng kiểu dữ liệu (ví dụ: không thể nhét một khối chữ "Text" vào ngàm tính toán của phép cộng "Math"). Khi lắp ghép chính xác, phần mềm sẽ phát ra tiếng "tách" trực quan.<br>

- Ưu điểm so với viết code truyền thống (Text-based)<br>
Loại bỏ lỗi cú pháp: Người học hoàn toàn không phải lo lắng về việc gõ thiếu dấu chấm phẩy ;, thiếu dấu ngoặc { }, hay gõ sai chính tả tên hàm — những lỗi kinh điển khiến code truyền thống bị lỗi không chạy được.<br>

Học tư duy nhanh hơn: Giúp người mới bắt đầu tập trung 100% vào việc phát triển tư duy thuật toán (App hoạt động thế nào? Khi nào bấm nút thì làm gì?) thay vì mất thời gian học thuộc lòng các từ khóa lập trình phức tạp.<br>

Trực quan và dễ nhớ: Màu sắc của các block giúp người lập trình dễ dàng nhận diện vùng quản lý dữ liệu bằng mắt thường nhanh hơn đọc một trang text đen trắng.<br>

- Nhược điểm<br>
Cồng kềnh khi dự án lớn: Khi ứng dụng phát triển phức tạp với hàng nghìn dòng lệnh, màn hình Blocks sẽ trở thành một "mê cung" khổng lồ, rất rối mắt, khó cuộn chuột để tìm kiếm, quản lý hoặc sửa lỗi.<br>

Bị giới hạn tính năng: Bạn chỉ có thể làm những gì mà các khối block có sẵn hỗ trợ. Việc muốn can thiệp sâu vào nhân hệ điều hành, tối ưu phần cứng hay viết thuật toán xử lý đồ họa nâng cao là bất khả thi nếu so với code thuần (Java/Kotlin).<br>

Tốc độ gõ chậm: Đối với lập trình viên chuyên nghiệp, việc dùng chuột kéo từng khối sẽ chậm hơn rất nhiều so với tốc độ gõ phím từ bàn phím.<br>


=============================================================================================================================================================<br>
B. Viết app sử dụng Android Studio<br>
### 1. AndroidManifest.xml & Cơ Chế Khai Báo Quyền (Permissions)<br>
* **AndroidManifest.xml mô tả gì?** Là file cấu hình bắt buộc nằm ở thư mục gốc, đóng vai trò như "sơ yếu lý lịch" của app nhằm mô tả: Cấu trúc các thành phần của app (`Activity`, `Service`, `Broadcast Receiver`), thông tin cơ bản (Package name, Icon, Tên app, Phiên bản SDK), và danh sách các quyền cần truy cập.<br>
* **Khai báo quyền thế nào?** Sử dụng thẻ `<uses-permission>` đặt trong thẻ `<manifest>` và nằm ngoài thẻ `<application>`.<br>
  * *Ví dụ xin quyền Camera:* `<uses-permission android:name="android.permission.CAMERA" />`<br>
* **Để làm gì?** Đây là cơ chế bảo mật của Android. App bắt buộc phải "xin phép" Hệ điều hành trước để được quyền can thiệp vào các tài nguyên hoặc dữ liệu nhạy cảm của thiết bị (Internet, Camera, Vị trí, Danh bạ). Nếu cố tình gọi code phần cứng mà không khai báo, app sẽ bị dừng đột ngột (`SecurityException`).<br>

### 2. Vòng Đời Ứng Dụng (Activity Lifecycle) & Hàm `onCreate()`<br>
* **Vòng đời ứng dụng là gì?** Là chuỗi các trạng thái của một màn hình (`Activity`) từ lúc khởi tạo đến khi bị đóng hoàn toàn, được quản lý qua các hàm callback tự động:<br>
  * `onCreate()` -> `onStart()` -> `onResume()`: Mở app, hiển thị giao diện và cho phép người dùng tương tác công khai.<br>
  * `onPause()` -> `onStop()`: Ẩn app (bấm nút Home, nhận cuộc gọi), màn hình bị che khuất một phần hoặc hoàn toàn, chuyển sang chế độ chạy ngầm.<br>
  * `onDestroy()`: Tắt hẳn app (bấm nút Back hoặc hệ thống giải phóng RAM), giao diện bị xóa hoàn toàn khỏi bộ nhớ.<br>
* **Tại sao có sẵn hàm `onCreate()`?** Vì đây là điểm khởi đầu (Entry Point) bắt buộc của một Activity. Hệ điều hành cần hàm này chạy đầu tiên (1 lần duy nhất) để làm nhiệm vụ nền móng: Nạp giao diện XML (`setContentView`), khởi tạo biến và liên kết các sự kiện ban đầu. Không có `onCreate`, màn hình không thể định hình và không thể chạy.<br>

### 3. Quản Lý Giao Diện XML & Tham Chiếu Tài Nguyên (Tránh Hardcode)<br>
* **Giao diện XML:** Định nghĩa bằng file XML trong thư mục `res/layout/` theo cấu trúc cây phân cấp (UI Design). Tách biệt hoàn toàn với logic xử lý bằng code Java.<br>
* **Lưu trữ thay vì Hardcode:** Các chuỗi chữ (text) hoặc giá trị cứng không được viết trực tiếp vào XML mà lưu tập trung tại file `strings.xml` (`res/values/strings.xml`).<br>
* **Cú pháp tham chiếu:**<br>
  * Trong file giao diện XML: `@string/ten_bien`<br>
  * Trong mã nguồn Java: `R.string.ten_bien`<br>
* **Ưu điểm của việc tham chiếu:**<br>
  * **Dễ bảo trì:** Sửa đổi câu chữ ở một nơi (`strings.xml`), hàng chục màn hình tự động cập nhật theo.<br>
  * **Tách biệt vai trò:** Giúp người thiết kế, lập trình viên và người dịch thuật làm việc độc lập.<br>
* **OS hỗ trợ tự động lấy giá trị theo LOCATION, LANGUAGE, THEME giúp app làm được gì?**<br>
  * Khi tạo các thư mục tài nguyên có hậu tố đặc biệt (như `values-vi/` cho tiếng Việt, `values-night/` cho chế độ tối), Android OS sẽ tự động nhận diện cấu hình máy để nạp đúng file tương ứng.<br>
  * **Kết quả:** Giúp app tự động đạt khả năng **Đa ngôn ngữ (Localization)** toàn cầu và hỗ trợ chế độ **Giao diện tối (Dark Mode)** mượt mà mà không cần viết thêm bất kỳ dòng lệnh điều kiện `if-else` nào.<br>

### 4. Đối Tượng Chứa (ViewGroup) & Quy Luật Sắp Xếp Giao Diện<br>
* **Đối tượng chứa (ViewGroup - Ví dụ `LinearLayout`):** Gom nhóm các đối tượng con lại và bắt chúng tuân theo một quy luật sắp xếp chung để hiển thị:<br>
  * **Chiều Dọc / Chiều Ngang:** Xác định qua thuộc tính `android:orientation="vertical"` (các phần tử con nằm xếp chồng kề nhau dọc từ trên xuống) hoặc `"horizontal"` (nằm kề nhau ngang từ trái sang phải).<br>
  * **Cơ chế Gravity:**<br>
    * `android:gravity`: Định vị vùng không gian của nội dung *bên trong* chính đối tượng đó (Ví dụ: Căn chữ nằm giữa ô).<br>
    * `android:layout_gravity`: Định vị vị trí của *bản thân cả khối đối tượng đó* so với không gian của ViewGroup cha chứa nó (Ví dụ: Căn cả nút bấm dịch sang bên phải màn hình).<br>

### 5. Code Tương Tác Với Layout & Xử Lý Sự Kiện (Event Handling)<br>
* **Mong muốn hiển thị text tự động theo thiết lập người dùng (Không hardcode):** <br>
  * Gọi trực tiếp ID tài nguyên thông qua lớp `R` trong Java:<br>
    `textView.setText(R.string.welcome_message);`<br>
* **Khi có sự kiện người dùng tác động (Click Button...), muốn chạy code xử lý:**<br>
  * **LAYOUT cần làm gì?** Cần cấp cho linh kiện một ID định danh duy nhất trong XML để code Java có thể tìm thấy: `android:id="@+id/btn_submit"`<br>
  * **CODE viết như thế nào? (2 cách):** <br>
    * *Cách 1 (Qua XML):* Thêm thuộc tính `android:onClick="xuLyBamNut"` vào XML, rồi viết hàm tương ứng trong Java:<br>
      `public void xuLyBamNut(View v) { /* Code xử lý */ }`<br>
    * *Cách 2 (Qua Java):* Sử dụng bộ lắng nghe sự kiện `setOnClickListener`:<br>
      `Button btn = findViewById(R.id.btn_submit); btn.setOnClickListener(new View.OnClickListener() { @Override public void onClick(View v) { /* Code xử lý */ } });`<br>

### 6. Kiểm Tra Quyền Thực Thi Trong Code Java (Runtime Permissions)<br>
* **Code kiểm tra quyền như thế nào?** (Áp dụng từ Android 6.0 trở lên cho các quyền nguy hiểm):<br>
  `if (ContextCompat.checkSelfPermission(this, Manifest.permission.CAMERA) == PackageManager.PERMISSION_GRANTED) { openCamera(); } else { ActivityCompat.requestPermissions(this, new String[]{Manifest.permission.CAMERA}, 101); }`<br>
* **Ý nghĩa:** Bảo vệ ứng dụng không bị crash bất ngờ nếu người dùng chủ động tắt quyền trong cài đặt máy, đồng thời tôn trọng tính riêng tư và bảo mật dữ liệu của khách hàng.<br>

### 7. Thư Mục Đặc Biệt: Assets<br>
* **Bản chất khi biên dịch (Compiler):** Thư mục `assets/` chứa các tài nguyên thô. Khi đóng gói thành file `.apk`, tất cả tệp tin và thư mục con trong này **đều đi theo app, nằm trong app và giữ nguyên vẹn cấu trúc gốc** (không bị mã hóa hay nén đổi tên).<br>
* **Cú pháp truy cập từ code Java:** <br>
  `AssetManager assetManager = getAssets(); InputStream is = assetManager.open("ten_thu_muc/file_cua_ban.txt");` <br>
* **Lợi ích của việc có sẵn file (Offline):** <br>
  * Ứng dụng hoạt động độc lập hoàn toàn, không cần kết nối Internet (Wifi/4G). <br>
  * Tốc độ truy xuất và đọc dữ liệu cực nhanh do đọc trực tiếp từ bộ nhớ trong của thiết bị. <br>
  * Tránh rủi ro bị mất file, chết link từ máy chủ (Server).<br> 
* **Ứng dụng thực tế:** *Xây dựng ứng dụng Cẩm nang Sơ cứu Y Tế Khẩn Cấp.* Toàn bộ các bài viết hướng dẫn xử lý tai nạn, hình ảnh sơ cứu được lưu sẵn offline dạng HTML/Text trong thư mục `assets/`. Khi người dùng gặp sự cố ở những nơi mất sóng (rừng núi, trên máy bay), app vẫn mở ra trơn tru để cứu hộ kịp thời, không phụ thuộc vào mạng. <br>

### 8. Viết App1:<br>
- Dữ liệu: Tài liệu bảo mật nội bộ của một công ty<br>
- công cụ để hiển thị dữ liệu: TextView + ScrollView<br>
- Vấn đề đặt ra: ác tập đoàn công nghệ lớn hoặc cơ quan đầu não thường có khu vực phòng Lab/phòng Server bảo mật cao. Nhân viên bước vào không được phép kết nối Internet, không có Wifi hay sóng di động để tránh rò rỉ dữ liệu (Data Leakage). Tuy nhiên, khi gặp sự cố kỹ thuật hoặc cần kiểm tra quy trình xử lý an ninh, họ bắt buộc phải có tài liệu hướng dẫn chuẩn để làm theo.<br>
- Giải pháp thực hiện: Xây dựng ứng dụng "Cẩm nang Quy trình Bảo mật Nội bộ" chạy độc lập hoàn toàn (Offline 100%). Toàn bộ tài liệu mật, các bước xử lý sự cố an ninh hệ thống được mã hóa cấu trúc sẵn dưới dạng JSON lồng mã HTML và lưu thẳng vào thư mục assets/ của ứng dụng. Nhân viên chỉ cần mở điện thoại chuyên dụng của công ty ra là tra cứu được ngay lập tức mà không sợ vi phạm quy định bảo mật mạng.<br>

- Đặc thù dữ liệu (Tệp rules.json trong Assets)<br>
Tính cấu trúc: Lưu dạng mảng JSON (JSONArray), chia thành các trường dữ liệu cố định (id, title, content) dễ bóc tách.<br>

 + Định dạng sẵn (Rich Text Hybrid): Nội dung chứa các thẻ HTML cơ bản (<b>, <i>, <p>) giúp cài cắm sẵn thuộc tính in đậm, in nghiêng, cách dòng ngay từ kho lưu       trữ thô.<br>

 + Đóng gói tĩnh: Dữ liệu chỉ đọc (Read-only), đi liền với bộ cài đặt app (.apk), hoạt động độc lập không cần Internet.<br>

- Thuật toán xử lý dữ liệu<br>
 + Đọc file (IO Stream): Quét mảng byte dữ liệu tĩnh từ Assets, chuyển đổi thành chuỗi String văn bản bằng bảng mã UTF-8 để giữ nguyên tiếng Việt có dấu.<br>

 + Phân tích cú pháp (JSON Parsing): Phân rã chuỗi văn bản thành các đối tượng JSON để trích xuất chính xác nội dung theo từng khóa (Key).<br>

 + Tiền xử lý đồ họa (HTML-to-Spanned): Dùng Html.fromHtml() để duyệt chuỗi, bẻ gãy các thẻ <b>, <i> thô và dịch thành văn bản giàu thuộc tính hiển thị (Rich         Text).<br>

- Đối tượng hiển thị dữ liệu (UI Components)<br>
+ TextView: Đối tượng hiển thị chính. Nhận nhiệm vụ vẽ văn bản đã qua xử lý HTML lên màn hình. Ưu điểm là nhẹ, tốn rất ít RAM và CPU, giúp tài liệu mở lên ngay      lập tức so với việc dùng WebViewer cồng kềnh.<br>

 + ScrollView: Thùng chứa bao bọc bên ngoài TextView, kích hoạt tính năng vuốt trượt theo chiều dọc để người dùng cuộn xem toàn bộ nội dung khi quy trình quá dài.<br>
- Quy Trình thực hiện:<br>
  + Khởi tạo project mới trên Android Studio:<br>
  + Chọn Android Views Activity:<br>
    <img width="1111" height="804" alt="image" src="https://github.com/user-attachments/assets/acd0dc9b-2d18-4f06-a1e8-1edc870e4fcc" /><br>

  + Cấu hình các thông số cho dự án bảo mật này:<br>

     Name: Điền CamNangBaoMat.<br>

     Language: Chọn Java.<br>

     Minimum SDK: Chọn API 24: Android ̃7.0 (Lollipop).<br>
    <img width="1112" height="808" alt="image" src="https://github.com/user-attachments/assets/b7fc7e54-bd0b-4fa7-9ed9-01e8bb037a8e" /><br>

    + Bấm finish và đợi Android Studio tự động đồng bộ các file dữ liệu nền móng<br>
    + Tạo thư mục Assets và nạp file JSON Bảo mật:<br>
      chuột phải vào thư mục app -> Chọn New -> Folder -> Assets Folder -> Bấm Finish<br>
      <img width="1714" height="903" alt="image" src="https://github.com/user-attachments/assets/626d8c7f-4b08-4ed8-9e73-1a0220a30b9f" /><br>
    + Click chuột phải vào assets -> Chọn New -> Directory -> Đặt tên là security_docs<br>
      <img width="1245" height="783" alt="image" src="https://github.com/user-attachments/assets/1059a687-bd2d-488e-b3c6-c9c07184b70f" /><br>
      <img width="532" height="83" alt="image" src="https://github.com/user-attachments/assets/cd8e109e-2494-4418-bd7b-3bfad4488b95" /><br>

    + Click chuột phải vào thư mục security_docs vừa tạo -> Chọn New -> File -> Đặt tên tệp là rules.json sau đó cấu hình file<br>
      
  <img width="524" height="103" alt="image" src="https://github.com/user-attachments/assets/8d83de16-99a5-4c51-9f8e-3490007a0203" /><br>
  <img width="622" height="381" alt="image" src="https://github.com/user-attachments/assets/867f55f3-dfe3-4ae2-8fbd-ceb3e0802434" /><br>

    + chuyển sang tab activity_main.xml, Sửa chế độ hiển thị sang dạng Code:<br>
      <img width="915" height="574" alt="image" src="https://github.com/user-attachments/assets/bb6c824e-da7f-47b3-be4b-414ba437c1ad" /><br>
    + Cấu hình cho file activity_main.xml<br>
      <img width="1617" height="868" alt="image" src="https://github.com/user-attachments/assets/d8f4020d-1be7-4cbc-8ca0-d45efdb9125a" /><br>
    + Sửa file logic MainActivity.java:<br>
      <img width="897" height="869" alt="image" src="https://github.com/user-attachments/assets/d18ddb53-4da7-4f08-8cf4-e389bfbc53b6" /><br>
    + Kết nối điện thoại với máy tính và cho phép gỡ lỗi qua USB<br>
    + RunApp trên Android Studio để cài đặt app về điện thoại<br>
    + Kết quả cài đặt<br>
      <img width="301" height="255" alt="image" src="https://github.com/user-attachments/assets/a5abbd29-98a0-4ef3-89e4-6b059c14af6a" /><br>
    + Kết quả sử dụng app không cần internet:<br>
      <img width="863" height="1896" alt="image" src="https://github.com/user-attachments/assets/50fdc2dd-97e0-464b-9a08-1e15683b9804" /><br>

  ### 9. Viết app2<br>
  - Tạo dự án mới cho App2: <br>
    <img width="1108" height="806" alt="image" src="https://github.com/user-attachments/assets/18f3aeff-5426-4778-a20b-9d3ded6b80d1" /><br>
  - Thêm thư viện gọi API (Volley) vào file Cấu hình:<br>
    <img width="1204" height="559" alt="image" src="https://github.com/user-attachments/assets/9be1a323-45ec-434d-bf5c-ff38109c78ff" /><br>
    <img width="634" height="571" alt="image" src="https://github.com/user-attachments/assets/cd82c6c0-b259-461c-865d-d073e667c440" /><br>

 - Khai báo Quyền Internet trong AndroidManifest.xml:<br>
   <img width="558" height="514" alt="image" src="https://github.com/user-attachments/assets/5511d18a-d7ed-4dc7-a79f-faf9ce0630cf" /><br>
  <img width="1013" height="787" alt="image" src="https://github.com/user-attachments/assets/58f3f8f7-015e-4bf2-890c-c8811603dc40" /><br>
 - Thêm thuộc tính android:usesCleartextTraffic="true" vào bên trong thẻ <application ...> để cho phép WebView load được cả các trang web không có bảo mật (HTTP) nếu cần:<br>
   <img width="1022" height="779" alt="image" src="https://github.com/user-attachments/assets/76ed6c36-b687-4d86-8661-ed9f8a0b0e11" /><br>

 - Tạo thêm 2 Activity mới:<br>
   <img width="1667" height="903" alt="image" src="https://github.com/user-attachments/assets/2a068859-8044-4e18-9c48-328b84125eab" /><br>
    <img width="562" height="642" alt="image" src="https://github.com/user-attachments/assets/c857100c-6404-485c-9517-7eb694938b18" /><br>
- Activity1:<br>
  + Thiết kế giao diện ( activity_main.xml):<br>
    <img width="1056" height="869" alt="image" src="https://github.com/user-attachments/assets/e9e42bdf-0f4b-4da9-bf6b-48e381bcffc9" /><br>

  + Viết code điều khiển java (MainActivity.java):<br>
    <img width="1074" height="874" alt="image" src="https://github.com/user-attachments/assets/afd17262-9b22-4bb3-a3cf-d2b49fe02e46" /><br>
- Activity2 Giải bài toán đơn giản và gọi API tới https://k58kmt.tdh.io.vn/api :<br>
  + Thiết kế layout (Activity2.xml):<br>
    <img width="1011" height="863" alt="image" src="https://github.com/user-attachments/assets/9229fb11-c618-4bc3-81f5-e70d7c7d2b18" /><br>
  + Xử lí logic và thuật toán(Activity2.java):<br>
   <img width="1041" height="832" alt="image" src="https://github.com/user-attachments/assets/842097d1-8e97-416f-b806-345ff6afacba" /><br>

- Activity3 dùng webview để truy cập từ trang web https://k58kmt.tdh.io.vn?masv=K225480106100:<br>
  + Thiết kế layout (Activity3.xml):<br>
      <img width="1030" height="908" alt="image" src="https://github.com/user-attachments/assets/8c6494fc-9708-4e5b-a523-c0bb692050ab" /><br>

   + Xử lí logic và truyền Url vào(Activity3.java):<br>
     <img width="1055" height="870" alt="image" src="https://github.com/user-attachments/assets/b1043fd1-2622-4248-9a45-a53dcc5eee3f" /><br>

  - Kết quả cài đặt và chạy app2:<br>
    <img width="234" height="156" alt="image" src="https://github.com/user-attachments/assets/44b1778c-68e3-428b-aa16-514112b016bd" /><br>
    + Activity1:<br>
      <img width="1497" height="844" alt="image" src="https://github.com/user-attachments/assets/1d102d16-25d7-486d-89e3-c4d23198940a" /><br>

     + Activity2:<br>
       <img width="1504" height="840" alt="image" src="https://github.com/user-attachments/assets/ab9b6d34-4302-4dd2-82b0-5062c1533d5b" /><br>
      + Activity3:<br>
      
        
        
