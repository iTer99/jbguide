# Hướng dẫn Jailbreak cho người mới bắt đầu

> Soạn bởi Anden Wieseler

> Phiên dịch bởi Nguyễn Thiện Hoàn (iTer99)

**Lưu ý trước khi bạn bắt đầu:**
* **_Nếu đây là lần đầu tiên bạn Jailbreak, hãy đảm bảo thực hiện theo hướng dẫn này một cách thật chính xác để ngăn các sự cố có thể phát sinh_**
* **_Nếu bạn Jailbreak điện thoại, tôi không chắc sẽ mất bảo hành (hãy đọc phần hướng dẫn gỡ bỏ Jailbreak_**
* **_Tôi không chịu trách nhiệm cho bất kỳ vấn đề phát sinh từ việc Jailbreak thiết bị của bạn. Thiết bị của bạn là trách nhiệm của bạn. Nhưng tôi có thể hỗ trợ trong khả năng mà tôi có thể giúp đỡ bạn_**

---

## Phần I: Tìm hiểu về Jailbreak

### 1): Jailbreak là gì ?

Jailbreak là việc khai thác lỗ hổng trong iOS / iPadOS cho phép truy cập vào các phần của hệ thống mà Apple thường không cho phép và để cài đặt các chương trình, tinh chỉnh của bên thứ 3 không có trên App Store

Jailbreak dựa trên các lỗ hổng khai được tìm thấy bởi các nhà nghiên cứu bảo mật iOS đã báo cáo các lỗi cho Apple, giú phần làm cho iOS và iPadOS an toàn hơn.

### 2): Mục đích của việc Jailbreak ?

Jailbreak iOS có nhiều mục đích khác nhau. Tùy vào người muốn Jailbreak để làm gì.

Phần lớn, người ta Jailbreak để tùy chỉnh thiết bị mà iOS không cho phép. Thực tế, đã nhiều tinh chỉnh Jailbreak trở thành ý tưởng cho các bản cập nhật iOS và iPadOS mới hơn (mặc dù Apple không thừa nhận điều đó).

### 3): Jailbreak có an toàn không ?

Jailbreak một thiết bị iOS, bản thân nó, thường an toàn. Những gì bạn làm với bản Jailbreak sẽ xác định xem thiết bị của bạn có an toàn không. Thông thường, điều này có nghĩa là chỉ cài đặt repos và chỉnh sửa đáng tin cậy và thay đổi mật khẩu gốc trên thiết bị của bạn, vì vậy tin tặc gặp khó khăn hơn trong việc cố gắng hack điện thoại của bạn và đánh cắp dữ liệu của bạn. Hãy nghĩ về nó như bất kỳ máy tính khác.

### 4): Jailbreak có hợp pháp không ?

Chính phủ Mỹ quyết định hợp pháp hóa việc bẻ khóa các loại điện thoại thông minh DMCA (2009). 

**Lưu ý về vi phạm bản quyền, ngay cả khi sử dụng bản bẻ khóa, vẫn là bất hợp pháp**

### 5): Tôi đã nói về cái gọi là "Tweaks" và "Repos", nó là gì ?

Khi bạn Jailbreak thiết bị của mình, một ứng dụng mới sẽ được cài đặt; một trình quản lý gói được gọi là Cydia (Cydia là tên loài bướm sử dụng táo làm thức ăn cho nó). Hãy nghĩ là nó như một cửa hàng ứng dụng (App Store) thì Cydia cho phép bạn tải xuống những tinh chỉnh (tweaks), các ứng dụng được phát triển để thay đổi toàn hệ thống và tất cả được lưu trữ trong một kho (gọi là Repository).  Một số tinh chỉnh là miễn phí, có một số bạn phải trả tiền giống như bất kì phần mềm nào khác.

---

## Phần II: Các loại Jailbreaks

Có nhiều loại Jailbreaks, mỗi loại Jailbreak mang ý nghĩa khác nhau.

Các loại Jailbreaks|Ý Nghĩa
---|---
Untethered|Loại jailbreak này được thực hiện từ máy tính, jailbreak vẫn được giữ nguyên sau những lần khởi động lại thiết bị; **Không còn phổ biến nữa**
Psuedo-untethered|Loại jailbreak này đưa một ứng dụng vào thiết bị của bạn và jailbreak từ ứng dụng đó, sau đó cài đặt gói cho phép bạn chạy jailbreak mỗi khi thiết bị được khởi động; **Không được phổ biến lắm**
Tethered|Loại jailbreak này yêu cầu cài đặt firmware* tùy chỉnh cho thiết bị và sử dụng máy tính để khởi động thiết bị; **Loại bẻ khóa này không còn phổ biến nữa**
Semi-tethered|Loại jailbreak này yêu cầu máy tính khởi động thiết bị để jailbreak, nhưng thiết bị sẽ mất jailbreak nếu không có máy tính; **Hiện tại đã có semi-tethered jailbreak**
Semi-untethered|**Đây là loại jailbreak phổ biến nhất hiện nay** Loại jailbreak này đưa một ứng dụng vào thiết bị của bạn và jailbreak từ ứng dụng đó. Jailbreak sẽ bị mất nếu thiết bị khởi động lại, trong trường hợp đó người dùng có thể re-jailbreak lại từ ứng dụng đó

* Firmware là các file .ipsw mà người hay dùng để Restore - chạy lại chương trình cho thiết bị iOS 

## Phần III: Lựa chọn công cụ Jailbreak của bạn

Dưới đây là tôi đang nói về iOS 13. Hãy đọc qua và lựa chọn công cụ Jailbreak bạn muốn sử dụng

**_Lưu ý: Nếu thiết bị của bạn không thể Jailbreak, hãy chắc chắn đã tắt Cập nhật tự động trong Cài đặt và KHÔNG Cập nhật phiên bản iOS của bạn_**

**_Các bản iOS mới nhất không có nghĩa là đã có thể Jailbreak được ngay, có thể mất vài tháng để phát hành công cụ Jailbreak. Và Jailbreak không dành cho người không thể chờ đợi.

Checkra1n|Unc0ver
---|---
Semi-tethered|Semi-untethered
Hỗ trợ iPhone 5s (A5 chip) đến iPhone X (A11 chip)|Hỗ trợ iPhone 5s (A5 chip) đến thế hệ iPhone mới nhất (thời điểm tôi viết thứ này là dòng iPhone 11, A13 chip)
Hỗ trợ iOS/iPadOS phiên bản iOS 12.3 và mới hơn|Hỗ trợ iOS/iPadOS phiên bản 11.0-13.3 (Không bao gồm 12.3-12.3.2 và 12.4.2-12.4.5)
Hỗ trợ macOS và Linux|Yêu cầu AltStore, Hỗ trợ Windows 10 và MacOS 10.14.4+
Đang tích cực phát triển|Đang tích cực phát triển

**_Xem toàn bộ công cụ Jailbreak với các phiên bản iOS tại [đây](https://www.reddit.com/r/jailbreak/wiki/escapeplan/guides/jailbreakcharts)._**

## Phần IV: Tải xuống công cụ Jailbreak của bạn
