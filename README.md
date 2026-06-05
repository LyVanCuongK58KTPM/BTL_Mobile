MÔN HỌC: PHÁT TRIỂN ỨNG DỤNG TRÊN THIẾT BỊ DI ĐỘNG - TEE0419 
BÀI TẬP LỚN:
A. Viết phần mềm trên công cụ Mit App inventor ( xây dựng 1 bài toán đơn giản gồm 3 screen và button gọi sang các screen)
1. Truy cập: https://appinventor.mit.edu/ và đăng nhập tài khoản
2. Tạo project:
  <img width="1889" height="890" alt="image" src="https://github.com/user-attachments/assets/9da22ca3-93df-4e89-ab74-159ceab595e3" />
3. Thêm 2 màn hình nữa:
  <img width="792" height="827" alt="image" src="https://github.com/user-attachments/assets/e70e6c03-c3cb-4a23-86f8-245c0ae5c324" />
4. Tại Screen 1:
  - Kéo thả thanh Label ở mục user interface bên trái vào Screen1, sửa đổi thuộc tính text trong cột Properties bên phải của Label thành nội dung cần hiển thị:
    <img width="1645" height="910" alt="image" src="https://github.com/user-attachments/assets/c0328ec2-c3de-4f6f-ad76-35915610b597" />
  - Kéo thả 2 button vào dưới thanh Label và sửa mục text của 2 button:
    + Text button 1: "Giải toán" để chuyển sang Screen giải toán
      <img width="1566" height="800" alt="image" src="https://github.com/user-attachments/assets/bc84ffd9-51d7-479f-9d9d-49e5b2d3b339" />

    + Text button 2: "Xem web" để chuyển sang Screen3 sử dụng webviewer để xem trang web có sẵn
     <img width="1634" height="861" alt="image" src="https://github.com/user-attachments/assets/df40942d-9aae-43f4-b493-80db1e6f88e0" />

5. Tại Screen 2:
   - Kéo thả 2 thanh textbox vào Screen2 và tích vào ô NumberOnly ở 2 textbox để chỉ nhập số khi tính toán:
     <img width="1620" height="854" alt="image" src="https://github.com/user-attachments/assets/de1d4273-491e-49b3-ab48-cac3d67db681" />
  - Kéo 1 thanh button vào dưới 2 thanh textbox để khi bấm nút sẽ thực hiện tính toán phép chia
  - Kéo 1 thanh label để hiển thị kết quả:
    ( Cấu trúc Screen 2):
    <img width="1037" height="797" alt="image" src="https://github.com/user-attachments/assets/3c7df739-2bcb-4d8a-be28-b70da0bf08c7" />

  
6. Tại Screen3:
   - Kéo link kiện Webviewer vào màn hình và thêm url trang web có sẵn vào mục HomeUrl:
     <img width="1918" height="854" alt="image" src="https://github.com/user-attachments/assets/547a316c-6746-451d-aba6-b9a362715332" />
7. Ghép các khối Blocks logic điều hướng và tính toán:
- Chuyển sang tab Block:
  <img width="1619" height="868" alt="image" src="https://github.com/user-attachments/assets/263e599e-07d5-43c4-92c4-0c5c78fb0542" />
  Tại Screen1:
- Bấm vào Button1 ở mục bên trái tab Block --> chọn "When button1 .click do"
  <img width="1919" height="919" alt="image" src="https://github.com/user-attachments/assets/b855b7d8-3fce-4f22-9de0-b1f2c217470e" />
- kéo khối open another screen with screenName gắn vào bên trong khối when Button1.Click:
<img width="654" height="222" alt="image" src="https://github.com/user-attachments/assets/349e326f-e89f-413d-897c-09f364ce4ac9" />

- Copy khối button 1 và đổi button1 thành button2:
  <img width="710" height="314" alt="image" src="https://github.com/user-attachments/assets/9c16fead-f2ea-4cb5-9387-87a9ab682ab4" />
  Tại Screen2:
 - Bấm vào Button1 ở cột trái, kéo khối when Button1.Click do ra màn hình:
