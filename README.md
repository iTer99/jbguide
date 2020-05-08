# Hướng dẫn Jailbreak cho người mới bắt đầu

> Biên soạn bởi [Anden Wieseler](https://github.com/JoeMcRainbow)

> Phiên dịch và chỉnh sửa bởi [Nguyễn Thiện Hoàn](https://github.com/iTer99)

**Lưu ý trước khi bạn bắt đầu:**
* **_Nếu đây là lần đầu tiên bạn Jailbreak, hãy đảm bảo thực hiện theo hướng dẫn này một cách thật chính xác để ngăn các sự cố có thể phát sinh_**
* **_Nếu bạn Jailbreak điện thoại, tôi không chắc sẽ mất bảo hành (hãy đọc phần X)_**
* **_Tôi không chịu trách nhiệm cho bất kỳ vấn đề phát sinh từ việc Jailbreak thiết bị của bạn. Thiết bị của bạn là trách nhiệm của bạn. Nhưng tôi có thể hỗ trợ trong khả năng mà tôi có thể giúp đỡ bạn_**

---

## Phần I: Tìm hiểu về Jailbreak

### 1) Jailbreak là gì ?

Jailbreak là việc khai thác lỗ hổng có trong iOS / iPadOS cho phép truy cập vào các phần của hệ thống mà Apple thường không cho phép và cài đặt các chương trình, tinh chỉnh của bên thứ 3 không có trên App Store.

Jailbreak dựa trên các lỗ hổng khai được tìm thấy bởi các nhà nghiên cứu bảo mật iOS đã báo cáo các lỗi cho Apple, giúp phần làm cho iOS và iPadOS an toàn hơn.

### 2) Mục đích của việc Jailbreak ?

Jailbreak iOS có nhiều mục đích khác nhau. Tùy vào cá nhân muốn Jailbreak để làm gì. Phần lớn, người dùng Jailbreak thiết bị của họ để tùy chỉnh những tính năng mà iOS không cho phép. Thực tế, đã có nhiều tinh chỉnh Jailbreak trở thành ý tưởng cho các bản cập nhật iOS và iPadOS mới hơn (mặc dù Apple không thừa nhận điều đó).

### 3) Jailbreak có an toàn không ?

Jailbreak một thiết bị iOS cơ bản là nó vẫn an toàn. Những gì bạn làm sau khi Jailbreak sẽ xác định xem thiết bị của bạn có còn an toàn không. Thông thường người dùng Jailbreak chỉ là cài đặt những Repos và những bản Tweaks đáng tin cậy. Quản lí truy xuất tệp tin trong hệ thống của máy. Mở một thế giới trong môi trường iOS cũng giống như cách mà Android và Windows cho phép. Jailbreak hoàn toàn không ảnh hưởng đến Dịch vụ vị trí GPS, tìm và định vị iPhone của bạn, mật khẩu, Touch ID hay Face ID và những chức năng khác của máy. Nên nó vẫn giữ được an toàn theo cách mà iOS đã làm.

Và cũng vì một vài lí do những bản Jailbreak chỉ có trên những phiên bản iOS cũ hơn và cũng gặp phải các vần đề hệ thống khiến người khác có thể lạm dụng vào nó mà phá hoại thiết bị của bạn. Thời điểm tôi viết thứ này cách đây chưa đầy một tuần, [lỗi kí tự lạ](https://www.thegioididong.com/tin-tuc/xuat-hien-ky-tu-la-khien-iphone-bi-te-liet-1251760) khiến thiết bị của bạn bị treo, crash ứng dụng nguy hiểm hơn là tự động khởi động lại máy thì các Developer Jailbreak cũng đã ra tinh chỉnh để sửa chữa nó xem tại [đây](https://www.reddit.com/r/jailbreak/comments/g6rpb8/release_capturetheflag_stop_italian_flag_emoji/). Một lỗi khác có tên [Youve got 0 Click Mail](https://blog.zecops.com/vulnerabilities/youve-got-0-click-mail/) còn gọi là Zero Day cho phép Hacker xâm nhập thiết bị thông qua điều khiển từ xa, theo dõi và đánh cắp dữ liệu trong thiết bị mà không cần phải mở Mail. Đặc biệt lỗi đã có từ iOS 6 và phải đến tận iOS 13.4.5 Apple mới sửa lỗi này và [đây](https://www.reddit.com/r/jailbreak/comments/g86cfm/releasemailmend_a_patch_for_mail_vulnerability_by/) là cách tạm thời để sửa lỗi đó nếu thiết bị của bạn đã Jailbreak. Có thể thấy rằng mục đích Jailbreak cũng không đúng và cũng không sai nên bạn hãy cứ yên tâm nhé.

### 4) Jailbreak có hợp pháp không ?

Chính phủ Mỹ quyết định hợp pháp hóa việc bẻ khóa các loại điện thoại thông minh DMCA năm 2009. 

**Lưu ý về vi phạm bản quyền, ngay cả khi sử dụng bản bẻ khóa, vẫn là bất hợp pháp**

### 5) Tôi đã nói về cái gọi là "Tweaks" và "Repos", nó là gì ?

Khi bạn Jailbreak thiết bị của mình, một ứng dụng mới sẽ được cài đặt; một trình quản lý gói được gọi là Cydia (Cydia là tên loài bướm sử dụng táo làm thức ăn cho nó). Hãy nghĩ là nó như một cửa hàng ứng dụng App Store thì Cydia cho phép bạn tải xuống những tinh chỉnh (Tweaks), thay đổi giao diện (Themes) và các ứng dụng được mà người ta  phát triển để thay đổi hệ thống. Tất cả được lưu trữ trong một kho (gọi là Repository).  Một số tinh chỉnh là miễn phí, có một số bạn phải trả tiền giống như bất kì phần mềm nào khác.

---

## Phần II: Các loại Jailbreaks

Có nhiều loại Jailbreaks, mỗi loại Jailbreak mang ý nghĩa khác nhau.

Các loại Jailbreaks|Ý Nghĩa
---|---
Untethered|Loại Jailbreak này được thực hiện từ máy tính, Jailbreak vẫn được giữ nguyên sau những lần khởi động lại thiết bị; **Không còn phổ biến nữa**
Psuedo-untethered|Loại Jailbreak này đưa một ứng dụng vào thiết bị của bạn và Jailbreak từ ứng dụng đó, sau đó cài đặt gói cho phép bạn chạy Jailbreak mỗi khi thiết bị được khởi động; **Không được phổ biến lắm**
Tethered|Loại Jailbreak này yêu cầu cài đặt firmware* tùy chỉnh cho thiết bị và sử dụng máy tính để khởi động thiết bị; **Loại bẻ khóa này không còn phổ biến nữa**
Semi-tethered|Loại Jailbreak này yêu cầu máy tính khởi động thiết bị để Jailbreak, nhưng thiết bị sẽ mất Jailbreak nếu không có máy tính; **Hiện tại đã có semi-tethered Jailbreak**
Semi-untethered|**Đây là loại Jailbreak phổ biến nhất hiện nay** Loại Jailbreak này đưa một ứng dụng vào thiết bị của bạn và Jailbreak từ ứng dụng đó. Jailbreak sẽ bị mất nếu thiết bị khởi động lại, trong trường hợp đó người dùng có thể re-Jailbreak lại từ ứng dụng đó

* *firmware là các file .ipsw mà người ta hay dùng để Restore - chạy lại chương trình cho thiết bị iOS 

---

## Phần III: Lựa chọn công cụ Jailbreak của bạn

Dưới đây là tôi đang nói về iOS 13. Hãy đọc qua và lựa chọn công cụ Jailbreak bạn muốn sử dụng

**_Lưu ý: Nếu thiết bị của bạn không thể Jailbreak, hãy chắc chắn đã tắt Cập nhật tự động trong Cài đặt và KHÔNG Cập nhật phiên bản iOS của bạn_**

**_Các bản iOS mới nhất không có nghĩa là đã có thể Jailbreak được ngay, có thể mất vài tháng để phát hành công cụ Jailbreak. Và Jailbreak không dành cho người không thể chờ đợi_**

Checkra1n|Unc0ver
---|---
Semi-tethered|Semi-untethered
Hỗ trợ iPhone 5s (A5 chip) đến iPhone X (A11 chip)|Hỗ trợ iPhone 5s (A5 chip) đến thế hệ iPhone mới nhất (thời điểm tôi viết thứ này là dòng iPhone 11, A13 chip)
Hỗ trợ iOS/iPadOS phiên bản iOS 12.3 và mới hơn|Hỗ trợ iOS/iPadOS phiên bản 11.0-13.3 (Không bao gồm 12.3-12.3.2 và 12.4.2-12.4.5)
Hỗ trợ macOS và Linux|Yêu cầu AltStore, Hỗ trợ Windows 10 và MacOS 10.14.4+
Đang tích cực phát triển|Đang tích cực phát triển

**_Xem toàn bộ công cụ Jailbreak với các phiên bản iOS tại [đây](https://www.reddit.com/r/Jailbreak/wiki/escapeplan/guides/Jailbreakcharts)._**

---

## Phần IV: Tải xuống công cụ Jailbreak của bạn

Trước khi bạn bắt đầu, bạn sẽ cần những thứ sau đây:

* Một máy tính có hệ điều hành được yêu cầu được cài đặt (xem bên trên) và một tài khoản có quyền quản trị viên
* Thiết bị iOS / iPadOS của bạn (để có kết quả tốt nhất, pin phải trên 50%)
* Cáp sạc hỗ trợ truyền dữ liệu (không phải những loại cáp 7 màu, có đèn chỗ đầu kết nối
* Thứ không thiếu là một kết nối mạng

Đối với Checkra1n, hãy truy cập https://checkra.in và tải xuống phiên bản mới nhất của Checkra1n

**_Lưu ý: Với Linux hãy bỏ qua phần này. Tôi sẽ giải thích cách sử dụng Checkra1n trong phần tiếp theo_**

Đối với Unc0ver:
* Yêu cầu iTunes, nếu bạn chưa cài đặt hãy cài đặt iTunes từ https://www.apple.com/itunes

**_Lưu ý: Với Windows: Đảm bảo bạn tải xuống phiên bản .exe, không phải phiên bản trên Microsoft Store_**

**_Lưu ý: Với MacOS Catalina: iTunes đã bị xóa khỏi MacOS Catalina. Chỉ cần bỏ qua bước này_**

* Tải về và cài đặt [AltStore](https://altstore.io) trên máy tính của bạn.

---

## Phần V: Cài đặt công cụ Jailbreak của bạn

### 1) Cài đặt Checkra1n

Để đơn giản hơn tôi sẽ chia phần này thành hai phần MacOS và Linux. Nếu bạn sử dụng Unc0ver, vui lòng bỏ qua phần này!

#### 1) Cài đặt Checkra1n trên MacOS

Trên MacOS, tất cả những gì bạn phải làm là mở tệp DMG bạn có được từ trang web Checkra1n và kéo tệp đó vào thư mục Ứng dụng của bạn. Dễ dàng!

#### 2) Cài đặt Checkra1n trên Linux

Mở Terminal và chạy các lệnh như sau

`sudo apt update && sudo apt upgrade` để đảm bảo các gói của bạn được cập nhật.

`echo "https://assets.checkra.in/debian/" | sudo tee -a /etc/apt/sources.list` để thêm repo APT Checkra1n.

`sudo apt-key adv --fetch-keys https://assets.checkra.in/debian/archive.key` để thêm khóa công khai.

`sudo apt update` để làm mới danh sách gói của bạn.

`sudo apt install checkra1n` để cài đặt ứng dụng Checkra1n.

### 2) Cài đặt Unc0ver

Cài đặt Unc0ver tương tự cho cả MacOS và Windows.

1. Cài đặt AltServer trên máy tính của bạn bằng cách xem các hướng dẫn tại [đây](https://altstore.io/faq)
2. Khi AltStore được cài đặt trên thiết bị của bạn, hãy cắm thiết bị vào máy tính
3. Mở Safari trên thiết bị của bạn và truy cập https://unc0ver.dev và tải xuống phiên bản mới nhất. Nó sẽ tự động lưu vào thư mục tải xuống trong máy của bạn
4. Mở AltStore trên thiết bị của bạn và đăng nhập
5. Sang tab "My Apps", nhấn vào dấu cộng ("+")
6. Chọn tệp Unc0ver.ipa vừa tải xuống
7. Đợi Unc0ver được cài đặt

**_Có rất nhiều trang chủ Unc0ver giả mạo, trang chủ chính xác là https://unc0ver.dev_**

**_Lưu ý: Cứ sau 7 ngày bạn sẽ phải làm mới một lần để duy trì Unc0ver hoạt động. Bằng cách kết nối điện thoại với máy tính, khởi động AltServer, mở AltStore trên thiết bị và nhấn refresh trong "Ứng dụng của tôi"._**

---

## Phần VI: Jailbreaking

### 1) Jailbreak trên Checkra1n

1. Mở ứng dụng Checkra1n trên máy tính của bạn
2. Kết nối thiết bị của bạn với máy tính
3. Nhấn bắt đầu
4. Làm theo hướng dẫn để đưa thiết bị vào chế độ DFU
5. Đợi thiết bị khởi động lại
6. Khi thiết bị đã khởi động, hãy mở ứng dụng Checkra1n trong màn hình chính 
7. Chọn Cydia để cài đặt Cydia
8. Xác minh rằng Cydia đã được cài đặt bằng cách mở Cydia từ màn hình chính
9. Hoàn tất

**_Lưu ý: Bạn sẽ phải làm lại tất cả các bước này mỗi khi thiết bị của bạn khởi động lại để tiếp tục Jailbreak!_**

### 2) Jailbreak trên Unc0ver

1. Đảm bảo thiết bị của bạn được rút khỏi máy tính
2. Mở Unc0ver
3. Nhấn Jailbreak ở phía dưới
4. Sẽ có một thông báo nói rằng The system snapshot has been renamed. Allow the device to reboot. Bấm vào OK
5. Khi thiết bị đã được khởi động lại, hãy mở ứng dụng Unc0ver lần nữa
6. Nhấn nút Jailbreak
7. Chờ Jailbreak được áp dụng. Điều này có thể mất đến một phút
8. Cho phép thiết bị khởi động lại
9. Mở Cydia để xác minh rằng quá trình Jailbreak đã hoàn tất
10. Hoàn tất

**_Lưu ý: Bạn sẽ phải mở ứng dụng Un0ver và re-Jailbreak lại mỗi khi thiết bị khởi động lại_**

---

## Phần VII: Vài lưu ý khi bạn đã hoàn tất các quá trình Jailbreak

Chúc mừng! Bạn đã hoàn tất quá trình Jailbreak lần đầu tiên của bạn!

* Không được cập nhật phiên bản iOS của bạn mà không xóa bỏ bản Jailbreak của bạn trước! (đọc phần IX)

* Với Unc0ver: hãy nhớ làm mới ứng dụng của bạn sau mỗi 7 ngày một lần!

* Hãy nhớ áp dụng lại Jailbreak của bạn sau mỗi lần khởi động lại!

---

## Phần VIII: Làm gì tiếp theo

### Repos, Tweaks và Themes

**Để thêm nguồn vào Cydia:**

1. Mở Cydia
2. Chuyển đến tab Các Nguồn
3. Nhấn nút Sửa ở trên bên phải
4. Nhấn nút Thêm sẽ hiện ra ở trên bên trái
5. Nhập URL của repo mà bạn muốn thêm và nhấn "Thêm nguồn"

**Dưới đây là các tinh chỉnh tôi giới thiệu**

Tinh chỉnh|Nhà phát triển|Repo|Thanh toán
---|---|---|---
SnowBoard|SparkDev|sparkdev.me|Miễn phí
HomePlus Beta|Kritanta|repo.openpack.io|Miễn phí
Xen HTML|Matchstic|repo.packix.com|Miễn phí
XenInfo|JunesiPhone|junesiphone.com/supersecret|Miễn phí
Complications|Ben Giannis|repo.packix.com|$1.99
Axon|Nepeta & Baw Appie|repo.rpgfarm.com|Miễn phí
Jellyfish|Justin Proulx & Ayden Panhuyzen|repo.dynastic.co|$1.99
Prysm|LaughingQuoll|repo.packix.com|$3.49
Ultrasound|Ayden Panhuyzen|repo.dynastic.co|$1.99

**Dưới đây là một số Repos nổi tiếng tôi sưu tầm được:**

[https://getzbra.com/repo/](https://getzbra.com/repo/) Zebra cũng giống như Cydia nhưng nó mới hơn

[https://apt.bingner.com/](https://apt.bingner.com/) kho không thể thiếu liên quan với cách vận hành của các tweaks

[https://sparkdev.me/](https://sparkdev.me/) SnowBoard tinh chỉnh dùng để thay đổi Themes cho máy

[http://getdelta.co/](http://getdelta.co/) Flex 3 beta có những bản vá để lượt bỏ hoặc thêm vài thành phần cho ứng dụng và hệ thống

[http://tigisoftware.com/cydia/](http://tigisoftware.com/cydia/) Filza File Manager quản lí tệp tin hệ thống

[https://apptapp.me/repo/](https://apptapp.me/repo/) Installer5 cũng giống như Zebra thay thế cho Cydia

[https://altstore.pixelomer.com/](https://altstore.pixelomer.com/) AltStore và một vài ứng dụng khá là hay ho

[https://repo.pixelomer.com/](https://repo.pixelomer.com/) MobileGoose có con vịt chạy khắp màn hình

[https://cokepokes.github.io/](https://cokepokes.github.io/) AppStore++ tăng/hạ cấp ứng dụng trong App Store

[https://cydia.akemi.ai/](https://cydia.akemi.ai/) AppSync Unified cài đặt file .IPA không được đăng kí 

[https://rpetri.ch/repo/](https://rpetri.ch/repo/) một trong những Repos không thể thiếu như AppList, RocketBootstrap, Activator...

[https://repo.dynastic.co/](https://repo.dynastic.co/) có những Tweaks và Theme cực xịn

[https://alexpng.github.io/](https://alexpng.github.io/) cách tinh chỉnh đổi hình nên theo giao diện Sáng và Tối

[https://repo.packix.com/](https://repo.packix.com/) có những Tweaks và Theme cực xịn

[https://ib-soft.net/cydia/beta/](https://ib-soft.net/cydia/beta/) iCleaner Pro quét rác, temp, tệp tin thừa trong máy

[https://skitty.xyz/repo/](https://skitty.xyz/repo/) Six (LS) màn hình khóa iOS 6 và một vài tinh tỉnh cũng hay ho

[https://repo.chariz.com/](https://repo.chariz.com/) có những Tweaks cực xịn

[https://opa334.github.io/](https://opa334.github.io/) CCSupport tùy chỉnh công tắt trong Control Center (trung tâm điều khiển)

[http://apt.thebigboss.org/repofiles/cydia/](http://apt.thebigboss.org/repofiles/cydia/) Repos huyền thoại cho toàn thế hệ iOS Jailbreak

[https://repo.twickd.com/](https://repo.twickd.com/) có những Tweaks và Theme cực xịn

[https://www.yourepo.com/](https://www.yourepo.com/) một trong các Repos lớn bây giờ

[https://cydiageek.yourepo.com/](https://cydiageek.yourepo.com/) có các tinh chỉnh nhỏ

[http://repo.litten.love/](http://repo.litten.love/) một trong Repos tôi yêu thích

**_Khả năng tương thích các tweak khác nhau tùy theo thiết bị và phiên bản iOS. Đặc biệt là với iPad_**

---

## Phần IX: Gỡ bỏ Jailbreak của bạn một cách an toàn

### 1) Xóa bản Jailbreak đối với Checkra1n

1. Hãy chắc chắn rằng bạn đã Jailbreak bằng máy tính và có Checkra1n trong màn hình chính
2. Mở Checkra1n trong màn hình chính của bạn
3. Nhấn nút Restore System
4. Đợi quá trình hoàn tất
5. Thiết bị của bạn sẽ tự khởi động lại
6. Hoàn tất

### 2) Loại bỏ Jailbreak đối với Un0ver

1. Khởi động lại để vào lại trạng thái không Jailbreak
2. Mở ứng dụng Unc0ver
3. Nhấn vào biểu tượng cài đặt
4. Bật dòng "Restore RootFS"
5. Quay trở lại màn hình Jailbreak
6. Nhấn nút "Re-Jailbreak" ở phía dưới
7. Một thông báo sẽ hiện lên The filesystem will be restored. Allow this and continue. Hãy bấm OK.
8. Khi quá trình hoàn tất, bạn sẽ được yêu cầu khởi động lại thiết bị của mình. Hãy bấm OK.
9. Sau khi thiết bị đã được khởi động lại, hãy xóa các ứng dụng Unc0ver và AltStore.

---

## Phần X: Làm gì nếu điện thoại bạn gặp vấn đề hoặc cần bảo hành

### 1) Nếu điện thoại của bạn gặp phải vấn đề do Jailbreak

**_Hướng dẫn Restore thiết bị của bạn về nguyên trạng như ban đầu_**

1. Trên máy tính cài đặt [iTunes](https://www.apple.com/itunes) và [3uTools](http://www.3u.com/)
2. Mở 3uTools và kết nối thiết bị với máy tính
3. Cho phép Tin cậy trên thiết bị của bạn và nhập mật khẩu (nếu có)
4. Trong 3uTools chuyển sang tab Flash & JB
5. Chọn phiên bản iOS mới nhất, tránh các phiên bản beta
6. Chắc chắn là đã tích xanh vào dòng Quick Flash Mode
7. Sau đó chỉ việc nhấn vào Flash
8. Để 3uTools hoàn thành các quá trình bao gồm tự động tải xuống file .ipsw (có thể mất 30p tùy vào tốc độ internet của bạn)
9. Điện thoại trở về màn hình Hello
10. Hoàn tất các thiết lập và đăng nhập vào ID Apple
11. Tải xuống xuống các ứng dụng từ App Store mà bạn cần

### 2) Nếu điện thoại của bạn cần được bảo hành

**_Cách để đối phó để không bị phát hiện thiết bị bạn đã Jailbreak_**

Thực hiện theo các cách Restore như trên nếu điện thoại vẫn có khả năng sử dụng được cảm ứng, cổng kết nối và các chức năng không ảnh hưởng quá trình Restore.

Nếu bạn gửi thiết bị của bạn đến trung tâm bản hành như Apple, FPT, TGDĐ các Chuyên gia sửa chữa có thể phát hiện thiết bị của bạn đã được Jailbreak, họ có thể sửa chữa nó nhưng bạn có thể phải trả phí bảo hành.

---

## Phần XI: Kết thúc

Nếu bạn đọc tất cả những điều này, rất vui bạn đã dành thời gian để tìm hiểu về Jailbreak!

Bạn gặp các vấn đề về Jailbreak. Đừng lo lắng, hãy nói tôi biết điều đó, tôi có thể giúp bạn trong khả năng mà tôi có thể làm. À mà r/Jailbreak cũng là lựa chọn tốt đấy.

Để tìm hiểu thêm về các tweaks và themes , hãy xem r/iOSTheme trên Reddit.

> Written with ❤️ by iTer99 Dev

> Và chân thành cảm ơn Anden Wieseler
