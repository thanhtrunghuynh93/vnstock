<div align="center">

[![python_course_3](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/python_data_analysis_course_3_thinhvu.png)](https://thinhvu.com/2023/08/09/phan-tich-du-lieu-voi-python-for-data-analysis-3/)

</div>

---

<div id="badges" align="center">
<img src="https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/vnstock-logo-white.jpg" alt= "logo"/>
</div>

<div id="badges" align="center">
<img src="https://img.shields.io/pypi/pyversions/vnstock?logoColor=brown&style=plastic" alt= "Version"/>
<img src="https://img.shields.io/pypi/dm/vnstock" alt="Download Badge"/>
<img src="https://img.shields.io/github/last-commit/thinh-vu/vnstock" alt="Commit Badge"/>
<img src="https://img.shields.io/github/license/thinh-vu/vnstock?color=red" alt="License Badge"/>
</div>

---

🌐 View in **[English](https://github.com/thinh-vu/vnstock/blob/main/README-en.md)**

MỤC LỤC

- [I. 🎤 Giới thiệu](#i--giới-thiệu)
- [II. 📚 Hướng dẫn sử dụng cho người mới](#ii--hướng-dẫn-sử-dụng-cho-người-mới)
- [III. 💻 Cách sử dụng các hàm trong vnstock](#iii--cách-sử-dụng-các-hàm-trong-vnstock)
- [IV. 🚚 Xuất, Lưu trữ, Chia sẻ dữ liệu](#iv--xuất-lưu-trữ-chia-sẻ-dữ-liệu)
- [V. 🙋‍♂️ Thông tin liên hệ](#v-️-thông-tin-liên-hệ)
- [VI. 💪 Hỗ trợ phát triển dự án vnstock](#vi--hỗ-trợ-phát-triển-dự-án-vnstock)
- [VII. ⚖ Tuyên bố miễn trừ trách nhiệm](#vii--tuyên-bố-miễn-trừ-trách-nhiệm)
- [VII. 🔗 Trích dẫn thông tin (Cite)](#vii--trích-dẫn-thông-tin-cite)
- [VIII. 🔑 Giấy phép (License)](#viii--giấy-phép-license)



# I. 🎤 Giới thiệu
## 1.1. Giới thiệu chung
vnstock là thư viện Python được thiết kế để tải dữ liệu chứng khoán Việt Nam một cách dễ dàng và miễn phí. vnstock sử dụng các nguồn cấp dữ liệu đáng tin cậy, bao gồm nhưng không giới hạn từ công ty chứng khoán và công ty phân tích thị trường tại Việt Nam. Gói thư viện được thiết kế dựa trên nguyên tắc về sự đơn giản và mã nguồn mở, hầu hết các hàm được viết dựa trên thư viện request và pandas có sẵn trên môi trường Google Colab do đó người dùng không cần cài đặt thêm các gói thư viện kèm theo.

## 1.2. Tính năng chính
vnstock cung cấp nhiều tính năng đa dạng như tải dữ liệu lịch sử giá, thông tin công ty niêm yết, thông tin thị trường cho tất cả các mã chứng khoán niêm yết.

## 1.3. Nguồn cấp dữ liệu
Thư viện `vnstock` cung cấp khả năng kết nối tới các API công khai của các nguồn cấp dữ liệu đáng tin cậy để người dùng có thể truy xuất dữ liệu chứng khoán Việt Nam và tương tác với các đối tượng Pandas DataFrame trong môi trường Python. Bạn cũng có thể xuất dữ liệu sang các định dạng phổ thông như csv, Excel, Google Sheets, Database để tiến hành phân tích nếu muốn. Việc truy xuất dữ liệu này là **TỰ DO** và hoàn toàn **MIỄN PHÍ**.

## 1.4. Tips
- Theo dõi những cập nhật về thay đổi của vnstock bằng tính năng `Watch`. Hiện tại vnstock được cập nhật thường xuyên hàng tuần qua nhánh `beta`, vì vậy theo dõi repo này giúp bạn luôn nắm bắt được kịp thời những thay đổi mới nhất.
- Đánh dấu yêu thích repo `vnstock` bằng tính năng `Star`. Đây cũng là cách giúp vnstock có thể tiếp cận tới nhiều người quan tâm hơn.

<details>
  <summary> Minh họa tính năng Watch và Star </summary>
  
![watch-star](https://github.com/thinh-vu/vnstock/blob/beta/src/vnstock-watch-and-star.png?raw=true)

</details>

## 1.5. Đóng góp xây dựng vnstock

### a. Lan toả vnstock tới nhiều người hơn
- Cách thức đầu tiên đơn giản và dễ áp dụng nhất cho bất kỳ ai yêu thích `vnstock` là góp phần lan tỏa nó tới bạn bè, cộng đồng về trải nghiệm của mình và chia sẻ về cách `vnstock` có thể giúp đơn giản hóa workflow phân tích dữ liệu chứng khoán của những người xung quanh trong cả công việc nghiên cứu lẫn đầu tư thực tế.
- Các hình thức lan tỏa và ủng hộ tinh thần cho `vnstock` bao gồm nhưng không giới hạn
  - Đánh dấu yêu thích dự án trên Github với tính năng `Star` ở trên
  - `Folk` dự án để bắt đầu tùy biến mã nguồn của dự án, đồng thời lan tỏa sự chú ý nhiều hơn cho `vnstock`.
  - Like fanpage vnstock trên Facebook: [vnstock.official](https://www.facebook.com/vnstock.official)
  - Theo dõi và chia sẻ cảm nghĩ của bạn qua bình luận trên Youtube channel [LEarn Anything](https://www.youtube.com/@learn_anything_az). Mình có series hướng dẫn sử dụng cụ thể về vnstock cùng nhiều kiến thức hữu ích khác.
  - Tham gia cộng đồng [Discord vnstock](https://discord.gg/qJvxJcChJ3) để trao đổi và học hỏi lẫn nhau. 

### b. Chia sẻ trải nghiệm của bạn về `vnstock` với tác giả qua bản khảo sát
> vnstock là một dự án tôi tâm huyết, đầu tư nhiều thời gian để phát triển giúp bản thân và cộng đồng tiếp cận nguồn dữ liệu chứng khoán miễn phí và đáng tin cậy.

Hoàn thành bản khảo sát: [Tại đây](https://forms.gle/zaJnbgUCjjL1GoTF6)
Để đảm bảo rằng vnstock phát triển theo hướng đáp ứng nhu cầu của bạn, tôi rất mong nhận được phản hồi từ bạn. Bạn là người dùng quan trọng của vnstock và ý kiến của bạn sẽ giúp chúng tôi xây dựng một kế hoạch phát triển vnstock một cách toàn diện.

### c. Góp sức phát triển mã nguồn dự án

> Các bạn có thể tham khảo file [CONTRIBUTING.MD](./CONTRIBUTING.md) để nắm rõ hơn tiêu chuẩn và hướng dẫn đóng góp mã nguồn dự án.

- Bạn có thể đóng góp xây dựng vnstock thông qua nhiều hình thức khác nhau, trong đó có việc xây dựng và cải tiến mã nguồn hoặc dịch tài liệu của dự án. 
- Để bắt đầu, bạn có thể `folk` nhánh `beta` của repo này về tài khoản của mình, sửa đổi mã nguồn và tạo `pull request` để yêu cầu cập nhật mã nguồn. Sau khi kiểm tra các thay đổi và phê duyệt, mã nguồn do bạn đóng góp sẽ được gộp vào vnstock.
- Lưu ý: Những thay đổi do bạn đóng góp sẽ được phát hành trong phiên bản tiếp theo của `vnstock` trên Pypi.org đồng thời với những cập nhật của tác giả trên nhánh `beta`.

## 1.6. Ủng hộ quỹ phát triển dự án

Nếu bạn nào quan tâm và có nhu cầu về `code` dạo hoặc học python, vui lòng [inbox](https://www.messenger.com/t/mr.thinh.ueh) để trao đổi thêm. Hoạt động này cũng giúp tôi hiểu thêm về những ứng dụng thực tế và phát triển vnstock trong tương lai.

<div id="badges" align="center">
  <a href="https://www.messenger.com/t/mr.thinh.ueh">
    <img src="https://img.shields.io/badge/Messenger-00B2FF?style=for-the-badge&logo=messenger&logoColor=white" alt="Messenger Badge"/>
  </a>
</div>

### 1.6.1. "Code" dạo theo yêu cầu

> Có nhiều bạn làm trong lĩnh vực đầu tư sẽ thấy ngay lợi ích của việc sử dụng vnstock trong việc xây dựng các thuật toán giao dịch nhưng không rành về lập trình hoặc không có thời gian để tự xây dựng, tôi có thể hỗ trợ. `vnstock` cho phép bạn tự động hóa tất cả các công việc liên quan đến việc tải dữ liệu, xây dựng các bộ lọc, phân tích một cách chính xác, nhanh chóng và áp dụng cho toàn bộ cổ phiếu trên sàn. Việc này bạn không thể thực hiện được một cách dễ dàng nếu chỉ biết Excel.

Thấu hiểu nhu cầu trên, tôi cung cấp dịch vụ "code dạo" theo đặt hàng cũng để gây quỹ phát triển dự án và mở rộng cộng đồng người sử dụng. Dịch vụ bao gồm nhưng không giới hạn với các hoạt động dưới đây:
- Tải dữ liệu thị trường
- Viết workflow quét dữ liệu, cập nhật cơ sở dữ liệu, vv
- Thiết lập dự án phân tích chứng khoán toàn diện
- Tạo bộ lọc cổ phiếu độc quyền
- Tạo robot giao dịch qua API
- Cung cấp API dữ liệu độc quyền

### 1.6.2. Đào tạo về phân tích dữ liệu và tự động hóa với Python

> Nếu bạn yêu thích vnstock, muốn ủng hộ tác giả đồng thời quan tâm về học lập trình Python cho việc phân tích dữ liệu nói chung và chứng khoán nói riêng, tôi có thể giúp bạn bằng các khóa học. Yên tâm, Python dễ lắm, tôi chỉ cho. AI cũng có thể hỗ trợ bạn thực hiện hầu hết công việc lập trình miễn là bạn có kiến thức căn bản và biết cách sử dụng chúng.

Khóa học Phân tích dữ liệu với Python #3 (mình tổ chức năm thứ 3 rồi) được triển khai trong tháng 8/2023, bạn nào quan tâm hãy [inbox](https://www.messenger.com/t/mr.thinh.ueh) cho tôi để trao đổi thêm. Bạn cũng có thể tham khảo bài viết giới thiệu khóa học trên blog về phân tích dữ liệu tôi đã từng tổ chức [tại đây](https://thinhvu.com/2023/08/09/phan-tich-du-lieu-voi-python-for-data-analysis-3/)

# II. 📚 Hướng dẫn sử dụng cho người mới
## 2.1. Tài nguyên quan trọng

Trước khi bắt đầu, bạn có thể xem Video giới thiệu chính thức cho vnstock mình mới chia sẻ trên Youtube [tại đây](https://www.youtube.com/watch?v=6kP2TTtEY9Y&ab_channel=LEarnAnything)

### 2.1.2. Website chính thức của vnstock
vnstock đã hoàn thiện bước đầu việc xây dựng một website chuyên biệt để cập nhật thông tin về dự án, tài liệu sử dụng, blog, khóa học, và các tài nguyên hữu ích khác. Các nội dung của website đang từng bước được cập nhật và hoàn thiện.

Bạn có thể truy cập [vnstock.site](https://vnstock.site?utm_source=github&utm_medium=readme-vnstock) để biết thêm chi tiết.

Bạn cũng có thể truy cập vnstock Web app dưới đây được nhúng trên website của vnstock để người dùng tiện tìm và sử dụng.

### 2.1.3 vnstock Web app

vnstock Web app đã được giới thiệu lần đầu vào 4/9/2023 nhằm giúp người dùng phổ thông có thể tiếp cận với vnstock theo cách đơn giản và thuận tiện nhất dù cho bạn không có bất cứ kỹ năng hay hiểu biết về lập trình python để sử dụng. 

vnstock web app được xây dựng bằng streamlit framework, sử dụng ngôn ngữ Python hoàn toàn. Đây  cũng là một định hướng rất triển vọng trong việc xây dựng các ứng dụng web trong việc phân tích chứng khoán với giao diện người dùng thân thiện và dễ sử dụng, bảo trì.

👉 Bạn có thể truy cập [vnstock Web app](https://vnstock.streamlit.app/) để trải nghiệm ngay. 

### 2.1.4 Notebook minh hoạ

👉 Bạn có thể mở tệp Jupyter Notebook [vnstock_demo_index_all_functions_testing](https://github.com/thinh-vu/vnstock/blob/beta/demo/gen2_vnstock_demo_index_all_functions_testing_2023.ipynb) để dùng thử tất cả các hàm của vnstock. Để sử dụng, nhấp vào nút ![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg) ở đầu trang của notebook để mở với Google Colab.

### 2.1.5. Docstring
Tất cả các hàm của vnstock đều được cung cấp docstring đầy đủ trong khi file README.md này có thể không cập nhật toàn bộ mô tả về các tham số cho phép của từng hàm. Bạn có thể xem phần gợi ý khi viết câu lệnh trên các IDE như Google Colab, Visual Studio Code, hay Jupyter Notebook hoặc mở phần source code của Github để xem chi tiết. Trong thời gian tới, vnstock sẽ được bổ sung mô tả đầy đủ tại README.md khi có thể.

<details>
  <summary>Docstring trên Google Colab</summary>
  Gợi ý cú pháp hàm được hiển thị khi viết bất kỳ hàm nào thuộc vnstock, trong ví dụ này hiển thị trong giao diện Google Colab.

  ![docstring_ide](https://github.com/thinh-vu/vnstock/blob/beta/src/docstring_suggestion.jpeg?raw=true)

</details>

<details>
  <summary>Docstring trong mã nguồn</summary>
  
  Mở mã nguồn tại file [vnstock.py](https://github.com/thinh-vu/vnstock/blob/beta/vnstock/stock.py), tìm hàm bạn cần tra cứu docstring.

  ![docstring_source](https://github.com/thinh-vu/vnstock/blob/beta/src/docstring_source_code.jpeg?raw=true)

</details>

### 2.1.6. Xây dựng cộng đồng vnstock

🖐 Nếu bạn thấy thư viện này có giá trị và muốn hỗ trợ tác giả duy trì vnstock dưới dạng mã nguồn mở, miễn phí thì có thể tham gia ủng hộ gây quỹ phát triển dự án này. Để biết thêm chi tiết, vui lòng tham khảo bài viết trên blog sau: [Cùng nhau xây dựng cộng đồng VNStock vững mạnh](https://thinhvu.com/2023/04/15/xay-dung-cong-dong-vnstock-vung-manh/).

- Tham gia nhóm vnstock trên Facebook: [Tại đây](https://www.facebook.com/groups/vnstock)
- Tham gia Discord channel: [Tại đây](https://discord.gg/qJvxJcChJ3)

<details>
  <summary>Ủng hộ quỹ phát triển vnstock</summary>
  Nếu vnstock giúp ích cho bạn, hãy đóng góp quỹ phát triển ứng dụng này theo một trong hai hình thức sau gồm chuyển khoản ngân hàng hoặc Momo. Mọi khoản đóng góp đều đáng trân quý và là động lực giúp tác giả duy trì vnstock luôn hữu ích, miễn phí, và dễ tiếp cận cho cộng đồng.

  - ![vcb-qr](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/vcb-qr-thinhvu.jpg)
  - ![momo-qr](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/momo-qr-thinhvu.jpeg)

</details>

### 2.1.7. Lộ trình phát triển

🔥 Bạn có thể tham khảo thêm [Ý tưởng cho các tính năng nâng cao cho các phiên bản sắp tới](https://github.com/users/thinh-vu/projects/1/views/4) để đồng hành cùng vnstock. 

### 2.1.8. Lịch sử thay đổi

👉 Từ phiên bản 0.1.3, tất cả các cập nhật về tính năng và nâng cấp cho thư viện được tổng hợp trong file [Lịch sử thay đổi](https://github.com/thinh-vu/vnstock/blob/beta/changes_log.md).

## 2.2 🛠 Cài đặt vnstock
### Bước 1. Chọn phiên bản phù hợp

Để sử dụng phiên bản vnstock ổn định được cập nhật trên pypi.org, bạn có thể cài đặt bằng câu lệnh:
`pip install --upgrade vnstock`

<details>

<summary>Ngoài ra bạn cũng có thể cài đặt trực tiếp từ source code Github như sau (click để mở rộng) </summary>

> vnstock được phát triển thành hai nhánh riêng biệt. Bạn cần chọn phiên bản phù hợp và *copy câu lệnh tương ứng để thực hiện cài đặt ở bước tiếp theo*:

- Bản `beta` (nhận cập nhật mới nhất) được chia sẻ tại nhánh `beta` của Github repo.

  `pip install git+https://github.com/thinh-vu/vnstock.git@beta`

- Bản `stable` (đã phát triển ổn định) được chia sẻ qua pypi.org và nhánh `main` tại Github repo này. Để cài đặt bản stable bạn dùng câu lệnh đơn giản sau: 
`pip install vnstock` hoặc cài đặt trực tiếp từ Github với câu lệnh:

  `pip install git+https://github.com/thinh-vu/vnstock.git@main`

<details>
  <summary> Chọn xem nhánh phù hợp </summary>

  ![select_branch](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/vnstock_select_branch.jpeg)

</details>

</details>

### Bước 2. Chạy câu lệnh cài đặt

> Khi sử dụng file demo [vnstock_demo_index_all_functions_testing_2023_06_22.ipynb](https://github.com/thinh-vu/vnstock/blob/beta/demo/gen2_vnstock_demo_index_all_functions_testing_2023.ipynb) để bắt đầu, các câu lệnh cài đặt cần thiết đã được cung cấp sẵn để bạn thực thi (run).

**pip được sử dụng để cài đặt vnstock**. pip có sẵn trong hầu hết các bản phân phối Python được cài đặt. Phiên bản python cần thiết cho vnstock tối thiểu là 3.7. Bạn có thể paste câu lệnh đã copy ở Bước 1 và chạy nó trong môi trường Python bạn đang sử dụng.

- Jupyter Notebook/Jupyter Lab/Google Colab: Mở file demo notebook để chạy các lệnh có sẵn.
- CLI: Mở Terminal (macOS/Linux) hoặc Command Prompt (Windows Desktop) và paste dòng lệnh trên, bấm Enter để cài đặt. Lưu ý: Nếu sử dụng Windows và Python cài đặt với Anaconda thì chọn Anaconda Prompt để chạy lệnh thay vì Command Prompt mặc định.
 
## 2.3. Cài đặt các gói thư viện bắt buộc (gỡ lỗi)

Trong trường hợp bạn không sử dụng Google Colab là môi trường mặc định để chạy vnstock, bạn sẽ cần phải đảm bảo môi trường Python của mình có đầy đủ các gói phần mềm bắt buộc kèm theo (dependencies/requirements) để có thể chạy được `vnstock`. 
- Nếu cài Python với Anaconda, bạn có thể bỏ qua bước này.
- Nếu cài bản python thuần từ python.org hoặc Python từ Windows Store, bạn sẽ cần cài đặt thêm tối thiểu `pandas` và `requests` với công cụ `pip`.

Để quá trình cài đặt diễn ra đơn giản và suôn sẻ, bạn có thể làm theo các bước sau:
- Tải file [requirement.txt](https://github.com/thinh-vu/vnstock/blob/beta/requirements.txt) về máy
-  Mở Command Prompt / Terminal, rỏ tới thư mục chứa file `requirements.txt`, thông thường là `Downloads` bằng lệnh `cd  ĐỊA_CHỈ_THƯ_MỤC_CỦA_BẠN`
-  Chạy lệnh sau: `pip install -r requirements.txt`

Như vậy là qúa trình chuẩn bị để sử dụng `vnstock` đã hoàn thành. Chúc bạn thành công!

---

# III. 💻 Cách sử dụng các hàm trong vnstock

Bạn sẽ nắm được cách sử dụng các hàm của vnstock thông qua tài liệu hướng dẫn này, hoặc mở file demo [vnstock demo index](https://github.com/thinh-vu/vnstock/blob/beta/demo/gen2_vnstock_demo_index_all_functions_testing_2023.ipynb) để chạy các dòng lệnh mẫu, làm quen và xem kết quả trực tiếp.

Để nạp các hàm của vnstock vào dự án Python của bạn, cần `import` chúng thông qua câu lệnh như dưới đây. Như vậy mọi thứ đã sẵn sàng để truy cập dữ liệu do vnstock cung cấp thông qua các hàm được liệt kê trong tài liệu hướng dẫn.

```python
from vnstock import *
```

## 3.1. ☑ Danh sách cổ phiếu niêm yết (Listing)

### 3.1.1. 📰 Danh sách các công ty niêm yết
```python
listing_companies()
```
Hàm này đọc dữ liệu từ tệp csv đính kèm trên Github theo mặc định (trong thư mục /data của repo này). Bởi danh sách các công ty niêm yết thường không thay đổi liên tục nên việc này không gây trở ngại nhiều.

<details>
  <summary>Output</summary>

```
>>> listing_companies()
  ticker comGroupCode                                       organName                  organShortName organTypeCode comTypeCode  ... VNHEAL  VNIND   VNIT  VNMAT VNREAL  VNUTI
0    VVS   UpcomIndex  Công ty Cổ phần Đầu tư Phát triển Máy Việt Nam  Đầu tư Phát triển Máy Việt Nam            DN          CT  ...  False  False  False  False  False  False
1    XDC   UpcomIndex   Công ty TNHH MTV Xây dựng Công trình Tân Cảng    Xây dựng Công trình Tân Cảng            DN          CT  ...  False  False  False  False  False  False
2    HSV   UpcomIndex           Công ty Cổ phần Tập đoàn HSV Việt Nam                Gang Thép Hà Nội            DN          CT  ...  False  False  False  False  False  False
```

</details>


Ngoài ra, bạn có thể lấy danh sách các mã cổ phiếu niêm yết thông qua bộ lọc cổ phiếu với hàm `stock_screening_insights` ở mục 3.5.2. Bộ lọc cổ phiếu. Khi đó điều kiện lọc chỉ đơn giản là chọn đủ 3 sàn `HOSE, HNX, UPCOM` để trả về toàn bộ các mã cổ phiếu hoặc chọn cô phiếu của từng sàn riêng lẻ theo ý bạn.

## 3.2. 🏳 Phân tích cơ bản (Fundamental Analysis)

### 3.2.1. 🏚 Thông tin tổng quan công ty

```python
company_overview('TCB')
```

<details>
  <summary>Output</summary>

  ```
  >>> company_overview('TCB')
    exchange    shortName  industryID industryIDv2   industry  ... deltaInMonth deltaInYear  outstandingShare  issueShare  ticker
  0     HOSE  Techcombank         289         8355  Ngân hàng  ...       -0.027      -0.038            3510.9      3510.9     TCB
  ```

</details>

### 3.2.2. Thông tin công ty (Mới)

```python
company_profile ('TCB')
```

<details>
  <summary>Output</summary>

  ```
  >>> company_profile ('TCB')
      id                                      companyName  ...                                    keyDevelopments                                 businessStrategies
  0  None  Ngân hàng Thương mại Cổ phần Kỹ thương Việt Nam  ...    Huy động vốn; Tín dụng; Liên kết và đầu tư t...    Áp dụng công nghệ tiên tiến hiện đại trong c...

  [1 rows x 9 columns]
  ```

</details>

### 3.2.3. Danh sách cổ đông (Mới)

```python
company_large_shareholders ('TCB')
```

<details>
  <summary>Output</summary>
```
  >>> company_large_shareholders ('TCB')
    ticker                     shareHolder  shareOwnPercent
  0    TCB  Công ty Cổ phần Tập đoàn Masan           0.1491
  1    TCB           Nguyễn Thị Thanh Thủy           0.0495
  2    TCB            Nguyễn Thị Thanh Tâm           0.0495
  3    TCB                     Hồ Anh Minh           0.0392
  4    TCB               Nguyễn Phương Hoa           0.0216
  5    TCB               Nguyễn Hương Liên           0.0198
  6    TCB                     HỒ HÙNG ANH           0.0112
  7    TCB              Nguyễn Thiều Quang           0.0086
  8    TCB                     Hồ Thủy Anh           0.0064
  9    TCB                            Khác           0.0292
  ```
</details>

### 3.2.4. Các chỉ số tài chính cơ bản (Mới)

```python
company_fundamental_ratio (symbol='TCB', mode='simplify', missing_pct=0.8)
```

<details>
  <summary>Output</summary>

  ```
  >>> company_fundamental_ratio (symbol='TCB', mode='simplify', missing_pct=0.8)
    ticker costOfFinancing.industryAvgValue interestMargin.industryAvgValue  ... loanOnDeposit.industryAvgValue equityOnTotalAsset.industryAvgValue badDebtOnAsset.industryAvgValue
  0    TCB                            0.055                           0.035  ...                          0.969                               0.086                           0.016

  [1 rows x 14 columns]
  ```

</details>

### 3.2.5. Mức biến động giá cổ phiếu (Mới)

```python
ticker_price_volatility (symbol='TCB')
```

<details>
  <summary>Output</summary>

  ```
  >>> ticker_price_volatility (symbol='TCB')
    ticker  ticker_highestPrice  ticker_lowestPrice  ticker_highestPricePercent  ticker_lowestPricePercent
  0    TCB              38950.0             20700.0                      -0.114                      0.667
  ```

</details>

### 3.2.6. Thông tin giao dịch nội bộ (Mới)

```python
company_insider_deals (symbol='TCB', page_size=20, page=0)
```

<details>
  <summary>Output</summary>

  ```
  >>> company_insider_deals (symbol='TCB', page_size=20, page=0)
    ticker dealAnnounceDate        dealMethod dealAction  dealQuantity  dealPrice  dealRatio
  0     TCB       2023-08-31       Cổ đông lớn        Bán     -300000.0    34500.0      0.000
  1     TCB       2023-08-22  Cổ đông sáng lập        Mua           0.0    33100.0      0.042
  2     TCB       2023-07-20    Cổ đông nội bộ        Bán     -933169.0    31900.0      0.082
  3     TCB       2023-04-18       Cổ đông lớn        Bán      -30000.0    29150.0      0.184
  4     TCB       2022-12-28  Cổ đông sáng lập        Bán      -21496.0    26150.0      0.319
  5     TCB       2022-11-28    Cổ đông nội bộ        Mua      200000.0    24600.0      0.402
  13    TCB       2022-09-06    Cổ đông nội bộ        Mua      350000.0    38650.0     -0.107
  12    TCB       2022-09-06    Cổ đông nội bộ        Mua      111404.0    38650.0     -0.107
  11    TCB       2022-09-06    Cổ đông nội bộ        Mua      100021.0    38650.0     -0.107
  10    TCB       2022-09-06    Cổ đông nội bộ        Mua       97770.0    38650.0     -0.107
  9     TCB       2022-09-06    Cổ đông nội bộ        Mua       80945.0    38650.0     -0.107
  8     TCB       2022-09-06    Cổ đông nội bộ        Mua       55764.0    38650.0     -0.107
  7     TCB       2022-09-06    Cổ đông nội bộ        Mua       42118.0    38650.0     -0.107
  6     TCB       2022-09-06    Cổ đông nội bộ        Mua        5318.0    38650.0     -0.107
  14    TCB       2022-08-08    Cổ đông nội bộ        Bán     -100000.0    39200.0     -0.120
  15    TCB       2022-05-10  Cổ đông sáng lập        Bán     -868500.0    38700.0     -0.109
  16    TCB       2022-04-05  Cổ đông sáng lập        Bán     -150000.0    49050.0     -0.297
  17    TCB       2022-03-23    Cổ đông nội bộ        Bán     -200000.0    49600.0     -0.304
  18    TCB       2021-10-26    Cổ đông nội bộ        Bán      -35704.0    51000.0     -0.324
  19    TCB       2021-10-14  Cổ đông sáng lập        Mua      300000.0    52500.0     -0.343

  ```

</details>

### 3.2.7. Danh sách công ty con, công ty liên kết (Mới)

```python
company_subsidiaries_listing (symbol='TCB', page_size=100, page=0)
```

<details>
  <summary>Output</summary>

  ```

  >>> company_subsidiaries_listing (symbol='TCB', page_size=100, page=0)
    ticker                                     subCompanyName  subOwnPercent
  0    TCB  Công ty TNHH MTV Quản Lý Nợ Và Khai Thác Tài S...          1.000
  1    TCB              Công ty Cổ phần Chứng khoán Kỹ Thương          0.942
  2    TCB              Công ty Cổ phần Quản Lý Quỹ Kỹ Thương          0.900
  3    TCB  Tổng Công ty Cổ phần Xuất nhập khẩu và Xây dựn...          0.004
  4    TCB            Tổng Công ty Hàng không Việt Nam - CTCP          0.000
  5    TCB          Công ty Tài Chính TNHH MTV Lotte Việt Nam          0.000

  ```

</details>

### 3.2.8. Ban lãnh đạo công ty (Mới)

```python
company_officers (symbol='TCB', page_size=20, page=0)
```

<details>
  <summary>Output</summary>

  ```
  >>> company_officers (symbol='TCB', page_size=10, page=0)
    ticker            officerName                 officerPosition  officerOwnPercent
  0    TCB  Nguyễn Thị Thanh Thủy                            None             0.0495
  1    TCB   Nguyễn Thị Thanh Tâm                            None             0.0495
  2    TCB            Hồ Anh Minh                            None             0.0392
  3    TCB      Nguyễn Phương Hoa                            None             0.0216
  4    TCB      Nguyễn Hương Liên                            None             0.0198
  5    TCB            HỒ HÙNG ANH                            None             0.0112
  6    TCB     Nguyễn Thiều Quang  Phó Chủ tịch Hội đồng Quản trị             0.0086
  7    TCB            Hồ Thủy Anh                            None             0.0064
  8    TCB   Nguyễn Cảnh Sơn Tùng                            None             0.0060
  9    TCB        Nguyễn Cảnh Sơn  Phó Chủ tịch Hội đồng Quản trị             0.0051

  ```

</details>

### 3.2.9. Thông tin sự kiện quyền (Mới)

```python
company_events (symbol='TPB', page_size=10, page=0)
```

<details>
  <summary>Output</summary>

  ```
  >>> company_events (symbol='TPB', page_size=10, page=0)
          id ticker  price  priceChange  priceChangeRatio  ...             exerDate         regFinalDate          exRigthDate                                          eventDesc eventNote
  0  2563370    TPB  18100         -350            -0.019  ...  2023-07-07 00:00:00  1753-01-01 00:00:00  1753-01-01 00:00:00  <p>Ngân hàng Thương mại Cổ phần Tiên Phong (TP...      None
  1  2563135    TPB  18535         -215            -0.011  ...  2023-06-09 00:00:00  2023-06-12 00:00:00  2023-06-09 00:00:00  <p>Ngân hàng Thương mại Cổ phần Tiên Phong (TP...      None
  2  2561933    TPB  15668          -64            -0.004  ...  2023-04-26 00:00:00  2023-03-29 00:00:00  2023-03-28 00:00:00  <p>Ngân hàng Thương mại Cổ phần Tiên Phong (TP...      None
  3  2561033    TPB  15441          -97            -0.006  ...  2023-04-03 00:00:00  2023-03-21 00:00:00  2023-03-20 00:00:00  <p>Ngân hàng Thương mại Cổ phần Tiên Phong (TP...      None
  4  2560718    TPB  14567            0             0.000  ...  1753-01-01 00:00:00  2023-01-17 00:00:00  2023-01-16 00:00:00  <p>Ngân hàng Thương mại Cổ phần Tiên Phong (TP...      None
  5  2517318    TPB  25832          453             0.018  ...  2022-04-26 00:00:00  2022-03-28 00:00:00  2022-03-25 00:00:00  <p>Ngân hàng Thương mại Cổ phần Tiên Phong (TP...      None
  6  2406108    TPB  27192            0             0.000  ...  2022-01-13 00:00:00  1753-01-01 00:00:00  1753-01-01 00:00:00  <DIV style="FONT-FAMILY: Arial; FONT-SIZE: 10p...
  7  2395935    TPB  24936          719             0.030  ...  2021-12-20 00:00:00  2021-12-21 00:00:00  2021-12-20 00:00:00  <DIV style="FONT-FAMILY: Arial; FONT-SIZE: 10p...
  8  2235221    TPB  31480          371             0.012  ...  2022-09-15 00:00:00  1753-01-01 00:00:00  1753-01-01 00:00:00  <DIV style="FONT-FAMILY: Arial; FONT-SIZE: 10p...
  9  2215176    TPB  30665          519             0.017  ...  1753-01-01 00:00:00  2021-10-11 00:00:00  2021-10-08 00:00:00  <DIV style="FONT-FAMILY: Arial; FONT-SIZE: 10p...

  [10 rows x 15 columns]

  ```

</details>


### 3.2.10. Tin tức công ty (Mới)

```python
company_news (symbol='TCB', page_size=10, page=0)
```

<details>
  <summary>Output</summary>

  ```
  >>> company_news (symbol='TCB', page_size=10, page=0)
    ticker  price  priceChange  priceChangeRatio  priceChangeRatio1W  priceChangeRatio1M        id                                              title source          publishDate
  0    TCB  34500          500             0.015               0.021               0.006  10915190  TCB:  Báo cáo kết quả giao dịch cổ phiếu của n...   HOSE  2023-08-31 11:12:00
  1    TCB  33650         -150            -0.004               0.035               0.004  10909083  TCB:  CBTT về việc giải tỏa cổ phiếu hạn chế c...   HOSE  2023-08-25 16:35:00
  2    TCB  33100          350             0.011              -0.028               0.020  10905062  TCB: Con gái Chủ tịch đăng ký mua trên 82 triệ...   HOSE  2023-08-22 11:19:00
  3    TCB  32750          250             0.008              -0.031               0.014  10904072  Báo cáo kết quả phân phối chứng quyền có bảo đ...   HOSE  2023-08-21 16:21:00
  4    TCB  34700         -600            -0.017               0.036               0.088  10900206  Thông báo phát hành chứng quyền và Bản cáo bạc...   HOSE  2023-08-17 14:48:00
  5    TCB  34700         -600            -0.017               0.036               0.088  10899331  Giấy chứng nhận chào bán chứng quyền có bảo đả...   HOSE  2023-08-17 08:55:00
  6    TCB  33800          150             0.004              -0.016               0.058  10895913  Thông báo hủy đợt phát hành chứng quyền có bảo...   HOSE  2023-08-14 17:36:00
  7    TCB  33500         -500            -0.015               0.000               0.047  10892819  TCB:  CBTT Chuyển quyền sở hữu cổ phiếu từ Côn...   HOSE  2023-08-10 17:55:00
  8    TCB  34000            0             0.000               0.003               0.063  10891020  Thông báo phát hành chứng quyền và Bản cáo bạc...   HOSE  2023-08-09 16:55:00
  9    TCB  34000            0             0.000               0.003               0.063  10890346  Báo cáo kết quả phân phối chứng quyền có bảo đ...   HOSE  2023-08-09 10:26:00

  ```

</details>

### 3.2.11. 🧧 Lịch sử chi trả cổ tức

```python
dividend_history("VNM")
```

<details>
  <summary>Output</summary>

```
   exerciseDate  cashYear  cashDividendPercentage issueMethod
0      10/01/22      2021                    0.14        cash
1      07/09/21      2021                    0.15        cash
2      07/06/21      2020                    0.11        cash
3      05/01/21      2020                    0.10        cash
```
</details>

## 3.3. 💰 Phân tích tài chính (Financial Analysis)

### 3.3.1. Bộ chỉ số tài chính
```python
financial_ratio(symbol="TCB", report_range='yearly', is_all=False)
```
Trong đó:
- `report_range` nhận 1 trong 2 giá trị: `yearly` cho phép trả về chỉ số theo năm, `quarterly` trả về dữ liệu theo quý
- `is_all` có giá trị mặc định là `True` cho phép lấy chỉ số qua tất cả các kỳ (năm hoặc quý), `False` cho phép lấy các kỳ gần nhất (5 năm hoặc 10 quý gần đây).

<details>
  <summary>Output</summary>

  ```
>>> financial_ratio('TCB', 'yearly')
year                      2022   2021   2020   2019   2018
ticker                     TCB    TCB    TCB    TCB    TCB
priceToEarning             4.5    9.7    9.0    8.2   10.7
priceToBook                0.8    1.9    1.5    1.3    1.8
roe                      0.197  0.217  0.181  0.178  0.215
roa                      0.032  0.036   0.03  0.029  0.029
earningPerShare           5729   5132   3504   2869   2410
bookValuePerShare        32248  26452  21214  17679  14749
interestMargin           0.053  0.057  0.049  0.043  0.041
nonInterestOnToi         0.259   0.28  0.307  0.323  0.379
badDebtPercentage        0.007  0.007  0.005  0.013  0.018
provisionOnBadDebt       1.573  1.629   1.71  0.948  0.851
costOfFinancing          0.028  0.022  0.031  0.038  0.041
equityOnTotalAsset       0.162  0.164   0.17  0.162  0.161
equityOnLoan              0.27  0.268  0.269  0.269  0.324
costToIncome             0.328  0.301  0.319  0.347  0.318
equityOnLiability          0.2    0.2    0.2    0.2    0.2
epsChange                0.116  0.465  0.221  0.191  0.313
assetOnEquity              6.2    6.1    5.9    6.2    6.2
preProvisionOnToi        0.537  0.554  0.542   0.52  0.542
postTaxOnToi               0.5  0.497  0.465  0.485  0.462
loanOnEarnAsset          0.684  0.665  0.681  0.649  0.537
loanOnAsset              0.602  0.611  0.631  0.602  0.498
loanOnDeposit            1.173  1.104    1.0  0.998  0.794
depositOnEarnAsset       0.583  0.603   0.68  0.651  0.676
badDebtOnAsset           0.004  0.004  0.003  0.008  0.009
liquidityOnLiability     0.347  0.382  0.372  0.411  0.531
payableOnEquity            5.2    5.1    4.9    5.2    5.2
cancelDebt               0.002  0.004  0.013  0.002  0.008
bookValuePerShareChange  0.219  0.247    0.2  0.199  0.923
creditGrowth             0.211  0.252  0.202  0.443 -0.006
  ```
</details>


### 3.3.2. 💵 Báo cáo kết quả kinh doanh, cân đối kế toán và lưu chuyển tiền tệ

#### 3.3.2.1. 📄 Báo cáo kinh doanh

![income_statement](https://raw.githubusercontent.com/thinh-vu/vnstock/main/src/financial_income_statement.png)
```python
financial_flow(symbol="TCB", report_type='incomestatement', report_range='quarterly')
```


<details>
  <summary>Output</summary>

```
        ticker  revenue  yearRevenueGrowth  quarterRevenueGrowth costOfGoodSold grossProfit  ...  investProfit  serviceProfit  otherProfit  provisionExpense operationIncome  ebitda
index                                                                                        ...
2021-Q4    TCB     7245              0.328                 0.074           None        None  ...           279           2103          532              -627            6767    None
2021-Q3    TCB     6742              0.310                 0.023           None        None  ...           384           1497          156              -589            6151    None
2021-Q2    TCB     6588              0.674                 0.076           None        None  ...           717           1457          444              -598            6615    None
2021-Q1    TCB     6124              0.454                 0.122           None        None  ...           812           1325          671              -851            6369    None
```
</details>

#### 3.3.2.2. 🧾 Bảng cân đối kế toán

![balance_sheet](https://raw.githubusercontent.com/thinh-vu/vnstock/main/src/financial_balancesheet.png)
```python
financial_flow(symbol="TCB", report_type='balancesheet', report_range='quarterly')
```

<details>
  <summary>Output</summary>

```
        ticker shortAsset  cash shortInvest shortReceivable inventory longAsset  fixedAsset  ...  payableInterest  receivableInterest deposit otherDebt  fund  unDistributedIncome  minorShareHolderProfit  payable
index                                                                                        ...

2021-Q4    TCB       None  3579        None            None      None      None        7224  ...             3098                5808  314753     33680  9156                47469                     845   475756
2021-Q3    TCB       None  3303        None            None      None      None        7106  ...             3074                6224  316376     34003  6784                45261                     753   453251
2021-Q2    TCB       None  3554        None            None      None      None        6739  ...             2643                5736  289335     27678  6790                40924                     659   420403
2021-Q1    TCB       None  4273        None            None      None      None        4726  ...             2897                5664  287446     26035  6790                36213                     563   3837
```
</details>

#### 3.3.2.3. 💶 Báo cáo lưu chuyển tiền tệ

```python
financial_flow(symbol="TCB", report_type='cashflow', report_range='quarterly')
```

<details>
  <summary>Output</summary>

```
        ticker  investCost  fromInvest  fromFinancial  fromSale  freeCashFlow
index
2021-Q4    TCB        -280        -276              0     -9328             0
2021-Q3    TCB        -180        -179             60     17974             0
2021-Q2    TCB        -337        -282              0     11205             0
2021-Q1    TCB        -143        -143              0     -6954             0
```
</details>

### 3.3.3. Chỉ số định giá

```python
stock_evaluation (symbol='TCB', period=1, time_window='D')
```

<details>
  <summary>Output</summary>

  ```
  >>> stock_evaluation (symbol='TCB', period=1, time_window='D')
      ticker   fromDate     toDate   PE   PB  industryPE  vnindexPE  industryPB  vnindexPB
  0      TCB 2022-09-05 2022-09-05  6.4  1.2         9.8       14.0         1.7        2.0
  1      TCB 2022-09-06 2022-09-06  6.4  1.2         9.9       14.0         1.7        2.0
  2      TCB 2022-09-07 2022-09-07  6.2  1.2         9.6       13.7         1.7        2.0
  3      TCB 2022-09-08 2022-09-08  6.2  1.2         9.4       13.5         1.6        1.9
  4      TCB 2022-09-09 2022-09-09  6.2  1.2         9.5       13.7         1.6        2.0
  ..     ...        ...        ...  ...  ...         ...        ...         ...        ...
  245    TCB 2023-08-25 2023-08-25  6.7  1.0         9.3       14.8         1.5        1.7
  246    TCB 2023-08-28 2023-08-28  6.7  1.0         9.3       15.0         1.6        1.7
  247    TCB 2023-08-29 2023-08-29  6.7  1.0         9.4       15.1         1.6        1.7
  248    TCB 2023-08-30 2023-08-30  6.7  1.0         9.5       15.2         1.6        1.7
  249    TCB 2023-08-31 2023-08-31  6.8  1.0         9.6       15.4         1.6        1.7

  [250 rows x 9 columns]
  ```
</details>

## 3.4. Phân tích kỹ thuật (Technical Analysis)

### 3.4.1 📈 Truy xuất dữ liệu giá lịch sử

> Phiên bản API hiện tại cho phép truy cập giá lịch sử tối đa đến ngày 2012-03-20 đối với tất cả mã cổ phiếu. Nếu bạn có nhu cầu lấy lịch sử giá từ thời điểm thị trường chứng khoán bắt đầu hoạt động (REE là mã cổ phiếu có giao dịch sớm nhất thị trường vào 2000-07-31), hãy là một thành viên của [vnstock membership](https://www.facebook.com/groups/vnstock) để được hỗ trợ.

vnstock cho phép người dùng tải xuống dữ liệu lịch sử giao dịch của `mã cổ phiếu, chỉ số, hợp đồng phái sinh`.
- Dữ liệu `cổ phiếu` và `chỉ số` hỗ trợ 5 mức độ chi tiết theo khoảng thời gian bao gồm: 1 phút, 15 phút, 30 phút, 1 giờ, 1 ngày. 
- Dữ liệu `phái sinh` hỗ trợ 8 mức độ chi tiết theo khoảng thời gian bao gồm: 1 phút, 3 phút, 5 phút, 15 phút, 30 phút, 45 phút, 1 giờ, 1 ngày
- Trường dữ liệu `time` sẽ là giá trị ngày tháng `YYYY-mm-dd` nếu `resolution` nhập vào là `1D`, trong khi `resolution` là cấp độ phút và giờ sẽ cho thêm thông tin thời gian giờ/phút.
- Đơn vị giá OHLC được làm tròn, chỉ lấy phần nguyên. Đơn vị tính là VND.

Trong ví dụ dưới đây, dữ liệu giá được truy xuất theo cấp độ ngày.

```python
df =  stock_historical_data(symbol='GMD', 
                            start_date="2021-01-01", 
                            end_date='2022-02-25', resolution='1D', type='stock')
print(df)
```
- Mới: 
  - Lưu ý: Đối với mức độ chi tiết của dữ liệu (resolution) nhỏ hơn 1 ngày (1D), API này chỉ cho phép truy ngược lại trong  khoảng thời gian 3-4 tháng. Bạn có thể gặp lỗi khi cố gắng lấy dữ liệu cũ hơn trong thời gian dài.
  - Giá trị mà tham số `resolution` có thể nhận là `1D` (mặc định, 1 ngày), '1' (1 phút), 3 (3 phút), 5 (5 phút), 15 (15 phút), 30 (30 phút), 45 (45 phút), '1H' (hàng giờ).
  - `type = 'stock'` cho phép lấy dữ liệu giá của mã cổ cổ phiếu, `type = 'index'` cho phép lấy dữ liệu giá của mã chỉ số, và `type='derivative` cho phép lấy dữ liệu phái sinh. Các mã được hỗ trợ bao gồm (nhưng không giới hạn): VNINDEX, VN30, HNX, HNX30, UPCOM, VNXALLSHARE, VN30F1M, VN30F2M, VN30F1Q, VN30F2Q

Bạn cũng có thể viết hàm theo dạng rút gọn như dưới đây, điều này đúng với tất cả các hàm, miễn là thông số được nhập vào đúng thứ tự:

  - Lấy dữ liệu lịch sử cổ phiếu
  ```python
  df = stock_historical_data("GMD", "2021-01-01", "2022-02-25", "1D", 'stock')
  print(df)
  ```
Và đây là kết quả

<details>
  <summary>Output</summary>

  ```{r, engine='python', count_lines}
   time        open     high     low      close    volume
0  2021-01-04  32182.0  33157.0  31987.0  32279.0  4226500
1  2021-01-05  32279.0  33596.0  31938.0  32962.0  4851900
2  2021-01-06  33352.0  33352.0  32279.0  32572.0  3641300
  ```

</details>

- Lấy dữ liệu lịch sử của mã chỉ số
```python
df = stock_historical_data("VNINDEX", "2021-01-01", "2022-02-25", "1D", 'index')
print(df)
```

- Lấy dữ liệu lịch sử của hợp đồng phái sinh
```python
df = stock_historical_data("VN30F1M", "2023-07-01", "2023-07-24", "1D", 'derivative')
print(df)
```

## 3.5. Lựa chọn cổ phiếu (Stock Screening)

### 3.5.1. So sánh các cổ phiếu tiềm năng

#### 3.5.1.1. 📊 Bảng giá (Price board)

Bạn có thể tải xuống bảng giá của một danh sách các cổ phiếu được chọn để phân tích, thiết lập thuật toán dễ dàng hơn (khi xuất ra Google Sheets/Excel) so với việc xem trực tiếp trên bảng giá của các công ty chứng khoán.

<details>
  <summary>Minh họa Bảng giá TCBS</summary>

  ![price_board](https://raw.githubusercontent.com/thinh-vu/vnstock/main/src/tcbs_trading_board_sector.png)

</details>


##### a. Thông tin bước giá, khối lượng và khớp lệnh

```python
price_depth('TCB,SSI,VND')
```
Sử dụng hàm này cho phép thống kê các bước giá và khối lượng trên bảng giá của một hoặc một danh sách các mã cổ phiếu. Bạn có thể sử dụng kết hợp hàm này với hàm `price_board` để kết hợp các thông tin đa dạng về giá, khối lượng, chỉ số, thông tin giao dịch để chọn lọc và theo dõi cổ phiếu theo mục đích sử dụng của mình.

<details>
  <summary>Output</summary>

  >>> price_depth('TCB,SSI,VND')
  Mã CP  Giá tham chiếu  Giá Trần  Giá Sàn  Giá mua 3 KL mua 3  Giá mua 2 KL mua 2  Giá mua 1  ... KL bán 1  Giá bán 2  KL bán 2  Giá bán 3 KL bán 3  Tổng Khối Lượng ĐTNN Mua  ĐTNN Bán  ĐTNN Room
0   TCB           31950     34150    29750      31900       10      31850      130      31800  ...     9240      32000     19940      32049     7750           447200        0         0          0     
1   SSI           28400     30350    26450      28450      100      28400     9850      28350  ...    30640      28550     22730      28600    48410          1610280   142759     17353  803963854     
2   VND           17950     19200    16700      18450    11620      18400    38790      18350  ...    73180      18550     87830      18600   223700          4360710   152966      8355  932083910     

[3 rows x 22 columns]

</details>


##### b. Thông tin giao dịch bổ sung và các chỉ số

```
price_board('TCB,SSI,VND')
```
Hàm này cho phép tải về thông tin giá, khối lượng và các chỉ số quan trọng cho một hoặc một danh sách mã cổ phiếu. Sử dụng kết hợp với hàm `price_depth` cho hiệu quả tốt nhất.

<details>
  <summary>Output</summary>

```
>>> price_board('TCB,SSI,VND')
  Mã CP  Giá Khớp Lệnh  KLBD/TB5D  T.độ GD  KLGD ròng(CM)  ...  vnid1m  vnid3m  vnid1y  vnipe    vnipb
0   TCB        48600.0        0.6     0.49         -23200  ...    -3.7    -2.0    22.4  17.99  2.46159
1   SSI        43300.0        0.5     0.50        -112200  ...    -3.7    -2.0    22.4  17.99  2.46159
2   VND        32600.0        0.7     0.68          37300  ...    -3.7    -2.0    22.4  17.99  2.46159
```
</details>


#### 3.5.1.2. 🏭 Phân tích chỉ số các cổ phiếu cùng ngành (Industry Analysis)

```python
industry_analysis("VNM", lang='vi)
```
- Trả về thông tin các mã cổ phiếu cùng ngành với mã cổ phiếu nằm trong cùng nhóm ngành với mã `VNM`.
- Tham số `lang='vi` mặc định trả về tên các chỉ số bằng tiếng Việt, đổi thành `en` để giữ nguyên chỉ số với tên tiếng Anh.

- Trong đó các chỉ số sau được thể hiện dưới dạng thập phân sử dụng để thể hiện chỉ số dưới dạng %: 
  ```dividend (Cổ tức), ROE, ROA, ebitOnInterest (Thanh toán lãi vay), currentPayment (Thanh toán hiện hành), quickPayment (Thanh toán nhanh), grossProfitMargin (Biên LNG), postTaxMargin (Biên LNST), badDebtPercentage (Tỉ lệ nợ xấu), debtOnEquity (Nợ/Vốn CSH), debtOnEbitda (Nợ/EBITDA), income5year (LNST 5 năm),  sale5year (Doanh thu 5 năm), income1quarter (LNST quý gần nhất), sale1quarter (Doanh thu quý gần nhất), nextIncome (LNST năm tới), nextSale (Doanh thu quý tới)```
- Lưu ý: Tên các column có thể chưa được chuyển đổi đầy đủ thành tiếng Việt. Nếu gặp chỉ số nào chưa được chuyển đổi tên thành tiếng Việt, bạn vui lòng comment cho tác giả nhé.

<details>
  <summary>Output</summary>

```
>>> industry_analysis('VNM', label='vi')
Mã CP                          VNM     MSN    MCH    QNS    KDC     IDP    SBT    MML    PAN    MCM    VSF    VOC    OCH    VSN    CLX    LSS     KTC    HSL    HKB
Vốn hóa (tỷ)                  None  107634  51307  17543  16102   13204  11478  10108   4303   4232   3979   2890   1680   1618   1274    932     383    219     46
Giá                           None   75600  71603  49149  62600  224000  15500  30900  20600  38473   7958  23727   8400  19994  14713  12500   10500   6180    900
Số phiên tăng/giảm liên tiếp  None       3      2      4      0      -3      3      1     -1      1     -2      0      0      0      1      3       0     -1      0
P/E                            NaN    49.2    9.1   12.3 -215.9    16.7   16.6  -18.7   13.2   11.7 -384.1    2.4   15.2   11.9    7.1   23.5    37.3   14.6   -0.8
PEG                            NaN    -0.6   -8.0    0.9    1.9    -1.6   -1.4    0.1   -1.9    5.9    4.0    0.0   -0.1   -1.6    1.1    2.2    -0.8    0.8    0.5
P/B                            NaN     4.1    2.2    2.3    2.5     6.5    1.2    1.9    1.0    1.8    1.7    1.1    1.3    1.2    0.8    0.6     1.0    0.5    0.2
EV/EBITDA                      NaN    20.0    8.2   10.4   36.1    13.1   13.7 -267.0    7.2   11.4   25.9   -8.9    6.3    8.3   10.5    6.5    20.0   12.8   -3.1
Cổ tức                         NaN   0.009    0.0    0.0  0.086   0.033    0.0    0.0    0.0    0.0    0.0    0.0    0.0    0.0    0.0    0.0     0.0    0.0    0.0
ROE                            NaN   0.081  0.277  0.195 -0.011   0.442  0.076 -0.098  0.075  0.159 -0.005  0.591  0.086  0.107  0.118  0.025   0.025  0.036 -0.263
ROA                            NaN   0.016  0.175  0.128 -0.006    0.22  0.025 -0.042  0.021   0.14 -0.001  0.484  0.049  0.067  0.082  0.014   0.007  0.031  -0.15
Thanh toán lãi vay             NaN     0.5    9.1    8.5   -0.2    19.4    0.9   -0.8    1.3    NaN    0.3   -2.0   -3.2   67.7   22.1    2.2     0.9    6.9   -4.4
Thanh toán hiện hành           NaN     0.8    2.7    1.8    1.6     1.5    1.2    1.4    1.3    8.6    1.0    4.2    1.9    2.5    3.1    1.3     0.9    9.7    0.3
Thanh toán nhanh               NaN     0.6    2.5    1.4    1.2     1.3    0.9    1.1    0.9    7.7    0.4    3.4    1.7    1.7    2.9    0.3     0.5    8.6    0.3
Biên LNG                       NaN   0.272  0.432   0.28  0.188   0.385  0.115  0.117  0.171  0.323  0.067    NaN  0.286  0.247  0.264  0.121   0.035  0.039  0.728
Biên LNST                      NaN   0.011  0.228  0.149    NaN   0.138  0.026    NaN  0.016  0.138    NaN  6.467    NaN  0.039  0.372  0.017   0.004  0.024    NaN
Nợ/Vốn CSH                     NaN     2.0    0.3    0.4    0.6     0.4    1.3    1.0    0.7    0.0    1.5    0.1    0.1    0.0    0.0    0.4     2.3    0.0    0.5
Nợ/EBITDA                      NaN     7.6    1.1    1.5    8.1     0.7    7.2  -88.3    3.4    0.1   12.3   -1.1    0.7    1.1    0.4    2.6    15.5    0.8   -2.0
LNST 5 năm                     NaN   0.028  0.207  0.046  -0.04     NaN   0.12    NaN  0.001  0.098    NaN    NaN    NaN  0.012  0.065   -0.1  -0.157 -0.081    NaN
Doanh thu 5 năm                NaN   0.152  0.153  0.016  0.123     NaN   0.22 -0.239  0.274  0.049 -0.053 -0.181 -0.018 -0.002  0.088 -0.008   0.067   0.16 -0.474
LNST quý gần nhất              NaN  -0.519 -0.255 -0.258    NaN   0.316  0.443    NaN -0.694  0.397    NaN    NaN    NaN -0.131  0.092    NaN  36.983  -0.44    NaN
Doanh thu quý gần nhất         NaN  -0.094 -0.252  0.093 -0.302  -0.057 -0.181  0.031 -0.352 -0.067  -0.31 -0.675 -0.197 -0.134 -0.123  0.102  -0.122 -0.142  0.009
LNST năm tới                   NaN   0.285   0.26  0.173 -0.202   0.074  0.047 -0.719 -0.041   0.04 -0.939  0.116  6.025 -0.034   0.09 -0.155   0.813  0.022    NaN
Doanh thu năm tới              NaN     0.2    0.3  0.162  0.283     0.1    0.1   -0.7   0.05   0.05   0.03   0.15   -0.5    0.1    0.3  -0.08   -0.06   0.02    NaN
RSI                            NaN    50.7   43.1   71.8   24.0    28.5   59.2   33.7   68.2   53.5   46.6   44.1   51.1   32.3   55.5   55.3    33.3   54.8   61.1
```
</details>


#### 3.5.1.3. 🔬 So sánh các chỉ số của danh sách các cổ phiếu tùy chọn
```python
stock_ls_analysis("TCB, BID, CEO, GMD", lang='vi')
```

<details>
  <summary>Output</summary>

![preview](./src/stock_ls_comparison.png)

```
  ticker  marcap  price  numberOfDays  priceToEarning  peg  priceToBook  valueBeforeEbitda  dividend  ...  debtOnEbitda  income5year  sale5year income1quarter  sale1quarter  nextIncome  nextSale   rsi    rs
0    GMD   15220  50500            -3            25.2  0.4          2.4               16.2       0.0  ...           1.8        0.092     -0.030          0.500         0.425         NaN       NaN  60.3  50.0
1    CEO   17062  66300             1           183.2 -0.8          5.7               81.8       0.0  ...           7.8       -0.099     -0.086            NaN         3.002      -1.469      -0.2  51.9  82.0
2    BID  225357  44550            -3            21.3  0.4          2.6                NaN       0.0  ...           NaN        0.115      0.154          0.083         0.000         NaN       NaN  49.1  34.0
3    TCB  178003  50700             1             9.9  0.2          1.9                NaN       0.0  ...           NaN        0.418      0.255          0.059         0.157         NaN       NaN  45.2  28.0
```

</details>


#### 3.5.1.4. ⭐ Đánh giá xếp hạng 
##### a. Đánh giá chung
![general_rating](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/general_rating.png)

```python
general_rating("VNM")
```

<details>
  <summary>Output</summary>

```
   stockRating  valuation  financialHealth  businessModel  businessOperation  rsRating  taScore  ... ticker highestPrice  lowestPrice  priceChange3m  priceChange1y  beta   alpha
0          2.4        1.5              4.8            3.0                3.2       1.0      1.0  ...    VNM     102722.2      78600.0         -0.092         -0.232  0.49 -0.0014
```
</details>

##### b. 🌱 Đánh giá mô hình kinh doanh
```python
biz_model_rating("VNM")
```

<details>
  <summary>Output</summary>

```
  ticker  businessModel  businessEfficiency  assetQuality  cashFlowQuality  bom  businessAdministration  productService  businessAdvantage  companyPosition  industry  operationRisk
0    VNM            3.0                   3             3                3    3                       3               3                  3                3         3              3
```
</details>

##### c. 🎮 Đánh giá hiệu quả hoạt động
```python
biz_operation_rating("VNM")
```

<details>
  <summary>Output</summary>

```
      industryEn loanGrowth depositGrowth netInterestIncomeGrowth netInterestMargin  ... last5yearsFCFFGrowth lastYearGrossProfitMargin lastYearOperatingProfitMargin  lastYearNetProfitMargin  TOIGrowth
0  Food Products       None          None                    None              None  ...                    2                         5                             3                        4       None
```
</details>

##### d. 📑 Đánh giá sức khỏe tài chính
```python
financial_health_rating("VNM")
```

<details>
  <summary>Output</summary>

```
      industryEn loanDeposit badLoanGrossLoan badLoanAsset provisionBadLoan ticker  financialHealth  netDebtEquity  currentRatio  quickRatio  interestCoverage  netDebtEBITDA
0  Food Products        None             None         None             None    VNM              4.8              4             5           5                 5              5
```
</details>

##### e. 💲 Đánh giá về Định giá
```python
valuation_rating("VNM")
```

<details>
  <summary>Output</summary>

```
      industryEn ticker  valuation  pe  pb  ps  evebitda  dividendRate
0  Food Products    VNM        1.5   2   1   1         1             3
```
</details>

##### f. 💳 Sức khỏe tài chính theo ngành
```python
industry_financial_health("VNM")
```

<details>
  <summary>Output</summary>

```
  industryEn loanDeposit badLoanGrossLoan badLoanAsset provisionBadLoan ticker  financialHealth  netDebtEquity  currentRatio  quickRatio  interestCoverage  netDebtEBITDA
0       None        None             None         None             None    VNM              3.4              4             4           3                 3              3
```
</details>

### 3.5.2. 🔎 Bộ lọc cổ phiếu

Bộ lọc cổ phiếu là một hàm cho phép bạn truy vấn và lọc các cổ phiếu theo nhiều tiêu chí đa dạng dựa trên dữ liệu phân tích của TCBS. Hàm này sẽ trả về một DataFrame chứa các thông tin toàn diện về các cổ phiếu thỏa mãn điều kiện lọc của bạn. Bạn có thể dùng DataFrame này để tiếp tục phân tích, biểu diễn hoặc xuất ra dữ liệu dạng bảng tính. Đây là cập nhật ưu việt giúp bạn tiết kiệm thời gian và công sức đáng kể khi làm việc với dữ liệu cổ phiếu, đồng thời cho phép lập trình để lọc là cập nhật danh sách cổ phiếu hiệu quả không cần sử dụng giao diện web từ công ty chứng khoán.

<details>
  <summary> Bộ lọc cổ phiếu TCBS </summary>

  ![stock_scanner](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/stock_scanner_tcbs.png)

</details>

Tham số
- params (dict): một từ điển chứa các tham số và giá trị của chúng cho việc lọc cổ phiếu. Các `key` là tên của các bộ lọc, và các `value` là một giá trị đơn hoặc một tupple gồm hai giá trị (min và max) cho bộ lọc đó. Đây là ví dụ cho tham số params được thiết lập đúng:
- drop_lang: Loại bỏ các cột dữ liệu sử dụng tên tiếng Việt (`vi`) hoặc Anh (`en`)

```python
params = {
            "exchangeName": "HOSE,HNX,UPCOM",
            "marketCap": (100, 1000),
            "dividendYield": (5, 10)
        }

# Áp dụng bộ lọc với hàm để lấy kết quả

df = stock_screening_insights (params, size=1700, drop_lang='vi')

```

<details>

<summary>Các bộ lọc gợi ý và tiêu chí hỗ trợ bao gồm</summary>

  a. BỘ LỌC GỢI Ý (PRESET)

    > Sử dụng các tiêu chí lọc như sau để thiết lập tham số params.

    - CANSLIM: epsGrowth1Year, lastQuarterProfitGrowth, roe, avgTradingValue20Day, relativeStrength1Month
    - Giá trị: roe, pe, avgTradingValue20Day
    - Cổ tức cao: dividendYield, avgTradingValue20Day
    - Phá nền mua: avgTradingValue20Day, forecastVolumeRatio, breakout: 'BULLISH'
    - Giá tăng + Đột biến khối lượng: avgTradingValue20Day, forecastVolumeRatio
    - Vượt đỉnh 52 tuần: avgTradingValue20Day, priceBreakOut52Week: 'BREAK_OUT'
    - Phá đáy 52 tuần: avgTradingValue20Day, priceWashOut52Week: 'WASH_OUT'
    - Uptrend ngắn hạn: avgTradingValue20Day, uptrend: 'buy-signal'
    - Vượt trội ngắn hạn: relativeStrength3Day, 
    - Tăng trưởng: epsGrowth1Year, roe, avgTradingValue20Day

  b. THÔNG TIN CHUNG

    - exchangeName: sàn giao dịch của cổ phiếu, ví dụ "HOSE", "HNX", hoặc "UPCOM". Bạn có thể dùng dấu phẩy để phân tách nhiều sàn, ví dụ "HOSE,HNX,UPCOM".
    - hasFinancialReport: Có báo cáo tài chính gần nhất. `1` nghĩa là có, `0` nghĩa là không.
    - industryName: Lọc các cổ phiếu theo ngành cụ thể. Giá trị dạng `Retail` cho ngành Bán lẻ. Các giá trị khác có thể là:
      - `Insurance`: Bảo hiểm
      - `Real Estate`: Bất động sản
      - `Technology`: Công nghệ thông tin
      - `Oil & Gas`: Dầu khí
      - `Financial Services`: Dịch vụ tài chính
      - `Utilities`: Điện, nước, xăng dầu và khí đốt
      - `Travel & Leisure`: Du lịch và giải trí
      - `Industrial Goods & Services`: Hàng và dịch vụ công nghiệp
      - `Personal & Household Goods`: Hàng cá nhân và gia dụng
      - `Chemicals`: Hóa chất
      - `Banks`: Ngân hàng
      - `Automobiles & Parts`: Ô tô và phụ tùng
      - `Basic Resources`: Tài nguyên cơ bản
      - `Food & Beverage`: Thực phẩm và đồ uống
      - `Media`: Truyền thông
      - `Telecommunications`: Viễn thông
      - `Construction & Materials`: Xây dựng và vật liệu
      - `Health Care`: Y tế
      - marketCap: vốn hóa thị trường của cổ phiếu tính bằng tỷ VND.
      - priceNearRealtime: giá hiện tại của cổ phiếu tính bằng VND.
      - foreignVolumePercent: tỷ lệ phần trăm khối lượng nước ngoài trong tổng khối lượng.
      - alpha: lợi nhuận vượt trội của cổ phiếu so với lợi nhuận thị trường.
      - beta: độ biến động của cổ phiếu so với thị trường.
      - freeTransferRate: tỷ lệ phần trăm cổ phiếu có thể chuyển nhượng tự do.
  
  c. TĂNG TRƯỞNG

    - revenueGrowth1Year: tốc độ tăng trưởng doanh thu trong năm qua.
    - revenueGrowth5Year: tốc độ tăng trưởng doanh thu trung bình trong 5 năm qua.
    - epsGrowth1Year: tốc độ tăng trưởng lợi nhuận trên mỗi cổ phiếu trong năm qua.
    - epsGrowth5Year: tốc độ tăng trưởng lợi nhuận trên mỗi cổ phiếu trung bình trong 5 năm qua.
    - lastQuarterRevenueGrowth: tốc độ tăng trưởng doanh thu trong quý gần nhất.
    - secondQuarterRevenueGrowth: tốc độ tăng trưởng doanh thu trong quý thứ hai.
    - lastQuarterProfitGrowth: tốc độ tăng trưởng lợi nhuận trong quý gần nhất.
    - secondQuarterProfitGrowth: tốc độ tăng trưởng lợi nhuận trong quý thứ hai.
  
  d. CHỈ SỐ TÀI CHÍNH
  
    - grossMargin: tỷ suất lợi nhuận gộp của cổ phiếu.
    - netMargin: tỷ suất lợi nhuận ròng của cổ phiếu.
    - roe: tỷ suất sinh lời về vốn chủ sở hữu của cổ phiếu.
    - doe: tỷ suất cổ tức về vốn chủ sở hữu của cổ phiếu.
    - dividendYield: tỷ suất cổ tức của cổ phiếu.
    - eps: lợi nhuận trên mỗi cổ phiếu của cổ phiếu tính bằng VND.
    - pe: tỷ số giá/lợi nhuận của cổ phiếu.
    - pb: tỷ số giá/giá trị sổ sách của cổ phiếu.
    - evEbitda: tỷ số giá trị doanh nghiệp/lợi nhuận trước thuế, lãi vay, khấu hao và amortization của cổ phiếu.
    - netCashPerMarketCap: tỷ số tiền mặt ròng/vốn hóa thị trường của cổ phiếu.
    - netCashPerTotalAssets: tỷ số tiền mặt ròng/tổng tài sản của cổ phiếu.
    - profitForTheLast4Quarters: tổng lợi nhuận trong 4 quý gần nhất của cổ phiếu tính bằng tỷ VND.
  
  e. BIẾN ĐỘNG GIÁ & KHỐI LƯỢNG

    - suddenlyHighVolumeMatching: tín hiệu chỉ ra nếu có sự tăng đột biến khối lượng khớp lệnh cho cổ phiếu này. 0 nghĩa là không, 1 nghĩa là có.
    - totalTradingValue: tổng giá trị giao dịch của cổ phiếu này tính bằng tỷ VND hôm nay.
    - avgTradingValue5Day: giá trị giao dịch trung bình của cổ phiếu này tính bằng tỷ VND trong 5 ngày.
    - avgTradingValue10Day: giá trị giao dịch trung bình của cổ phiếu này tính bằng tỷ VND trong 10 ngày.
    - avgTradingValue20Day: giá trị giao dịch trung bình của cổ phiếu này tính bằng tỷ VND trong 20 ngày.
    - priceGrowth1Week: tốc độ tăng trưởng giá của cổ phiếu trong tuần qua.
    - priceGrowth1Month: tốc độ tăng trưởng giá của cổ phiếu trong tháng qua.
    - percent1YearFromPeak: tỷ lệ phần trăm thay đổi của cổ phiếu từ giá cao nhất trong 1 năm.
    - percentAwayFromHistoricalPeak: tỷ lệ phần trăm thay đổi của cổ phiếu từ giá cao nhất lịch sử.
    - percent1YearFromBottom: tỷ lệ phần trăm thay đổi của cổ phiếu từ giá thấp nhất trong 1 năm.
    - percentOffHistoricalBottom: tỷ lệ phần trăm thay đổi của cổ phiếu từ giá thấp nhất lịch sử.
    - priceVsSMA5: mối quan hệ giữa giá hiện tại và SMA 5 ngày của cổ phiếu. Các giá trị có thể là "ABOVE", "BELOW", "CROSS_ABOVE", hoặc "CROSS_BELOW".
    - priceVsSma10: mối quan hệ giữa giá hiện tại và SMA 10 ngày của cổ phiếu. Các giá trị có thể là "ABOVE", "BELOW", "CROSS_ABOVE", hoặc "CROSS_BELOW".
    - priceVsSMA20: mối quan hệ giữa giá hiện tại và SMA 20 ngày của cổ phiếu. Các giá trị có thể là "ABOVE", "BELOW", "CROSS_ABOVE", hoặc "CROSS_BELOW".
    - priceVsSma50: mối quan hệ giữa giá hiện tại và SMA 50 ngày của cổ phiếu. Các giá trị có thể là "ABOVE", "BELOW", "CROSS_ABOVE", hoặc "CROSS_BELOW".
    - priceVsSMA100: mối quan hệ giữa giá hiện tại và SMA 100 ngày của cổ phiếu. Các giá trị có thể là "ABOVE", "BELOW", "CROSS_ABOVE", hoặc "CROSS_BELOW".
    - forecastVolumeRatio: tỷ số giữa khối lượng dự báo và khối lượng thực tế của cổ phiếu hôm nay.
    - volumeVsVSma5: tỷ số giữa khối lượng hiện tại và SMA khối lượng 5 ngày của cổ phiếu.
    - volumeVsVSma10: tỷ số giữa khối lượng hiện tại và SMA khối lượng 10 ngày của cổ phiếu.
    - volumeVsVSma20: tỷ số giữa khối lượng hiện tại và SMA khối lượng 20 ngày của cổ phiếu.
    - volumeVsVSma50: tỷ số giữa khối lượng hiện tại và SMA khối lượng 50 ngày của cổ phiếu.
  
  f. HÀNH VI THỊ TRƯỜNG

    - strongBuyPercentage: tỷ lệ phần trăm tín hiệu mua mạnh cho cổ phiếu này dựa trên phân tích kỹ thuật.
    - activeBuyPercentage: tỷ lệ phần trăm tín hiệu mua tích cực cho cổ phiếu này dựa trên phân tích kỹ thuật.
    - foreignTransaction: loại giao dịch nước ngoài cho cổ phiếu này hôm nay. Các giá trị có thể là "buyMoreThanSell", "sellMoreThanBuy", hoặc "noTransaction".
    - foreignBuySell20Session: giá trị mua bán ròng nước ngoài cho cổ phiếu này tính bằng tỷ VND trong 20 phiên.
    - numIncreaseContinuousDay: số ngày liên tiếp cổ phiếu này tăng giá.
    - numDecreaseContinuousDay: số ngày liên tiếp cổ phiếu này giảm giá.
  
  g. TÍN HIỆU KỸ THUẬT

    - rsi14: chỉ số sức mạnh tương đối (RSI) của cổ phiếu với chu kỳ 14 ngày.
    - rsi14Status: trạng thái của RSI cho cổ phiếu này. Các giá trị có thể là "intoOverBought", "intoOverSold", "outOfOverBought", hoặc "outOfOverSold".
    - tcbsBuySellSignal: tín hiệu mua bán cho cổ phiếu này dựa trên phân tích của TCBS. Các giá trị có thể là "BUY" hoặc "SELL".
    - priceBreakOut52Week: tín hiệu chỉ ra nếu có sự đột phá giá cho cổ phiếu này trong 52 tuần. Các giá trị có thể là "BREAK_OUT" hoặc "NO_BREAK_OUT".
    - priceWashOut52Week: tín hiệu chỉ ra nếu có sự rửa giá cho cổ phiếu này trong 52 tuần. Các giá trị có thể là "WASH_OUT" hoặc "NO_WASH_OUT".
    - macdHistogram: tín hiệu chỉ ra nếu có tín hiệu MACD histogram cho cổ phiếu này. Các giá trị có thể là "macdHistGT0Increase", "macdHistGT0Decrease", "macdHistLT0Increase", hoặc "macdHistLT0Decrease".
    - relativeStrength3Day: sức mạnh tương đối của cổ phiếu so với thị trường trong 3 ngày.
    - relativeStrength1Month: sức mạnh tương đối của cổ phiếu so với thị trường trong 1 tháng.
    - relativeStrength3Month: sức mạnh tương đối của cổ phiếu so với thị trường trong 3 tháng.
    - relativeStrength1Year: sức mạnh tương đối của cổ phiếu so với thị trường trong 1 năm.
    - tcRS: sức mạnh tương đối của TCBS của cổ phiếu so với thị trường.
    - sarVsMacdHist: tín hiệu chỉ ra nếu có tín hiệu SAR vs MACD histogram cho cổ phiếu này. Các giá trị có thể là "BUY" hoặc "SELL".
  
  h. TÍN HIỆU MUA/BÁN

    - bollingBandSignal: tín hiệu chỉ ra nếu có tín hiệu Bollinger Band cho cổ phiếu này. Các giá trị có thể là "BUY" hoặc "SELL".
    - dmiSignal: tín hiệu chỉ ra nếu có tín hiệu chỉ số chuyển động hướng (DMI) cho cổ phiếu này. Các giá trị có thể là "BUY" hoặc "SELL".
    - uptrend: tín hiệu chỉ ra nếu có tín hiệu xu hướng tăng cho cổ phiếu này. Các giá trị có thể là "buy-signal" hoặc "sell-signal".
    - breakout: tín hiệu chỉ ra nếu có tín hiệu đột phá cho cổ phiếu này. Các giá trị có thể là "BULLISH" hoặc "BEARISH".
  
  i. TCBS ĐÁNH GIÁ

    - tcbsRecommend: tín hiệu chỉ ra nếu có khuyến nghị của TCBS cho cổ phiếu này. Các giá trị có thể là "BUY" hoặc "SELL".
    - stockRating: điểm đánh giá cổ phiếu cho cổ phiếu này dựa trên phân tích của TCBS. Điểm từ 1 đến 5, với 5 là tốt nhất.
    - businessModel: điểm đánh giá mô hình kinh doanh cho cổ phiếu này dựa trên phân tích của TCBS. Điểm từ 1 đến 5, với 5 là tốt nhất.
    - businessOperation: điểm đánh giá hoạt động kinh doanh cho cổ phiếu này dựa trên phân tích của TCBS. Điểm từ 1 đến 5, với 5 là tốt nhất.
    - financialHealth: điểm đánh giá sức khỏe tài chính cho cổ phiếu này dựa trên phân tích của TCBS. Điểm từ 1 đến 5, với 5 là tốt nhất.

</details>


## 3.6. 🔥 Dữ liệu khớp lệnh trong ngày giao dịch

<details>
  <summary>Minh hoạ giao diện TCBS</summary>

  ![intraday](https://raw.githubusercontent.com/thinh-vu/vnstock/main/src/tcbs_intraday_screen1.png)
  ![intraday](https://raw.githubusercontent.com/thinh-vu/vnstock/main/src/tcbs_intraday_screen2.png)

</details>
vnstock cho phép người dùng tải xuống dữ liệu khớp lệnh trong ngày giao dịch theo thời gian thực. Nếu mốc thời gian bạn truy cứu rơi vào Thứ Bảy, Chủ Nhật thì dữ liệu nhận được thể hiện cho ngày giao dịch của Thứ 6 của tuần đó.

```python
df =  stock_intraday_data(symbol='TCB', 
                            page_size=500)
print(df)
```

<details>
  <summary>Terminal output</summary>

  ```{r, engine='python', count_lines}
>>> stock_intraday_data('TCB', 500)

  ticker      time  orderType investorType  volume  averagePrice  orderCount
0    TCB  14:29:55  Sell Down        SHEEP    1000       32700.0           1
1    TCB  14:29:47     Buy Up        SHEEP     200       32750.0           1
2    TCB  14:29:44  Sell Down         WOLF    8000       32700.0          14
3    TCB  14:29:41  Sell Down        SHEEP    1000       32700.0           5
4    TCB  14:29:36  Sell Down         WOLF   23800       32700.0          10
  ```

</details>

<details>
  <summary>Giải thích ý nghĩa chỉ số</summary>
  • Khi 1 lệnh lớn (từ Cá mập, tay to, tổ chức....) mua chủ động (hoặc bán chủ động) được đưa vào Sàn, thường thì nó sẽ được khớp với nhiều lệnh nhỏ đang chờ bán (hoặc chờ mua). Nếu chỉ nhìn realtime theo từng lệnh khớp riêng lẻ, thì sẽ không thể phát hiện được các lệnh to (của Cá mập, tay to...) vừa được đẩy vào Sàn. Vì vậy, chúng tôi "cộng dồn" các lệnh khớp này lại (phát sinh bởi 1 lệnh lớn chủ động vào sàn trong 1 khoảng thời gian rất nhanh) để giúp NĐT phát hiện các lệnh lớn (của Cá mập, tay to....) chính xác hơn. Lệnh Cá mập sẽ được tô xanh (cho Mua chủ động) và đỏ (cho Bán chủ động). 

  • Cá mập: (CM - SHARK) nhà đầu tư tay to, tổ chức, đầu tư lớn, dẫn dắt thị trường. Giá trị 1 lệnh đặt > 1 tỷ đồng/lệnh đặt. Đồ thị 1N dùng số liệu 1 phút cho 60’ gần nhất; 1W là tổng mỗi 15’ cho 1 tuần; 1M là tổng hàng ngày cho 1 tháng

  • Sói già: (SG - WOLF) nhà đầu tư kinh nghiệm, giá trị lệnh đặt cao. Giá trị 1 lệnh đặt từ 200 tr đến 1 tỷ đồng/lệnh đặt.

  • Cừu non: (CN - SHEEP) nhà đầu tư nhỏ lẻ, giá trị giao dịch và mua bán chủ động thấp. Giá trị 1 lệnh đặt Mua hoặc Bán chủ động < 200 triệu đồng/lệnh đặt vào.

  • Mua chủ động (hay Buy Up) là khi NĐT thực hiện chủ động mua lên qua việc đặt lệnh mua với giá bằng giá dư bán gần nhất để có thể khớp luôn. Như thế, giá khớp cho lệnh này thường sẽ đẩy giá khớp lên cao hơn thị giá trước đó.

  • Bán chủ động (hay Sell Down) là khi NĐT thực hiện chủ động Bán dưới giá hiện tại (hay thị giá) của cổ phiếu bằng việc đặt lệnh bán với giá bán bằng giá dư mua gần nhất để khớp ngay. Và như thế, thị giá sẽ bị kéo xuống thấp hơn so với thị giá trước đó. Thống kê khối lượng giao dich theo Mua CĐ và Bán CĐ dùng để đánh giá tương quan giữa cung (Bán CĐ) và cầu (Mua CĐ) trên giao dịch khớp lệnh thực tế, nhằm nhận định tương đối về sự vận động của xu hướng dòng tiền. Khi tỷ lệ % Mua CĐ trên (Tổng Mua và Bán CĐ) lớn hơn 50%, đồng nghĩa với việc thị trường đang có xu hướng mua vào nhiều hơn bán ra và ngược lại, qua đó xác định được dòng tiền vào/ra với mỗi cổ phiếu. Khi tỷ lệ này cao đột biến (>70% hay <30%) so với điểm cân bằng (50%) , đó là tín hiệu của việc mua hoặc bán bất chấp của thị trường.

</details>


## 3.7. 🌏 Thông tin thị trường

<details>
  <summary>Tạm ngưng hoạt động, chờ nâng cấp APIs</summary>

### 3.7.1. Các mã cổ phiếu đứng đầu theo tiêu chí xếp loại 

<details>
  <summary>SSI Top Stocks</summary>

Top Breakout (Đột phá) > Top Gainers (Tăng giá) > Top Losers (Giảm giá) > Top Value (Giá trị) > Top Volume (Khối lượng)
![top_mover](./src/ssi_top_breakout_gainer_loser.png)

Top New High (vượt đỉnh) > Top Foreign Trading (nhà đầu tư ngước ngoài) > Top New Low (thủng đáy)
![top_foreigntrading_high_low](./src/top_foreigntrading_newhigh_newlow.png)

</details>

```python
market_top_mover('ForeignTrading')
```

<details>
  <summary>Output</summary>

```
    foreignBuyVolume  foreignBuyValue  ...                                          financial                                          technical
0          3826600.0     1.703888e+11  ...  {'organCode': 'DXG', 'rtd7': 14713.265320738, ...  {'organCode': 'DXG', 'sma20Past4': 34887.5, 's...
1          3270200.0     1.088892e+11  ...  {'organCode': 'STB', 'rtd7': 18173.6958318461,...  {'organCode': 'STB', 'sma20Past4': 34332.5, 's...
2          1456800.0     4.199166e+10  ...  {'organCode': 'FUEVFVND', 'rtd7': None, 'rtd11...  {'organCode': 'FUEVFVND', 'sma20Past4': 27993....
3          1033300.0     1.281170e+10  ...  {'organCode': 'FLC', 'rtd7': 12898.0038031343,...  {'organCode': 'FLC', 'sma20Past4': 12062.5, 's...
4           998600.0     5.324337e+10  ...  {'organCode': 'NLG', 'rtd7': 23318.1252311207,...  {'organCode': 'NLG', 'sma20Past4': 52385.0, 's...
```
</details>

### 3.7.2. Thông tin giao dịch nhà đầu tư nước ngoài (NDTNN)
Trong ví dụ dưới đây, thể hiện giao dịch mua vào của NDTNN.

```python
fr_trade_heatmap ('All', 'FrBuyVol')
```
<details>
  <summary>Output</summary>

  ```
    organCode  name      value  percentPriceChange  ...  ceilingPrice  floorPrice        industry_name      rate
  0        PVD   PVD  1433300.0            0.068627  ...       16350.0     14250.0              Dầu khí  0.040308
  1        PVS   PVS   370100.0            0.096154  ...       22800.0     18800.0              Dầu khí  0.040308
  2      PETRO   PLX   249700.0            0.014516  ...       33150.0     28850.0              Dầu khí  0.040308
  3   PETECHIM   PTV     4000.0            0.064000  ...        5400.0      4000.0              Dầu khí  0.040308
  4       BSRC   BSR     3800.0            0.002000  ...       17200.0     12800.0              Dầu khí  0.040308
  ..       ...   ...        ...                 ...  ...           ...         ...                  ...       ...
  10      None  Khác   210200.0            0.027762  ...           0.0         0.0            Ngân hàng  0.050653
  0        CMG   CMG    74400.0            0.024390  ...       43850.0     38150.0  Công nghệ Thông tin  0.034816
  1        SAM   SAM    35700.0            0.020833  ...        7700.0      6700.0  Công nghệ Thông tin  0.034816
  2        ELC   ELC     4100.0            0.049197  ...       10650.0      9270.0  Công nghệ Thông tin  0.034816
  3        ITD   ITD     2000.0            0.068548  ...       13250.0     11550.0  Công nghệ Thông tin  0.034816

  [92 rows x 10 columns]
  ```
</details>

### 3.7.3. Biến động của các nhóm chỉ số
![latest_indices](https://raw.githubusercontent.com/thinh-vu/vnstock/main/src/get_latest_indices.png)

Thông tin các nhóm chỉ số phổ biến của thị trường chứng khoán Việt Nam.

```python
get_latest_indices()
```

<details>
  <summary>Output</summary>

  ```
  >>> get_latest_indices()
    indexId comGroupCode  indexValue          tradingDate  ...  matchValue  ceiling  floor  marketStatus
0         0      VNINDEX     1108.08  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
1         0         VN30     1121.92  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
2         0     HNXIndex      219.87  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
3         0        HNX30      378.94  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
4         0   UpcomIndex       73.98  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
5         0       VNXALL     1707.39  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
6         0        VN100     1063.59  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
7         0        VNALL     1066.54  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
8         0       VNCOND     1537.34  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
9         0       VNCONS      793.25  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
10        0    VNDIAMOND     1689.15  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
11        0        VNENE      541.51  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
12        0        VNFIN     1252.54  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
13        0    VNFINLEAD     1631.16  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
14        0  VNFINSELECT     1676.21  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
15        0       VNHEAL     1552.19  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
16        0        VNIND      628.34  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
17        0         VNIT     2631.82  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
18        0        VNMAT     1534.50  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
19        0        VNMID     1394.75  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
20        0       VNREAL      981.94  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
21        0         VNSI     1715.37  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
22        0        VNSML     1140.40  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
23        0        VNUTI      874.84  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
24        0        VNX50     1805.33  2023-01-19T00:00:00  ...         0.0      0.0    0.0          None
  ```
</details>

### 3.7.4. Dữ liệu chuyên sâu theo nhóm chỉ số cụ thể
![index_series_data](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/get_index_series_data.png)

```python
get_index_series(index_code='VNINDEX', time_range='OneYear')
```
- Nhà cung cấp dữ liệu: SSI iBoard sử dụng dữ liệu từ FiinTrade.
- Sử dụng một trong các mã chỉ số sau để tra cứu:
  
  ```
  'VNINDEX', 'VN30', 'HNXIndex', 'HNX30', 'UpcomIndex', 'VNXALL',
  'VN100','VNALL', 'VNCOND', 'VNCONS','VNDIAMOND', 'VNENE', 'VNFIN',
  'VNFINLEAD', 'VNFINSELECT', 'VNHEAL', 'VNIND', 'VNIT', 'VNMAT', 'VNMID',
  'VNREAL', 'VNSI', 'VNSML', 'VNUTI', 'VNX50'
  ```
  Bạn có thể liệt kê toàn bộ các nhóm chỉ số với hàm `get_latest_indices()`.

- `time_range`: Sử dụng khung thời gian là một trong các giá trị sau
 ```
 'OneDay', 'OneWeek', 'OneMonth', 'ThreeMonth', 'SixMonths', 'YearToDate', 'OneYear', 'ThreeYears', 'FiveYears'
 ```
<details>
  <summary>Output</summary>

  ```
  >>> get_index_series(index_code='VNINDEX', time_range='OneYear')
      comGroupCode  indexValue          tradingDate  ...    matchValue  totalMatchVolume  totalMatchValue
  0        VNINDEX     1470.76  2022-01-27T00:00:00  ...  1.554536e+13       498256400.0     1.554536e+13
  1        VNINDEX     1478.96  2022-01-28T00:00:00  ...  1.913215e+13       634887600.0     1.913215e+13
  2        VNINDEX     1497.66  2022-02-07T00:00:00  ...  1.710999e+13       516533800.0     1.710999e+13
  3        VNINDEX     1500.99  2022-02-08T00:00:00  ...  2.106676e+13       660158600.0     2.106676e+13
  4        VNINDEX     1505.38  2022-02-09T00:00:00  ...  2.360041e+13       722161500.0     2.360041e+13
  ..           ...         ...                  ...  ...           ...               ...              ...
  241      VNINDEX     1060.17  2023-01-13T00:00:00  ...  7.884840e+12       459494342.0     7.884840e+12
  242      VNINDEX     1066.68  2023-01-16T00:00:00  ...  6.724499e+12       391079501.0     6.724499e+12
  243      VNINDEX     1088.29  2023-01-17T00:00:00  ...  1.016031e+13       566247477.0     1.016031e+13
  244      VNINDEX     1098.28  2023-01-18T00:00:00  ...  9.377296e+12       531786150.0     9.377296e+12
  245      VNINDEX     1108.08  2023-01-19T00:00:00  ...  1.054607e+13       556193050.0     1.054607e+13

  [246 rows x 14 columns]
  ```
</details>

</details>

## 3.8. 🛡 Thị trường Phái Sinh

### 3.8.1. Dữ liệu giá lịch sử

> Xem chi tiết mục [3.4.1 📈 Truy xuất dữ liệu giá lịch sử](#341--truy-xuất-dữ-liệu-giá-lịch-sử) cùng với thông tin giá chứng khoán cơ sở.

### 3.8.2. Dữ liệu khớp lệnh lịch sử

<details>

<summary>Minh họa bảng dữ liệu khớp lệnh Phái sinh - CK Rồng Việt </summary>

![livedragon_derivative_match](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/livedragon_derivative_history_match.png)

</details>

Để truy vấn dữ liệu từ hàm này, bạn cần có cookie người dùng (không cần đăng nhập) của chứng khoán Rồng Việt. Các bước thực hiện như sau:
  1. Truy cập `https://livedragon.vdsc.com.vn/all/all.rv`
  2. Mở `Developer Tools` trên trình duyệt, sử dụng F12 hoặc `Ctrl` + `Shift` + `I` trên Windows hoặc `Cmd` + `Option` + `I` trên macOS
  3. Chuyển đến tab `Network` và chọn mục `Fetch/XHR`
  4. Mở bất kỳ mục request nào trong tab này, tìm mục `Header` của request
  5. Tìm và copy giá trị của `Cookie` trong request này để điền vào bước tiếp theo dưới đây trước khi gọi hàm

```python
cookie = 'GIÁ TRỊ COOKIE CẦN PASTE VÀO ĐÂY'
derivatives_historical_match (symbol='VN30F2308', date='2023-07-24', cookie=cookie)
```

# IV. 🚚 Xuất, Lưu trữ, Chia sẻ dữ liệu

> Để xuất, lưu trữ và chia sẻ dữ liệu với vnstock, bạn có rất nhiều sự lựa chọn kể cả sử dụng cơ sở dữ liệu, bảng tính (Excel, Google Sheets) và nhiều hình thức khác. Dữ liệu tiêu chuẩn tạo ra bởi vnstock là các pandas DataFrame do đó bạn có thể biến đổi và lưu trữ/chia sẻ dữ liệu dễ dàng với cách thức tiêu chuẩn của python. Dưới đây là hướng dẫn cơ bản với cách thức xuất dữ liệu ra csv và Google Sheets.

## 4.1. Xuất dữ liệu ra csv

Dành cho những bạn mới làm quen Python và Pandas có thể sử dụng dữ liệu từ vnstock dễ dàng với công cụ bảng tính quen thuộc. Bạn có thể xuất dữ liệu từ hàm bất kỳ ra csv và mở bằng Excel hoặc upload lên Google Drive và mở bằng Google Sheets.

```python
start_date = '2023-06-01'
end_date = '2023-07-24'
# Truy xuất dữ liệu
df = stock_historical_data('TCB', start_date, end_date)
# Xuất dữ liệu ra csv, chèn ngày tháng và mã CP
df.to_csv(f'THƯ-MỤC-CỦA-BẠN/TCB_historical_price_{start_date}_{end_date}.csv', index=True)
```

## 4.2. Xuất dữ liệu ra Google Sheets

Phương thức này được thiết kế riêng để xuất dữ liệu trực tiếp từ Google Colab sang Google Sheets (sẽ không hoạt động nếu chạy ở môi trường local, không thiết lập môi trường tương đồng Colab). Tham khảo cách làm chi tiết trong file demo, mục `III. Data Export`


# V. 🙋‍♂️ Thông tin liên hệ

Bạn có thể kết nối với tác giả qua các hình thức sau. Trong trường hợp cần hỗ trợ nhanh, bạn có thể chọn nhắn tin qua Messenger hoặc Linkedin, tôi sẽ phản hồi ngay lập tức nếu có thể trong hầu hết các trường hợp.

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/thinh-vu">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://www.messenger.com/t/mr.thinh.ueh">
    <img src="https://img.shields.io/badge/Messenger-00B2FF?style=for-the-badge&logo=messenger&logoColor=white" alt="Messenger Badge"/>
  <a href="https://www.youtube.com/channel/UCYgG-bmk92OhYsP20TS0MbQ">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  </a>
    <a href="https://github.com/thinh-vu">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="Github Badge"/>
  </a>
</div>

# VI. 💪 Hỗ trợ phát triển dự án vnstock

Nếu bạn nhận thấy giá trị từ vnstock và các dự án mã nguồn mở của tôi, bạn có thể hỗ trợ phát triển chúng bằng cách quyên góp hoặc đơn giản là gửi tặng tôi một ly cà phê để cảm ơn.
Bạn có thể chọn 1 trong 3 hình thức đóng góp bao gồm Momo, Chuyển khoản ngân hàng và Gửi tiền qua Paypal. Sự đóng góp của bạn sẽ giúp tôi duy trì phí lưu trữ blog và tiếp tục tạo ra nội dung chất lượng cao. Cảm ơn sự ủng hộ của bạn!

- [Paypal](https://paypal.me/thinhvuphoto?country.x=VN&locale.x=en_US)

- ![momo-qr](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/momo-qr-thinhvu.jpeg)
  
- ![vcb-qr](https://raw.githubusercontent.com/thinh-vu/vnstock/beta/src/vcb-qr-thinhvu.jpg)

# VII. ⚖ Tuyên bố miễn trừ trách nhiệm
vnstock được phát triển nhằm mục đích cung cấp các công cụ nghiên cứu đơn giản và miễn phí, nhằm giúp người nghiên cứu tiếp cận và phân tích dữ liệu chứng khoán một cách dễ dàng. Dữ liệu được cung cấp phụ thuộc vào nguồn cấp dữ liệu, do đó, khi sử dụng, bạn cần thận trọng và cân nhắc.

💰 Trong bất kỳ trường hợp nào, người sử dụng hoàn toàn chịu trách nhiệm về quyết định sử dụng dữ liệu trích xuất từ vnstock và chịu trách nhiệm với bất kỳ tổn thất nào có thể phát sinh. Bạn nên tự mình đảm bảo tính chính xác và đáng tin cậy của dữ liệu trước khi sử dụng chúng.

Việc sử dụng dữ liệu chứng khoán và quyết định đầu tư là hoạt động có rủi ro và có thể gây mất mát tài sản. Bạn nên tìm kiếm lời khuyên từ các chuyên gia tài chính và tuân thủ các quy định pháp luật về chứng khoán tại Việt Nam và quốc tế khi tham gia vào hoạt động giao dịch chứng khoán.

Xin lưu ý rằng vnstock không chịu trách nhiệm và không có bất kỳ trách nhiệm pháp lý nào đối với bất kỳ tổn thất hoặc thiệt hại nào phát sinh từ việc sử dụng gói phần mềm này.

🐱‍👤 vnstock được thiết kế hoàn toàn cho mục đích phân tích và thực hành nghiên cứu đầu tư. Mọi hình thức sử dụng không đúng mục đích hoặc việc sử dụng trái phép thư viện với mục đích xấu như tấn công public API hay gây hại cho hệ thống thông qua từ chối truy cập hoặc các hành động tương tự, hoàn toàn nằm ngoài phạm vi sử dụng dự định và không thuộc trách nhiệm của nhóm phát triển.

# VII. 🔗 Trích dẫn thông tin (Cite)

Khi bạn sử dụng gói phần mềm `vnstock` trong dự án của mình, hãy tuân thủ các hướng dẫn về `Trích dẫn` (Cite) dưới đây:

Nếu bạn sử dụng dữ liệu hoặc mã nguồn của Vnstock trong dự án/bài viết/video của mình, xin vui lòng cung cấp trích dẫn (cite) tới dự án Vnstock. Dưới đây là ví dụ trích dẫn mẫu:

```
Dữ liệu được lấy từ Vnstock - gói phần mềm Python phân tích thị trường chứng khoán Việt Nam. (thinh-vu @ Github, Copyright (c) 2022).
```

Trích dẫn cho mã nguồn:
```
Mã nguồn được lấy từ Vnstock - gói phần mềm Python phân tích thị trường chứng khoán Việt Nam. (thinh-vu @ Github, Copyright (c) 2022).
```

# VIII. 🔑 Giấy phép (License)

Vnstock được cấp phép theo Giấy phép MIT. Nội dung của giấy phép như dưới đây, và thể hiện trong file [LICENSE](https://github.com/thinh-vu/vnstock/blob/beta/LICENSE).

Khi sử dụng Vnstock trong dự án của mình, bạn phải tuân thủ và giữ nguyên giấy phép MIT của Vnstock. Đồng thời, hãy chắc chắn rằng bạn đã bao gồm tên tác giả và giấy phép trong dự án của bạn.
Lưu ý: Vnstock là một dự án mã nguồn mở, do đó việc tuân thủ giấy phép và trích dẫn đóng vai trò quan trọng trong việc hỗ trợ và duy trì cộng đồng nguồn mở.
Chúng tôi cảm ơn bạn đã sử dụng Vnstock và tuân thủ các hướng dẫn `Trích dẫn` và `Giấy phép` này. Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào, xin vui lòng liên hệ với tôi qua mục [Thảo luận](https://github.com/thinh-vu/vnstock/discussions) của repo Github này hoặc nhắn tin trực tiếp.

Xin cảm ơn và chúc bạn thành công!

```
Copyright (c) 2022 Thinh Vu | thinh-vu @ Github | MIT

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

<details>

<summary> Bản dịch tiếng Việt để các bạn tiện tham khảo </summary>

```
Bản quyền (c) 2022 Thinh Vu | thinh-vu @ Github | MIT

Được cấp phép theo quyền tự do, miễn phí, cho bất kỳ cá nhân nào nhận được một bản sao của phần mềm này và các tệp tài liệu liên quan (gọi chung là "Phần mềm"), để sử dụng Phần mềm mà không có bất kỳ hạn chế nào, bao gồm nhưng không giới hạn quyền sử dụng, sao chép, sửa đổi, hợp nhất, xuất bản, phân phối, cấp phép lại và/hoặc bán các bản sao của Phần mềm, và cho phép những người nhận Phần mềm được nhúng vào Phần mềm này, tuân thủ các điều kiện sau đây:

Thông báo bản quyền trên và thông báo giấy phép này phải được bao gồm trong tất cả các bản sao hoặc phần quan trọng của Phần mềm.

PHẦN MỀM ĐƯỢC CUNG CẤP "NGUYÊN BẢN", KHÔNG CÓ BẤT KỲ HÌNH THỨC BẢO ĐẢM NÀO, BAO GỒM NHƯNG KHÔNG GIỚI HẠN ĐẾN SỰ BẢO ĐẢM VỀ CHẤT LƯỢNG KINH DOANH, PHÙ HỢP VỚI MỤC ĐÍCH CỤ THỂ VÀ VI PHẠM QUYỀN SỞ HỮU. TRONG MỌI TRƯỜNG HỢP, TÁC GIẢ HOẶC CHỦ SỞ HỮU BẢN QUYỀN KHÔNG CHỊU TRÁCH NHIỆM ĐỐI VỚI BẤT KỲ YÊU CẦU BỒI THƯỜNG, THIỆT HẠI HOẶC TRÁCH NHIỆM PHÁP LÝ NÀO PHÁT SINH TỪ HOẶC LIÊN QUAN ĐẾN SỬ DỤNG HOẶC HIỆN HỮU CỦA PHẦN MỀM.
```

</details>