- Bấm vào Label1, tìm và kéo khối màu xanh lá: set Label1.Text to gắn vào trong sự kiện click của nút bấm
- Bấm vào mục Math, kéo khối phép cộng [  ] + [  ] gắn vào đuôi của khối set Label1.Text to
- Bấm vào TextBox1, kéo khối TextBox1.Text gắn vào ô trống thứ nhất của phép cộng.
- Bấm vào TextBox2, kéo khối TextBox2.Text gắn vào ô trống thứ hai của phép cộng.
  <img width="902" height="187" alt="image" src="https://github.com/user-attachments/assets/8193f57b-b36c-48f3-9f62-549784a88c89" />

  Tại Screen3: đã gán url của trang web có sẵn nên không cần thêm block nào
8. Chạy thử ứng dụng:
 - Lên thanh menu trên cùng, chọn Connect -> AI Companion. Một mã QR và mã ký tự sẽ hiện ra.
   <img width="1917" height="917" alt="image" src="https://github.com/user-attachments/assets/3d03fd2e-c34a-4aa2-857e-88c3c25d6924" />
<img width="493" height="500" alt="image" src="https://github.com/user-attachments/assets/42b4ad97-9002-4b90-997f-989d9e048b79" />
- Trên điện thoại, bạn cài ứng dụng MIT AI2 Companion (có sẵn trên CH Play/App Store).
- Mở app trên điện thoại lên, chọn Scan QR Code và quét mã trên màn hình máy tính.
  <img width="1920" height="2560" alt="image" src="https://github.com/user-attachments/assets/a146a607-666b-48fe-afc0-76ece63c7262" />
  <img width="1920" height="2560" alt="image" src="https://github.com/user-attachments/assets/5e6b73be-7617-4e3a-acc4-ebb34258bb47" />
  <img width="646" height="779" alt="image" src="https://github.com/user-attachments/assets/cb739d6e-7e3c-44d2-9e13-b20b8ddfcd69" />
9. Giải thích ý nghĩa của Block:
- Bản chất của việc kéo thả Block
Trực quan hóa mã nguồn: Về bản chất, mỗi khối block là một "đoạn code" (như cú pháp Java, C#) đã được bao bọc dưới dạng một mảnh ghép hình học có màu sắc riêng biệt theo từng nhóm chức năng (Vòng lặp, Điều kiện, Toán học, Biến...).

Ràng buộc logic vật lý: Các block được thiết kế các mấu lồi/lõm (ngàm kết nối) tương ứng với cấu trúc cú pháp của lập trình. Chúng chỉ có thể khớp chặt vào nhau khi đúng logic và đúng kiểu dữ liệu (ví dụ: không thể nhét một khối chữ "Text" vào ngàm tính toán của phép cộng "Math"). Khi lắp ghép chính xác, phần mềm sẽ phát ra tiếng "tách" trực quan.

- Ưu điểm so với viết code truyền thống (Text-based)
Loại bỏ lỗi cú pháp: Người học hoàn toàn không phải lo lắng về việc gõ thiếu dấu chấm phẩy ;, thiếu dấu ngoặc { }, hay gõ sai chính tả tên hàm — những lỗi kinh điển khiến code truyền thống bị lỗi không chạy được.

Học tư duy nhanh hơn: Giúp người mới bắt đầu tập trung 100% vào việc phát triển tư duy thuật toán (App hoạt động thế nào? Khi nào bấm nút thì làm gì?) thay vì mất thời gian học thuộc lòng các từ khóa lập trình phức tạp.

Trực quan và dễ nhớ: Màu sắc của các block giúp người lập trình dễ dàng nhận diện vùng quản lý dữ liệu bằng mắt thường nhanh hơn đọc một trang text đen trắng.

- Nhược điểm
Cồng kềnh khi dự án lớn: Khi ứng dụng phát triển phức tạp với hàng nghìn dòng lệnh, màn hình Blocks sẽ trở thành một "mê cung" khổng lồ, rất rối mắt, khó cuộn chuột để tìm kiếm, quản lý hoặc sửa lỗi.

Bị giới hạn tính năng: Bạn chỉ có thể làm những gì mà các khối block có sẵn hỗ trợ. Việc muốn can thiệp sâu vào nhân hệ điều hành, tối ưu phần cứng hay viết thuật toán xử lý đồ họa nâng cao là bất khả thi nếu so với code thuần (Java/Kotlin).

Tốc độ gõ chậm: Đối với lập trình viên chuyên nghiệp, việc dùng chuột kéo từng khối sẽ chậm hơn rất nhiều so với tốc độ gõ phím từ bàn phím.


=============================================================================================================================================================
B. Viết app sử dụng Android Studio
### 1. AndroidManifest.xml & Cơ Chế Khai Báo Quyền (Permissions)
* **AndroidManifest.xml mô tả gì?** Là file cấu hình bắt buộc nằm ở thư mục gốc, đóng vai trò như "sơ yếu lý lịch" của app nhằm mô tả: Cấu trúc các thành phần của app (`Activity`, `Service`, `Broadcast Receiver`), thông tin cơ bản (Package name, Icon, Tên app, Phiên bản SDK), và danh sách các quyền cần truy cập.
* **Khai báo quyền thế nào?** Sử dụng thẻ `<uses-permission>` đặt trong thẻ `<manifest>` và nằm ngoài thẻ `<application>`.
  * *Ví dụ xin quyền Camera:* `<uses-permission android:name="android.permission.CAMERA" />`
* **Để làm gì?** Đây là cơ chế bảo mật của Android. App bắt buộc phải "xin phép" Hệ điều hành trước để được quyền can thiệp vào các tài nguyên hoặc dữ liệu nhạy cảm của thiết bị (Internet, Camera, Vị trí, Danh bạ). Nếu cố tình gọi code phần cứng mà không khai báo, app sẽ bị dừng đột ngột (`SecurityException`).

### 2. Vòng Đời Ứng Dụng (Activity Lifecycle) & Hàm `onCreate()`
* **Vòng đời ứng dụng là gì?** Là chuỗi các trạng thái của một màn hình (`Activity`) từ lúc khởi tạo đến khi bị đóng hoàn toàn, được quản lý qua các hàm callback tự động:
  * `onCreate()` -> `onStart()` -> `onResume()`: Mở app, hiển thị giao diện và cho phép người dùng tương tác công khai.
  * `onPause()` -> `onStop()`: Ẩn app (bấm nút Home, nhận cuộc gọi), màn hình bị che khuất một phần hoặc hoàn toàn, chuyển sang chế độ chạy ngầm.
  * `onDestroy()`: Tắt hẳn app (bấm nút Back hoặc hệ thống giải phóng RAM), giao diện bị xóa hoàn toàn khỏi bộ nhớ.
* **Tại sao có sẵn hàm `onCreate()`?** Vì đây là điểm khởi đầu (Entry Point) bắt buộc của một Activity. Hệ điều hành cần hàm này chạy đầu tiên (1 lần duy nhất) để làm nhiệm vụ nền móng: Nạp giao diện XML (`setContentView`), khởi tạo biến và liên kết các sự kiện ban đầu. Không có `onCreate`, màn hình không thể định hình và không thể chạy.

### 3. Quản Lý Giao Diện XML & Tham Chiếu Tài Nguyên (Tránh Hardcode)
* **Giao diện XML:** Định nghĩa bằng file XML trong thư mục `res/layout/` theo cấu trúc cây phân cấp (UI Design). Tách biệt hoàn toàn với logic xử lý bằng code Java.
* **Lưu trữ thay vì Hardcode:** Các chuỗi chữ (text) hoặc giá trị cứng không được viết trực tiếp vào XML mà lưu tập trung tại file `strings.xml` (`res/values/strings.xml`).
* **Cú pháp tham chiếu:**
  * Trong file giao diện XML: `@string/ten_bien`
  * Trong mã nguồn Java: `R.string.ten_bien`
* **Ưu điểm của việc tham chiếu:**
  * **Dễ bảo trì:** Sửa đổi câu chữ ở một nơi (`strings.xml`), hàng chục màn hình tự động cập nhật theo.
  * **Tách biệt vai trò:** Giúp người thiết kế, lập trình viên và người dịch thuật làm việc độc lập.
* **OS hỗ trợ tự động lấy giá trị theo LOCATION, LANGUAGE, THEME giúp app làm được gì?**
  * Khi tạo các thư mục tài nguyên có hậu tố đặc biệt (như `values-vi/` cho tiếng Việt, `values-night/` cho chế độ tối), Android OS sẽ tự động nhận diện cấu hình máy để nạp đúng file tương ứng.
  * **Kết quả:** Giúp app tự động đạt khả năng **Đa ngôn ngữ (Localization)** toàn cầu và hỗ trợ chế độ **Giao diện tối (Dark Mode)** mượt mà mà không cần viết thêm bất kỳ dòng lệnh điều kiện `if-else` nào.

### 4. Đối Tượng Chứa (ViewGroup) & Quy Luật Sắp Xếp Giao Diện
* **Đối tượng chứa (ViewGroup - Ví dụ `LinearLayout`):** Gom nhóm các đối tượng con lại và bắt chúng tuân theo một quy luật sắp xếp chung để hiển thị:
  * **Chiều Dọc / Chiều Ngang:** Xác định qua thuộc tính `android:orientation="vertical"` (các phần tử con nằm xếp chồng kề nhau dọc từ trên xuống) hoặc `"horizontal"` (nằm kề nhau ngang từ trái sang phải).
  * **Cơ chế Gravity:**
    * `android:gravity`: Định vị vùng không gian của nội dung *bên trong* chính đối tượng đó (Ví dụ: Căn chữ nằm giữa ô).
    * `android:layout_gravity`: Định vị vị trí của *bản thân cả khối đối tượng đó* so với không gian của ViewGroup cha chứa nó (Ví dụ: Căn cả nút bấm dịch sang bên phải màn hình).

### 5. Code Tương Tác Với Layout & Xử Lý Sự Kiện (Event Handling)
* **Mong muốn hiển thị text tự động theo thiết lập người dùng (Không hardcode):**
  * Gọi trực tiếp ID tài nguyên thông qua lớp `R` trong Java:
    `textView.setText(R.string.welcome_message);`
* **Khi có sự kiện người dùng tác động (Click Button...), muốn chạy code xử lý:**
  * **LAYOUT cần làm gì?** Cần cấp cho linh kiện một ID định danh duy nhất trong XML để code Java có thể tìm thấy: `android:id="@+id/btn_submit"`
  * **CODE viết như thế nào? (2 cách):**
    * *Cách 1 (Qua XML):* Thêm thuộc tính `android:onClick="xuLyBamNut"` vào XML, rồi viết hàm tương ứng trong Java:
      `public void xuLyBamNut(View v) { /* Code xử lý */ }`
    * *Cách 2 (Qua Java):* Sử dụng bộ lắng nghe sự kiện `setOnClickListener`:
      `Button btn = findViewById(R.id.btn_submit); btn.setOnClickListener(new View.OnClickListener() { @Override public void onClick(View v) { /* Code xử lý */ } });`

### 6. Kiểm Tra Quyền Thực Thi Trong Code Java (Runtime Permissions)
* **Code kiểm tra quyền như thế nào?** (Áp dụng từ Android 6.0 trở lên cho các quyền nguy hiểm):
  `if (ContextCompat.checkSelfPermission(this, Manifest.permission.CAMERA) == PackageManager.PERMISSION_GRANTED) { openCamera(); } else { ActivityCompat.requestPermissions(this, new String[]{Manifest.permission.CAMERA}, 101); }`
* **Ý nghĩa:** Bảo vệ ứng dụng không bị crash bất ngờ nếu người dùng chủ động tắt quyền trong cài đặt máy, đồng thời tôn trọng tính riêng tư và bảo mật dữ liệu của khách hàng.

### 7. Thư Mục Đặc Biệt: Assets
* **Bản chất khi biên dịch (Compiler):** Thư mục `assets/` chứa các tài nguyên thô. Khi đóng gói thành file `.apk`, tất cả tệp tin và thư mục con trong này **đều đi theo app, nằm trong app và giữ nguyên vẹn cấu trúc gốc** (không bị mã hóa hay nén đổi tên).
* **Cú pháp truy cập từ code Java:**
  `AssetManager assetManager = getAssets(); InputStream is = assetManager.open("ten_thu_muc/file_cua_ban.txt");`
* **Lợi ích của việc có sẵn file (Offline):**
  * Ứng dụng hoạt động độc lập hoàn toàn, không cần kết nối Internet (Wifi/4G).
  * Tốc độ truy xuất và đọc dữ liệu cực nhanh do đọc trực tiếp từ bộ nhớ trong của thiết bị.
  * Tránh rủi ro bị mất file, chết link từ máy chủ (Server).
* **Ứng dụng thực tế:** *Xây dựng ứng dụng Cẩm nang Sơ cứu Y Tế Khẩn Cấp.* Toàn bộ các bài viết hướng dẫn xử lý tai nạn, hình ảnh sơ cứu được lưu sẵn offline dạng HTML/Text trong thư mục `assets/`. Khi người dùng gặp sự cố ở những nơi mất sóng (rừng núi, trên máy bay), app vẫn mở ra trơn tru để cứu hộ kịp thời, không phụ thuộc vào mạng.




