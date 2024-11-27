# LINUX-BASIC
## 1. Nguồn gốc của Unix
- ### Khái niệm Unix
    - Unix là một hệ điều hành máy tính đa năng được viết vào những năm ***1960*** tại ***Bell Labs*** bởi một nhóm các nhà khoa học.
    - Ban đầu, hệ điều hành này chỉ được sử dụng trong hệ thống Bell của AT&T.
    - Nhưng sau đó, công ty này đã cấp phép Unix cho các đơn vị bên ngoài. Từ đó hình thành một loạt biến thể của hệ điều hành Unix và phát triển đến ngày nay
    - Có thể kể đến các biến thể nổi tiếng như BSD, Xenix, macOS X và Linux.
## 2. Linux là gì? Bắt nguồn từ đâu? Sự khác biệt cơ bản giữa Linux và Windows.
- ### Linux là gì?
    - **Linux** là một họ các hệ điều hành tự do nguồn mở tương tự Unix và dựa trên Linux kernel.
- ### Bắt nguồn từ đâu?
    - Năm 1991, khi theo học tại Đại học Helsinki, Torvalds trở nên tò mò về hệ điều hành. Thất vọng vì việc cấp phép MINIX, lúc đó chỉ giới hạn sử dụng cho mục đích giáo dục, ông bắt đầu làm việc với nhân hệ điều hành của chính mình, cuối cùng trở thành Linux. 
    - Torvalds đã bắt đầu phát triển nhân Linux trên MINIX và các ứng dụng được viết cho MINIX cũng được sử dụng trên Linux.
    - Sau đó, Linux trưởng thành và việc phát triển nhân Linux được tiếp tục trên các hệ thống Linux.
- ### Sự khác biệt cơ bản giữa Linux và Windows:
    - Truy cập
        - __Linux__ người dùng có quyền truy cập vào mã nguồn của kernel và thay đổi mã theo nhu cầu của mình. Ưu điểm riêng của Linux như các lỗi trong HĐH sẽ được khắc phục với tốc độ nhanh và nhược điểm là các nhà phát triển có thể tận dụng bất kỳ điểm yếu nào trong HĐH nếu họ tìm thấy.
        - __Windows__ mỗi người dùng sẽ không có quyền truy cập vào mã nguồn, chỉ có các thành viên của nhóm được lựa chọn mới có quyền truy cập vào nó.
    - Sự đa dạng
        - __Linux__ có nhiều bản phân phối khác nhau tùy theo nhu cầu của người dùng.
        - __Windows__ có rất nhiều tùy chọn tùy chỉnh có sẵn.
    - Giấy phép
        - __Linux__ với hệ điều hành được cấp phép GPL, người dùng có thể tự do sửa đổi phần mềm, có thể sử dụng lại trong bất kỳ hệ thống nào và thậm chí họ có thể bán phiên bản sửa đổi.
        - __Windows__ với giấy phép của Microsoft, người dùng sẽ không có quyền truy cập vào mã nguồn (không thể sửa đổi phần mềm) và dựa số lượng giấy phép – mới có thể cài đặt trên máy tính.
    - Dòng lệnh
        - __Linux__ dòng lệnh là một công cụ rất hữu ích để quản trị và thực hiện các công việc hàng ngày, nhưng đối với người dùng cuối, nó không tạo ra nhiều khác biệt.
        - __Windows__ chúng ta có dòng lệnh nhưng có thể sử dụng như dòng lệnh Linux. Chúng ta cần chạy và nhập cmd thì dòng lệnh sẽ mở.
    - Mức độ chạy
        - __Linux__ có khả năng dừng ở các cấp độ chạy khác nhau. Với điều này, chúng ta có thể làm việc bằng cách sử dụng một dòng lệnh và GUI nếu có ai đó gặp sự cố.
        - __Windows__ nếu chúng ta gặp phải bất kỳ sự cố nào để khắc phục sự cố, bắt buộc phải khởi động lại ở cấp 3 với tư cách quản trị viên để tìm và khắc phục sự cố.
    - Khả năng sử dụng
        - __Linux__ rất phức tạp để cài đặt nhưng có khả năng hoàn thành các tác vụ phức tạp dễ dàng hơn.
        - __Windows__ cung cấp cho người dùng một hệ thống đơn giản để vận hành nhưng sẽ mất nhiều thời gian hơn để cài đặt.
    - Hỗ trợ
        - __Linux__ có hỗ trợ thông qua một cộng đồng lớn các diễn đàn / trang web người dùng và tìm kiếm trực tuyến.
        - __Windows__ có hỗ trợ dễ dàng truy cập, các diễn đàn / trang web trực tuyến và có cả hỗ trợ trả phí.
    - Cập nhật
        - __Linux__ người dùng có toàn quyền kiểm soát các bản cập nhật, chúng tôi có thể cài đặt bất cứ khi nào chúng tôi cần và sẽ mất ít thời gian hơn mà không cần khởi động lại.
        - __Windows__ các bản cập nhật sẽ đến vào những thời điểm bất tiện như bạn đang in một bản in cho máy in nhưng đột nhiên bản cập nhật bật lên sẽ khiến người dùng bực bội và mất nhiều thời gian hơn để cài đặt.
    - Bảo mật
        - __Linux__ an toàn hơn so với __Windows__, tin tặc hoặc nhà phát triển vi-rút sẽ khó xâm nhập vào Linux.
        - __Windows__ là mục tiêu chính của các nhà phát triển virus và phần mềm độc hại và nó rất dễ xâm nhập nếu không có phần mềm chống vi-rút.
## 3. Các bản phân phối nổi bật Linux. Tìm hiểu về bản phân phối RHEL và Centos. Tìm hiểu về giấy phép trong Linux và chu kỳ phát triển của một bản phân phối
- ### Các bản phân phối nổi bật Linux.
    - Các bản phân phối Linux phổ biến bao gồm __Debian, Fedora, và Ubuntu__. Các bản phân phối thương mại bao gồm __Red Hat Enterprise Linux và SUSE Linux Enterprise Server__. Bản phân phối Desktop Linux bao gồm một windowing system như __X11 hoặc Wayland__, và một môi trường desktop giống như __GNOME hay KDE Plasma__.
- ### Tìm hiểu về bản phân phối RHEL và Centos.
    - #### Khái niệm RHEL.
        - RHEL là gì?
            - __Red Hat Enterprise Linux (RHEL)__ là một bản phân phối Linux được phát triển bởi Red Hat và mục tiêu hướng tới thị trường thương mại.
            - __Red Hat Enterprise Linux__ được phát hành cho các phiên bản máy chủ x86, x86-64, Itanium, PowerPC và IBM System z, và các phiên bản máy tính để bàn cho x86 và x86-64.
        - Nguồn gốc của RHEL
            - Phiên bản đầu tiên của Red Hat Enterprise Linux phân phối ra thị trường được mang tên ___"Red Hat Linux Advanced Server"___
            - Năm 2003 Red Hat đổi thương hiệu **Red Hat Linux Advanced Server** thành ***"Red Hat Enterprise Linux AS"***, và bổ sung thêm hai biến thể, __Red Hat Enterprise Linux ES__ và __Red Hat Enterprise Linux WS__.
    - #### Khái niệm Centos.
        - Centos là gì?
            - __CentOS__ là một hệ điều hành Linux dựa trên mã nguồn mở của Red Hat Enterprise Linux (RHEL).
            - Tên gọi **"CentOS"** được viết tắt từ cụm từ **"Community ENTerprise Operating System".**
        - #### Tổng hợp các phiên bản của CentOS
            - **CentOS 2**: Phiên bản đầu tiên của CentOS, được phát hành vào năm 2004. Nó dựa trên Red Hat Enterprise Linux 2.
            - **CentOS 5**: Một bản phát hành quan trọng được hỗ trợ lâu dài, được phát hành vào năm 2007. Nền tảng cung cấp nhiều cải tiến về hiệu suất và tính ổn định.
            - **CentOS 6**: Phát triển hành động vào năm 2010, CentOS 6 mở rộng các tính năng và công nghệ mới, nhất là với bản cập nhật cốt lõi của hệ điều hành.
            - **CentOS 7**: Là một trong những bản phát hành quan trọng nhất, CentOS 7 ra mắt vào năm 2014 với cải tiến đáng kể về hiệu suất, bảo mật và hỗ trợ phần cứng mới.
            - **CentOS 8**: Là phiên bản mới nhất, được phát hành vào năm 2019. CentOS 8 mang đến sự cải tiến về công nghệ, bảo mật và hiệu suất.
- ### Tìm hiểu về giấy phép trong Linux và chu kỳ phát triển của một bản phân phối
    - #### Tìm hiểu về giấy phép trong Linux
        - ##### Giấy phép GNU General Public License (GPL)
            - **Phiên bản**: GPL có nhiều phiên bản, phổ biến nhất là GPLv2 và GPLv3.
            - **Điều khoản**: GPL yêu cầu bất kỳ phần mềm nào dựa trên mã nguồn GPL cũng phải được phát hành dưới cùng một giấy phép. Điều này có nghĩa là người dùng có quyền sửa đổi, sử dụng, và phân phối phần mềm, nhưng phải giữ mã nguồn mở cho các phiên bản sau.
            - **Sử dụng**: Nhiều bản phân phối Linux, như Debian và Ubuntu, sử dụng giấy phép GPL cho kernel và các phần mềm liên quan.
        - ##### Giấy phép MIT
            - **Đặc điểm**: Rất đơn giản và linh hoạt. Người dùng có quyền sử dụng, sao chép, chỉnh sửa, và phân phối phần mềm mà không có nhiều hạn chế.
            - **Tính năng**: Phổ biến trong cộng đồng mã nguồn mở, vì nó không yêu cầu phát hành mã nguồn của phần mềm đã sửa đổi.
        - ##### Giấy phép Apache
            - **Đặc điểm**: Tương tự như MIT nhưng có thêm các điều khoản bảo vệ quyền sở hữu trí tuệ.
            - **Điều khoản**: Cho phép sửa đổi và phân phối, nhưng yêu cầu ghi nhận tác giả ban đầu và cung cấp bản sao giấy phép khi phân phối.
        - ##### Giấy phép BSD
            - **Loại**: Có nhiều biến thể, nhưng nhìn chung là rất mở.
            - **Điều khoản**: Cho phép sử dụng, sao chép và phân phối với ít hạn chế. Một số biến thể yêu cầu ghi nhận tác giả.
        - ##### Giấy phép Creative Commons
            - Sử dụng: Thường không được sử dụng cho phần mềm, mà chủ yếu cho nội dung như văn bản, hình ảnh, và video.
    - #### Quá trình phát triển của Centos.
        - **CentOS** (Hệ điều hành Enterprise cộng đồng) được phát triển dựa trên mã nguồn mở của **Red Hat Enterprise Linux (RHEL)**. Đây là một dự án cộng đồng được bắt đầu vào năm 2004.
        - Ban đầu, các phiên bản CentOS được xây dựng trực tiếp từ mã nguồn của RHEL và không có những thay đổi đáng kể.
        - Sau này, với sự phát triển và mở rộng của cộng đồng người dùng đã giúp CentOS đã trở thành một dự án độc lập.
        - Nền tảng nổi bật với nhiều lựa chọn đa dạng, khả năng mở rộng các tính năng riêng chứ không chỉ là một bản sao chép của RHEL.
        - Năm 2014, Red Hat đã mua lại CentOS và công bố một chiến lược hợp lý chặt chẽ hơn giữa CentOS và RHEL.
## 4. Tìm hiểu các tổ chức, website phát triển các dự án liên quan đến Linux và các bản phân phối. Các website liên quan đến đóng góp, fix lỗi bug, đóng góp code.
- ### **Tổ chức phát triển Linux**
    - **The Linux Foundation**: Đây là tổ chức chính hỗ trợ phát triển Linux và nhiều dự án mã nguồn mở khác. Họ tổ chức các khóa học, sự kiện và phát triển các dự án lớn như Kubernetes.
    - **Debian Project**: Dự án Debian là một trong những bản phân phối Linux lâu đời và có cộng đồng rất mạnh. Họ có hệ thống quản lý lỗi (Debian Bug Tracking System) cho phép người dùng báo cáo và theo dõi lỗi.
    - **Fedora Project**: Fedora là một bản phân phối Linux do cộng đồng hỗ trợ và có nhiều cơ hội để đóng góp mã. Họ có một trang web riêng cho việc báo cáo lỗi và phát triển.
    - Ubuntu Community: Cộng đồng Ubuntu cũng rất phát triển và cung cấp nhiều cơ hội cho người dùng đóng góp mã, báo cáo lỗi và tham gia vào các dự án.
- ### **Trang web đóng góp**
    - **GitHub**: Nhiều dự án mã nguồn mở, bao gồm cả Linux và các bản phân phối, được lưu trữ trên GitHub. Bạn có thể tìm kiếm các dự án và tham gia vào việc đóng góp mã hoặc sửa lỗi.
    - **GitLab**: Tương tự như GitHub, GitLab là nơi nhiều dự án mã nguồn mở được phát triển và bạn có thể tham gia vào việc đóng góp.
    - **SourceForge**: Một nền tảng cũ hơn nhưng vẫn còn sử dụng cho một số dự án mã nguồn mở.
    - **Open Source Initiative (OSI)**: Tổ chức này không chỉ cấp phép cho các dự án mã nguồn mở mà còn cung cấp thông tin về cách tham gia và đóng góp.
- ### **Hệ thống báo cáo lỗi và đóng góp mã**
    - **Bugzilla**: Nhiều dự án, như Mozilla và Fedora, sử dụng Bugzilla để theo dõi lỗi và đóng góp.
    - **Redmine**: Một số dự án mã nguồn mở sử dụng Redmine để quản lý lỗi và nhiệm vụ.
    - **Launchpad**: Là công cụ quản lý dự án và phát triển phần mềm được Ubuntu sử dụng, cho phép người dùng báo cáo lỗi và đóng góp mã.
- ### **Các trang tài liệu và hướng dẫn**
    - **Kernel Newbies**: Cung cấp hướng dẫn cho những người mới bắt đầu tham gia phát triển Linux kernel.
    - **Linux Documentation Project**: Tập hợp tài liệu, hướng dẫn và thông tin hữu ích cho người dùng và nhà phát triển Linux.
    - **FreeCodeCamp và các khóa học trực tuyến**: Nơi bạn có thể học về Linux và các công nghệ mã nguồn mở thông qua các khóa học miễn phí.
## 5. Cấu trúc kernel và quá trình khởi động trong Linux và các INIT Level
- ### Cấu trúc Kernel trong Linux
    - #### Kernel là gì?
        - **Kernel** là phần lõi của hệ điều hành Linux, chịu trách nhiệm quản lý phần cứng và cung cấp các dịch vụ cơ bản cho các chương trình chạy trên hệ thống.
    - #### Cấu trúc kernel bao gồm các phần chính sau:
        - **Process Management**: Quản lý các tiến trình, bao gồm tạo, hủy và lên lịch tiến trình.
        - **Memory Management**: Quản lý bộ nhớ, bao gồm việc cấp phát và giải phóng bộ nhớ cho các tiến trình.
        - **Device Drivers**: Giao tiếp với phần cứng thông qua các driver, giúp kernel quản lý các thiết bị như ổ đĩa, mạng, và các thiết bị ngoại vi khác.
        - **File System Management**: Cung cấp các giao thức để truy cập và quản lý dữ liệu trên các thiết bị lưu trữ.
        - **Networking**: Quản lý các kết nối mạng và giao thức truyền thông.
- ### Quá trình khởi động trong Linux
    - **Power On Self Test (POST)**: Khi bật máy, BIOS/UEFI kiểm tra phần cứng.
    - **Boot Loader**: BIOS/UEFI tìm kiếm bootloader (như GRUB hoặc LILO) trên ổ đĩa để tải kernel vào bộ nhớ.
    - **Kernel Initialization**: Bootloader nạp kernel vào bộ nhớ và chuyển quyền điều khiển cho nó. Kernel sẽ khởi tạo các driver và cấu hình phần cứng.
    - **Init Process**: Sau khi kernel hoàn tất khởi động, nó sẽ gọi tiến trình `init` (hoặc systemd trong nhiều hệ thống hiện đại) để bắt đầu các dịch vụ và thiết lập môi trường cho người dùng.
- ### Các mức INIT (Runlevels)
    - #### Khái niệm
        - **Runlevels** là các mức hoạt động mà hệ thống có thể ở trong đó. Mỗi runlevel tương ứng với một trạng thái hệ thống khác nhau.
    - #### Các runlevels phổ biến
        - **Runlevel 0**: Tắt máy (halt).
        - **Runlevel 1**: Chế độ một người dùng (single-user mode), chỉ cho phép một người dùng đăng nhập, thường dùng cho bảo trì hệ thống.
        - **Runlevel 2**: Chế độ đa người dùng không có mạng.
        - **Runlevel 3**: Chế độ đa người dùng với mạng.
        - **Runlevel 4**: Chế độ tùy chỉnh (thường không được sử dụng).
        - **Runlevel 5**: Chế độ đa người dùng với giao diện đồ họa (X Window System).
        - **Runlevel 6**: Khởi động lại (reboot).
    - **Ghi chú**: Với hệ thống sử dụng `systemd`, các runlevels được thay thế bằng "targets", nhưng khái niệm vẫn tương tự. Ví dụ, `graphical.target` tương ứng với runlevel 5 và `multi-user.target` tương ứng với runlevel 3.
## 6. Filesystem là gì? Các type filesystem được Linux hỗ trợ, So sánh các loại này. Cấu trúc thư mục phân cấp trong Linux.
- ### Filesystem là gì?
    - **File System** là một phần mềm hoặc hệ thống được sử dụng để quản lý, tổ chức và lưu trữ dữ liệu trên các thiết bị lưu trữ như đĩa cứng, ổ đĩa USB hoặc thẻ nhớ. Nó cung cấp cho người dùng một giao diện để truy cập và quản lý các tệp tin và thư mục trong một hệ thống lưu trữ.
    - **File System** cũng đảm bảo tính toàn vẹn và bảo mật của dữ liệu bằng cách kiểm soát quyền truy cập và cung cấp các tính năng sao lưu và khôi phục dữ liệu. Một hệ thống tập tin phải hỗ trợ đủ các tính năng như tên file, đường dẫn, kích thước, quyền truy cập và thời gian tạo, sửa đổi và truy cập file.
    - **File System** là một thành phần quan trọng trong hệ thống máy tính, đặc biệt là khi nó liên quan đến các ứng dụng quản lý dữ liệu lớn và cần sự đáng tin cậy cao.
- ### Các type filesystem được Linux hỗ trợ, So sánh các loại này.
    - #### Các type filesystem được Linux hỗ trợ
        - **Filesystem cơ bản**: EXT2, EXT3, EXT4, XFS, Btrfs, JFS, NTFS,…
        - **Filesystem dành cho dạng lưu trữ Flash**: thẻ nhớ,…
        - **Filesystem dành cho hệ cơ sở dữ liệu**
        - **Filesystem mục đích đặc biệt**: procfs, sysfs, tmpfs, squashfs, debugfs,…
    - #### Một số loại filesystem phổ biến trong Linux và ưu nhược điểm
        - **ext2 (Second Extended Filesystem)**
            - **Đặc điểm**:
                - Ra đời vào năm 1993.
                - Không hỗ trợ journaling, nghĩa là không ghi lại các thay đổi trước khi thực hiện.
            - **Ưu điểm**:
                - Đơn giản và ổn định, thích hợp cho các hệ thống nhúng hoặc thiết bị lưu trữ nhỏ.
            - **Nhược điểm**:
                - Không bảo vệ dữ liệu tốt khi hệ thống bị tắt đột ngột.
        - **ext3 (Third Extended Filesystem)**
            - **Đặc điểm**:
                - Cải tiến từ ext2 với khả năng journaling.
                - Có thể chuyển đổi từ ext2 sang ext3 mà không cần format lại.
            - **Ưu điểm**:
                - An toàn hơn so với ext2 nhờ khả năng khôi phục nhanh sau sự cố.
            - **Nhược điểm**:
                - Hiệu suất thấp hơn so với các filesystem hiện đại khác do cách thực hiện journaling.
        - **ext4 (Fourth Extended Filesystem)**
            - **Đặc điểm**:
                - Cải tiến từ ext3, hỗ trợ các tệp lớn hơn (lên đến 1 exabyte).
                - Thời gian khởi động nhanh hơn và hiệu suất tốt hơn.
            - **Ưu điểm**:
                - Hỗ trợ journaling, làm việc với các tệp lớn, tăng tốc độ truy cập.
            - **Nhược điểm**:
                - Có thể phức tạp hơn trong việc khôi phục dữ liệu so với ext2/ext3.
        - **XFS**
            - **Đặc điểm**:
                - Hệ thống tệp high-performance, được phát triển bởi SGI.
                - Tối ưu cho các khối lượng dữ liệu lớn và hỗ trợ journaling.
            - **Ưu điểm**:
                - Tốc độ ghi nhanh và hiệu suất cao khi xử lý dữ liệu lớn.
            - **Nhược điểm**:
                - Có thể kém hiệu quả với các tệp nhỏ hoặc khối lượng dữ liệu nhỏ.
        - **Btrfs (B-tree Filesystem)**
            - **Đặc điểm**:
                - Hệ thống tệp mới hơn, được thiết kế để thay thế ext4.
                - Hỗ trợ snapshot, RAID tích hợp và khả năng tự sửa lỗi.
            - **Ưu điểm**:
                - Linh hoạt và có nhiều tính năng hiện đại, như snapshot và chia sẻ dung lượng lưu trữ.
            - **Nhược điểm**:
                - Còn đang trong quá trình phát triển, có thể gặp một số vấn đề về độ ổn định.
        - **FAT32 (File Allocation Table 32)**
            - **Đặc điểm:**
                - Hệ thống tệp phổ biến trên các thiết bị di động và USB.
            - **Ưu điểm**
                - Tương thích cao với nhiều hệ điều hành, dễ dàng sử dụng trên các thiết bị khác nhau.
            - **Nhược điểm**:
                - Giới hạn kích thước tệp tối đa là 4GB, không hỗ trợ các tính năng hiện đại như bảo mật và phân quyền.
    - #### So sánh các loại này
        |Filesystem|Journaling|Kích thước tệp tối đa|Hiệu suất |Tính năng nâng cao|Tương thích|
        |:--------:|:--------:|:-------------------:|:--------:|:----------------:|:---------:|
        |   ext2   |  Không   |          2TB        |Thấp      |Không             |Thấp       |
        |   ext3   |    Có    |          2TB        |Trung bình|Không             |Trung bình |
        |   ext4   |    Có    |          1EB        |Cao       |Hỗ trợ snapshot   |Trung bình |
        |   XFS    |    Có    |          8EB        |Rất cao   |Hỗ trợ snapshot   |Thấp       |
        |  Btrfs   |    Có    |          16EB       |Trung bình|Snapshot, RAID    |Thấp       |
        |  FAT32   |  Không   |          4GB        |Thấp      |Không             |Rất cao    |
- ### Cấu trúc thư mục phân cấp trong Linux
    - **Thư mục gốc /**
        - Đây là thư mục gốc (root directory) của hệ thống. Tất cả các thư mục khác đều nằm dưới thư mục này.
    - **Thư mục con chính trong /**
        - **`/bin`: Chứa các tệp thực thi (binaries) của các lệnh cơ bản mà người dùng có thể sử dụng, như `ls`, `cp`, `mv`, và `cat`.**
        - `/boot`: Chứa các tệp cần thiết để khởi động hệ thống, bao gồm kernel và các tệp cấu hình liên quan đến quá trình khởi động.
        - `/dev`: Chứa các tệp thiết bị (device files) đại diện cho các thiết bị phần cứng như ổ đĩa, ổ USB, và các thiết bị ngoại vi.
        - **`/etc`: Chứa các tệp cấu hình cho hệ thống và các ứng dụng. Ví dụ: `passwd`, `fstab`, `hosts`.**
        - **`/home`: Chứa thư mục người dùng. Mỗi người dùng sẽ có thư mục con của mình trong thư mục này, thường được đặt theo tên người dùng (ví dụ: `/home/user`).**
        - `/lib`: Chứa các thư viện (libraries) cần thiết cho các chương trình trong `/bin` và `/sbin`.
        - `/media`: Thư mục tạm thời để gắn kết (mount) các thiết bị lưu trữ di động, như USB hoặc đĩa CD/DVD.
        - `/mnt`: Thư mục tạm thời để gắn kết các hệ thống tệp. Thường được sử dụng bởi quản trị viên hệ thống.
        - `/opt`: Chứa các ứng dụng phần mềm tùy chọn và các gói phần mềm bổ sung mà không phải là một phần của hệ thống chính.
        - `/proc`: Chứa thông tin về các tiến trình đang chạy và trạng thái hệ thống. Đây là hệ thống tệp ảo, không thực sự lưu trữ trên đĩa.
        - `/root`: Thư mục chính của người dùng root (superuser). Đây là tài khoản quản trị viên của hệ thống.
        - **`/sbin`: Chứa các tệp thực thi của các lệnh hệ thống và quản trị, thường chỉ được sử dụng bởi quản trị viên.**
        - `/srv`: Chứa dữ liệu cho các dịch vụ mà hệ thống cung cấp (ví dụ: tệp web cho server web).
        - `/sys`: Thư mục hệ thống ảo cung cấp thông tin về thiết bị phần cứng và kernel.
        - `/tmp`: Thư mục chứa tệp tin tạm thời. Các tệp ở đây có thể bị xóa khi khởi động lại hệ thống.
        - `/usr`: Chứa dữ liệu người dùng, bao gồm thư viện, chương trình và tài liệu. Một số thư mục con chính trong `/usr` là:
            - `/usr/bin`: Chứa các tệp thực thi cho người dùng.
            - `/usr/lib`: Chứa thư viện cho các chương trình trong `/usr/bin`.
            - `/usr/share`: Chứa các tệp chia sẻ như tài liệu và mẫu.
        - **`/var`: Chứa các tệp dữ liệu có kích thước thay đổi thường xuyên, như nhật ký (logs), tệp tin tạm, và cơ sở dữ liệu.**
    - chức năng của nhưng file log 
## 7. Hiểu cấu trúc thư mục cây trong linux, khái niệm về đường dẫn, sử dụng các lệnh cơ bản thao tác với 1 thư mục `cd`, `pwd`, `ls`. Trong Linux các thư mục, socket ... thực chất là gì ? 
- ### Hiểu cấu trúc thư mục cây trong linux, khái niệm về đường dẫn, sử dụng các lệnh cơ bản thao tác với 1 thư mục `cd`, `pwd`, `ls`.
    - #### Hiểu cấu trúc thư mục cây trong linux
        - Thư mục gốc (`/`): Là thư mục đầu tiên và cao nhất trong hệ thống, từ đó tất cả các thư mục khác được xây dựng.
        - Thư mục con: Mỗi thư mục có thể chứa các thư mục con, tạo thành một cấu trúc giống như cây. Ví dụ, từ thư mục gốc, bạn có thể có các thư mục như `/home`, `/etc`, `/usr`, v.v. Từ thư mục  `/home`, `/etc`, `/usr` bạn có thể có các thư mục như `/home/user`, `/etc/opt`, `/usr/lib/`, v.v.
    - #### Khái niệm về đường dẫn
        - ##### Khái Niệm
            - **Đường dẫn** trong hệ thống tệp của Linux (và các hệ điều hành tương tự UNIX) rất quan trọng để xác định vị trí của tệp tin hoặc thư mục.
        - ##### Các loại đường dẫn 
            - **Đường dẫn tuyệt đối (Absolute Path)**
                - **Định nghĩa**: Là đường dẫn bắt đầu từ thư mục gốc (/). Nó cung cấp thông tin đầy đủ về vị trí của tệp tin hoặc thư mục trong cây thư mục.
                - **Cấu trúc**: Đường dẫn tuyệt đối luôn bắt đầu bằng dấu / theo sau là chuỗi các thư mục.
                - **Ví dụ**:
                    - `/home/user/Documents/file.txt`: Đường dẫn này chỉ đến tệp `file.txt` trong thư mục `Documents`, thuộc về người dùng `user`.
            - **Đường dẫn tương đối (Relative Path)**
                - **Định nghĩa**: Là đường dẫn được xác định dựa trên thư mục hiện tại, không bắt đầu bằng dấu /. Đường dẫn tương đối chỉ rõ vị trí của tệp tin hoặc thư mục từ thư mục mà bạn đang làm việc.
                - **Cấu trúc**: Đường dẫn tương đối có thể chứa tên thư mục hoặc tệp tin, và có thể sử dụng ký hiệu đặc biệt để điều hướng lên hoặc xuống trong cây thư mục.
                - **Ví dụ**:
                    - Nếu bạn đang ở trong thư mục `/home/user`, bạn có thể tham chiếu đến tệp `file.txt` trong thư mục `Documents` bằng đường dẫn tương đối là `Documents/file.txt`.
        - ##### Ký hiệu đặc biệt trong đường dẫn
            - `.`: Đại diện cho thư mục hiện tại.
                - Ví dụ: `./file.txt` chỉ đến tệp `file.txt` trong thư mục hiện tại.
            - `..`: Đại diện cho thư mục cha (thư mục chứa thư mục hiện tại).
                - Ví dụ: `../Documents` sẽ chuyển đến thư mục `Documents` nằm ở cấp cao hơn so với thư mục hiện tại.
        - ##### Sử dụng các lệnh cơ bản thao tác với 1 thư mục cd, pwd, ls
            - Lệnh `cd` (Change Directory) được sử dụng để thay đổi thư mục hiện tại trong terminal.
                - Ví Dụ: cd /home/user/Documents/file.txt
            - Lệnh `pwd` (Print Working Directory) được sử dụng để hiển thị đường dẫn đầy đủ của thư mục hiện tại mà bạn đang làm việc.
                - Ví Dụ: `pwd` Khi bạn chạy lệnh này, nó sẽ trả về đường dẫn đầy đủ của thư mục hiện tại: `/home/user/Documents`
            - Lệnh `ls` (List) được sử dụng để liệt kê các tệp tin và thư mục trong thư mục hiện tại.
                - Ví Dụ: 
                    - Liệt kê các tệp tin và thư mục trong thư mục hiện tại: `ls`
                    - Liệt kê chi tiết với thông tin bổ sung (như quyền, kích thước, thời gian tạo): `ls -l`
                    - Liệt kê tất cả các tệp, bao gồm các tệp ẩn (tệp bắt đầu bằng dấu chấm): `ls -a`
                    - Liệt kê trong một thư mục cụ thể: `ls /home/user`
- ### Trong Linux các thư mục, socket ... thực chất là gì ?
    - #### Trong Linux, các thư mục, socket và các loại tệp khác nhau đều được quản lý trong hệ thống tệp (filesystem) và có các khái niệm cụ thể như sau:
        - ##### Thư mục (Directory)
            - **Định nghĩa**: Thư mục là một tập hợp các tệp tin và thư mục con. Nó giúp tổ chức và quản lý tệp tin theo cấu trúc phân cấp, tạo ra một cây thư mục.
            - **Chức năng**: Thư mục cho phép người dùng nhóm các tệp tin liên quan lại với nhau, giúp dễ dàng tìm kiếm và quản lý.
        - ##### Socket
            - **Định nghĩa**: Socket là một giao diện để giao tiếp giữa các tiến trình (process) trên cùng một máy hoặc trên các máy khác trong mạng. Sockets cho phép truyền tải dữ liệu qua các giao thức mạng.
            - **Đặc điểm**: Sockets trong Linux được coi là tệp, và bạn có thể tương tác với chúng giống như các tệp tin thông thường. Chúng có thể được sử dụng để gửi và nhận dữ liệu qua các giao thức mạng như TCP/IP hoặc UDP.
            - **Chức năng**: Socket được sử dụng trong lập trình mạng để thiết lập kết nối giữa máy chủ và máy khách, cho phép truyền tải dữ liệu hai chiều.
            - **Loại**: Có hai loại socket chính:
                - **Stream Sockets**: Sử dụng giao thức TCP, cho phép giao tiếp liên tục và có kết nối.
                - **Datagram Sockets**: Sử dụng giao thức UDP, cho phép gửi dữ liệu không cần kết nối.
        - ##### Tệp (File)
            - **Định nghĩa**: Tệp là một đơn vị lưu trữ thông tin trong hệ thống tệp. Tệp có thể là tệp văn bản, tệp nhị phân, hình ảnh, video, v.v.
            - **Chức năng**: Tệp chứa dữ liệu mà người dùng cần sử dụng hoặc lưu trữ.
        - ##### Tệp thiết bị (Device Files)
            - **Định nghĩa**: Tệp thiết bị là các tệp đại diện cho các thiết bị phần cứng trong hệ thống, như ổ đĩa, bàn phím, và chuột.
            - **Chức năng**: Thông qua các tệp thiết bị, kernel của hệ điều hành có thể giao tiếp với phần cứng.
        - ##### Tệp ẩn (Hidden Files)
            - **Định nghĩa**: Tệp ẩn là các tệp tin bắt đầu bằng dấu chấm (.) trong Linux, không được liệt kê mặc định khi sử dụng lệnh ls.
            - **Chức năng**: Tệp ẩn thường được sử dụng để lưu trữ các tệp cấu hình hoặc các tệp không cần hiển thị cho người dùng thông thường.
## 8. Tìm hiểu lệnh `man`
- ### Khái Niệm
    - Lệnh `man` trong Linux (viết tắt của manua) là công cụ dùng để tra cứu thông tin chi tiết về bất kỳ lệnh nào. Khi sử dụng man, bạn sẽ được cung cấp một trang hướng dẫn đầy đủ bao gồm tóm tắt, mô tả, tùy chọn, trạng thái thoát, tác giả, bản quyền,…
- ### Các tùy chọn sử dụng lệnh man
    - man -k , --apropos : Tìm kiếm từ khóa trong toàn bộ trang hướng dẫn và hiển thị tất cả các kết quả khớp
    - man -f, --whatis : Tìm kiếm mô tả ngắn về bất kỳ từ khóa hoặc lệnh nào
    - man -d, –default : Đặt lại lệnh man về mặc định
    - man -i, –ignore-case : Bỏ qua sự phân biệt chữ hoa chữ thường của lệnh
    - man -I, –match-case : Tìm kiếm chính xác chữ hoa chữ thường
    - man -a, –all : Hiển thị tất cả các trang hướng dẫn khớp với từ khóa hoặc lệnh cụ thể
## 9. Câu lệnh làm việc với tập tin như đọc, ghi,.. (liệt kê tất cả có thể)
- `cat`: đọc file
- `vi`: sửa file
- `vim`: sửa file
- `cd`: di chuyển thư mục
- `ls`: show file và thư mục trong thư mục hiện tại
- `echo`: ghi vào file
- `find`: tìm file
- `pwd`: show đường dẫn hiện tại đang làm việc
- `top`: hiển thị trang thái cấu hình
- `df`: hiển thị dung lượng trên ổ cứng
- `passwd` đổi pass user

## 10. Tìm hiểu về nhóm người dùng trong Linux
- ### Khái niệm về nhóm người dùng
    - **Người dùng (User)**: Là một cá nhân hoặc tiến trình có thể đăng nhập và sử dụng hệ thống. Mỗi người dùng có một tên đăng nhập (username) và một mã số định danh (user ID - UID).
    - **Nhóm (Group)**: Là một tập hợp của một hoặc nhiều người dùng. Nhóm giúp tổ chức và quản lý quyền truy cập cho nhiều người dùng cùng một lúc. Mỗi nhóm có một tên và một mã số định danh (group ID - GID).
- ### Vai trò của nhóm người dùng
    - **Quản lý quyền truy cập**: Nhóm giúp đơn giản hóa việc cấp quyền cho nhiều người dùng. Thay vì cấp quyền cho từng người dùng riêng lẻ, bạn có thể cấp quyền cho cả nhóm.
    - **Chia sẻ tài nguyên**: Các thành viên trong cùng một nhóm có thể chia sẻ tệp tin và thư mục dễ dàng hơn.
- ### Các loại nhóm
    - **Nhóm chính (Primary Group)**: Mỗi người dùng chỉ có một nhóm chính, được chỉ định khi tạo tài khoản. Nhóm này thường là nhóm mà người dùng thuộc về.
    - **Nhóm phụ (Secondary Group)**: Người dùng có thể thuộc về nhiều nhóm phụ. Điều này cho phép người dùng có quyền truy cập vào các tài nguyên mà các nhóm khác sở hữu.
- ### Quản lý nhóm người dùng
    - **Xem thông tin người dùng và nhóm**
        - **cat /etc/passwd**: Hiển thị danh sách người dùng cùng với UID và nhóm chính.
        - **cat /etc/group**: Hiển thị danh sách các nhóm và các thành viên trong từng nhóm.
    - **Tạo nhóm**
        - **Lệnh**: `groupadd [tên nhóm]`
            - Ví dụ: 
                ```
                groupadd IT
                ```
    - **Thêm người dùng vào nhóm**
        - **Lệnh**: `usermod -aG [tên nhóm] [tên người dùng]`
            - Ví dụ:
                ```
                sudo usermod -aG IT user1
                ```
    - **Xóa nhóm**
        - **Lệnh**: `groupdel [tên nhóm]`
            - Ví Dụ:
                ```
                groupdel IT
                ```
- ### Quyền truy cập và nhóm
    - **Mỗi tệp tin và thư mục trong Linux có ba loại quyền truy cập**:
        - **Read (r)**: Quyền đọc.
        - **Write (w)**: Quyền ghi.
        - **Execute (x)**: Quyền thực thi.
    - **Quyền truy cập được chia cho ba loại người**:
        - **Người sở hữu (Owner)**: Người dùng tạo ra tệp tin.
        - **Nhóm (Group)**: Nhóm mà tệp tin thuộc về.
        - **Khác (Others)**: Những người dùng không thuộc về người sở hữu hoặc nhóm.
## 11. Tìm hiểu về người dùng trong User. Các loại người dùng trong Linux. Với mỗi loại họ có quyền gì trong hệ thống.
- ### Root (Superuser)
    - **Tên người dùng**: root
    - **Quyền hạn**:
        - Root là người dùng có toàn quyền kiểm soát tất cả các tài nguyên của hệ thống, bao gồm thay đổi cấu hình hệ thống, quản lý các tài khoản người dùng, cài đặt phần mềm, và truy cập vào mọi tập tin trên hệ thống.
        - Root có thể thực thi mọi lệnh và có khả năng làm thay đổi hệ thống mà không bị giới hạn.
        - Người dùng root có quyền đọc, ghi, và thay đổi mọi thứ trên hệ thống, kể cả các tệp hệ thống và tệp người dùng khác.
- ### Normal User (Người dùng bình thường)
    - **Tên người dùng**: Không cố định, người dùng có thể có tên tùy chỉnh.
    - **Quyền hạn**:
        - Người dùng bình thường chỉ có quyền truy cập vào thư mục và tài nguyên mà họ sở hữu. Họ không thể thay đổi hoặc truy cập vào các tệp của người dùng khác nếu không có sự cấp quyền.
        - Người dùng bình thường có thể thực thi các chương trình và ứng dụng trong phạm vi quyền hạn của mình, chẳng hạn như thay đổi cấu hình cá nhân, chỉnh sửa các tệp cá nhân, hoặc chạy các ứng dụng mà họ được phép.
        - Họ không thể thay đổi các cài đặt hệ thống hoặc thực hiện các hành động ảnh hưởng đến toàn bộ hệ thống.
- ### Sudoers
    - **Tên người dùng**: Các người dùng hoặc nhóm được cấp quyền `sudo`
    - **Quyền hạn**:
        - Các người dùng hoặc nhóm trong danh sách sudoers có thể thực thi các lệnh với quyền root mà không cần đăng nhập với tài khoản root. Điều này giúp duy trì tính bảo mật trong khi cho phép người dùng thực hiện các tác vụ quản trị cần thiết.
        - Quyền `sudo` có thể được cấp cho từng người dùng hoặc nhóm thông qua tệp cấu hình `/etc/sudoers`.
        - Người dùng `sudo` không có quyền root đầy đủ như root, nhưng có thể tạm thời thực hiện các lệnh quản trị với quyền cao nhất bằng cách sử dụng lệnh `sudo`.
- ### System Users (Người dùng hệ thống)
    - **Tên người dùng**: Các tài khoản người dùng hệ thống thường không liên quan đến các người dùng tương tác với hệ thống, ví dụ: `daemon`, `www-data`, `nobody`, `mysql`, `ftp`.
    - **Quyền hạn**:
        - Những người dùng này có quyền hạn hạn chế và thường được sử dụng cho các dịch vụ hệ thống như máy chủ web, máy chủ cơ sở dữ liệu, hoặc dịch vụ FTP.
        - Họ không được phép truy cập vào hệ thống với các quyền thông thường và thường chỉ có quyền đọc và ghi vào các tệp cấu hình hoặc thư mục mà dịch vụ của họ yêu cầu.
        - Người dùng hệ thống này giúp cô lập các dịch vụ và bảo vệ hệ thống khỏi các lỗ hổng bảo mật.
- ### Guest User (Người dùng khách)
    - **Tên người dùng**: Tài khoản người dùng khách có thể được tạo ra để cho phép người dùng tạm thời truy cập vào hệ thống mà không yêu cầu đăng nhập chính thức.
    - **Quyền hạn**:
        - Quyền hạn của người dùng khách thường bị giới hạn rất nhiều, chỉ có quyền truy cập vào các tệp và ứng dụng cần thiết cho mục đích tạm thời.
        - Các tệp và dữ liệu của người dùng khách thường không được lưu lại sau khi họ đăng xuất.
    
    |Loại Người Dùng     |Quyền Hạn                                                                             |
    |--------------------|--------------------------------------------------------------------------------------|
    |Root (Superuser)    |Toàn quyền hệ thống, thay đổi cấu hình hệ thống, quản lý người dùng, cài đặt phần mềm.|
    |Normal User         |Quyền hạn giới hạn vào các tài nguyên cá nhân, không thể thay đổi cấu hình hệ thống.  |
    |Sudoers             |Có thể thực thi các lệnh với quyền root, nhưng không phải là root trực tiếp.          |
    |System Users        |Tài khoản hệ thống có quyền hạn hạn chế, phục vụ các dịch vụ hệ thống.                |
    |Guest User          |Quyền hạn cực kỳ hạn chế, chỉ sử dụng tạm thời và không lưu lại dữ liệu cá nhân.      |

## 12. Tìm hiểu về phân quyền trong Linux. Phân quyền cơ bản trong filesystem. Trong Linux thư mục nào được phân quyền mặc định 777 .
- ### Phân quyền trong Linux
    - Phân quyền trong Linux là cơ chế bảo mật dùng để kiểm soát quyền truy cập vào tệp và thư mục trên hệ thống. Mỗi tệp hoặc thư mục đều có ba loại quyền chính (read, write, execute) áp dụng cho ba đối tượng:
        - **Chủ sở hữu (Owner)**: Người tạo ra tệp/thư mục, mặc định là người sở hữu.
        - **Nhóm (Group)**: Một nhóm người dùng có thể chia sẻ quyền với nhau.
        - **Người khác (Others)**: Tất cả người dùng khác ngoài chủ sở hữu và nhóm.
- ### Các quyền cơ bản trong Linux
    - **Read (r)**: Quyền đọc nội dung tệp hoặc danh sách thư mục.
    - **Write (w)**: Quyền ghi, sửa đổi nội dung tệp hoặc tạo/tùy chỉnh tệp con trong thư mục.
    - **Execute (x)**:
        - Với tệp: Quyền thực thi (chạy) tệp như một chương trình.
        - Với thư mục: Quyền truy cập vào các tệp hoặc thư mục con bên trong.

    Quyền của một tệp/thư mục được hiển thị dưới dạng 10 ký tự. Ví dụ:

        -rwxr-xr--

    Trong đó:
    - Ký tự đầu tiên (d hoặc -) cho biết loại tệp: `-` (tệp thường), `d` (thư mục), `l` (liên kết mềm).
    - 9 ký tự còn lại chia thành 3 nhóm:
        - Chủ sở hữu: `rwx`
        - Nhóm: `r-x`
        - Người khác: `r--`
- ### Hệ thống phân quyền số (Octal)
    - Các quyền trong Linux cũng được biểu diễn bằng các con số:
        - `r = 4`, `w = 2`, `x = 1`
        - Tổng hợp quyền:
            - `7 = rwx` (đầy đủ quyền)
            - `6 = rw-` (đọc và ghi)
            - `5 = r-x` (đọc và thực thi)
            - `4 = r--` (chỉ đọc)
            - `0 = ---` (không có quyền)
- ### Phân quyền mặc định của thư mục
    - Mặc định, Linux sử dụng lệnh `umask` để xác định quyền mặc định của tệp và thư mục khi được tạo.
        - Với tệp: Quyền mặc định là `666` (không cho phép thực thi), sau đó trừ đi `umask`.
        - Với thư mục: Quyền mặc định là `777`, sau đó trừ đi `umask`.
- ### Thư mục nào có quyền mặc định 777?
    - Một số thư mục đặc biệt trong Linux được phân quyền mặc định 777:
        - Thư mục `/tmp`:
            - Được dùng để lưu trữ tệp tạm thời, các ứng dụng có thể tạo và sử dụng.
            - Quyền `777` cho phép tất cả người dùng đọc, ghi và truy cập. Tuy nhiên, để bảo mật, thuộc tính "Sticky Bit" (`t`) được bật, khiến người dùng chỉ có thể xóa tệp của chính họ.
        - Thư mục `/var/tmp`:
            - Tương tự như /tmp nhưng thường lưu trữ dữ liệu tạm thời lâu hơn.
## 13. Tìm hiểu về phân quyền nâng cao : SUID, SGID, Sticky Bit. Và chỉ số umask
- ### SUID (Set User ID)
    - **SUID** là một quyền đặc biệt được thiết lập trên tệp tin thực thi. Khi một tệp tin có SUID, người dùng thực thi tệp tin đó sẽ tạm thời có quyền của chủ sở hữu tệp tin (thường là root).
    - **Ví dụ**: Nếu bạn thực thi một chương trình có SUID là root, bạn sẽ có quyền truy cập tương tự như root, mặc dù bạn là người dùng bình thường. Điều này có thể giúp thực thi các tác vụ cần quyền truy cập cao hơn mà không cần cấp quyền root cho người dùng.
    - **Cách thiết lập**: 
        - Sử dụng lệnh chmod: `chmod u+s filename`
    - **Ví dụ**: Tệp /usr/bin/passwd có thể có SUID để người dùng bình thường có thể thay đổi mật khẩu của mình mà không cần quyền root.
- ### SGID (Set Group ID)
    - **SGID** là một quyền đặc biệt cho phép tệp tin hoặc thư mục có hành vi tương tự như SUID nhưng đối với nhóm thay vì người dùng. Khi một tệp tin có SGID, khi người dùng thực thi tệp tin đó, nhóm quyền của tệp sẽ là nhóm của tệp chứ không phải nhóm của người dùng.
    - **Tệp tin**: Tương tự như SUID, khi SGID được thiết lập cho một tệp tin thực thi, chương trình sẽ chạy với quyền nhóm của chủ sở hữu tệp.
    - **Thư mục**: Khi SGID được thiết lập cho một thư mục, tất cả các tệp tin mới tạo trong thư mục đó sẽ thuộc về nhóm của thư mục, không phải nhóm của người tạo tệp tin.
    - **Cách thiết lập**: 
        - Sử dụng lệnh chmod: `chmod g+s filename_or_directory`
- ### Sticky Bit
    - **Sticky Bit** thường được thiết lập trên các thư mục, đặc biệt là thư mục /tmp, để ngăn người dùng xóa hoặc thay đổi các tệp tin của người khác trong thư mục đó.
    - Khi một thư mục có Sticky Bit, chỉ có chủ sở hữu của tệp tin hoặc thư mục, hoặc người dùng root mới có quyền xóa hoặc đổi tên các tệp tin bên trong thư mục đó.
    - **Ví dụ**: Thư mục /tmp trên hệ thống thường có Sticky Bit để đảm bảo rằng người dùng không thể xóa tệp của người dùng khác.
    - **Cách thiết lập**: 
        - Sử dụng lệnh chmod: `chmod +t directory`
- ### umask (User Mask)
    - **umask** là một giá trị được sử dụng để xác định các quyền mặc định của tệp tin và thư mục khi chúng được tạo ra.
    - **umask** xác định quyền truy cập nào sẽ bị từ chối khi tạo tệp tin. Thông qua umask, bạn có thể xác định quyền của tệp tin hoặc thư mục mới, ví dụ như tệp tin mới có thể có quyền đọc, ghi, thực thi (rwx) đối với người sở hữu, nhóm, và người khác.
    - **Cách hoạt động**: Một giá trị umask là sự khấu trừ từ quyền mặc định. Quyền mặc định cho tệp tin là 666 (rw-rw-rw-), và quyền mặc định cho thư mục là 777 (rwxrwxrwx).
    - **Ví dụ**: Nếu umask được thiết lập là `022`, quyền mặc định của tệp tin mới sẽ là `644` (rw-r--r--), và quyền của thư mục sẽ là `755` (rwxr-xr-x).
    - **Cách kiểm tra và thiết lập umask**:
        - Kiểm tra umask hiện tại: `umask`
        - Thiết lập umask mới: `umask 022`
## 14. Tìm hiểu các trình quản lý package trong ubuntu. Sự khác biệt giữa apt và dpkg là gì ?
- ### Tìm hiểu các trình quản lý package trong ubuntu
- Trong Ubuntu (cũng như các hệ điều hành dựa trên Debian), việc quản lý gói phần mềm (package management) là rất quan trọng để cài đặt, cập nhật và gỡ bỏ phần mềm trên hệ thống. Ubuntu sử dụng hệ thống quản lý gói APT (Advanced Packaging Tool) để xử lý việc cài đặt và quản lý phần mềm. Ngoài APT, còn có một số công cụ khác hỗ trợ quản lý phần mềm trên hệ thống Ubuntu.
    - #### **APT (Advanced Packaging Tool)**
        - APT là công cụ chính để quản lý gói phần mềm trong các hệ điều hành Debian-based, bao gồm Ubuntu. APT giúp dễ dàng cài đặt, cập nhật và gỡ bỏ phần mềm từ kho lưu trữ chính thức của Ubuntu.
    - Các lệnh phổ biến trong APT:
        - **Cài đặt gói phần mềm**: `sudo apt install <package_name>`
        - **Cập nhật danh sách gói phần mềm** (từ kho lưu trữ): `sudo apt update`
        - **Cập nhật tất cả gói phần mềm đã cài**: `sudo apt upgrade`
        - **Cài đặt một phiên bản cụ thể của gói**: `sudo apt install <package_name>=<version_number>`
        - **Gỡ bỏ gói phần mềm**: `sudo apt remove <package_name>`
        - **Gỡ bỏ gói phần mềm và các tệp cấu hình liên quan**: `sudo apt purge <package_name>`
        - **Dọn dẹp các gói không cần thiết** (dùng sau khi gỡ bỏ phần mềm): `sudo apt autoremove`
        - **Tìm kiếm gói phần mềm**: `apt search <package_name>`
        - **Hiển thị thông tin chi tiết của một gói phần mềm**: `apt show <package_name>`
    - #### **dpkg (Debian Package Manager)**
        - `dpkg` là công cụ quản lý gói cơ bản, thấp hơn so với APT. APT thực chất là một lớp giao diện cao hơn, sử dụng `dpkg` để cài đặt, gỡ bỏ và xử lý gói. `dpkg` không tự động xử lý kho lưu trữ, vì vậy bạn phải cung cấp gói cài đặt cụ thể (dưới dạng `.deb`).
    - Các lệnh phổ biến trong `dpkg`:
        - **Cài đặt gói** `.deb`: `sudo dpkg -i <package_file.deb>`
        - **Gỡ bỏ gói phần mềm**: `sudo dpkg -r <package_name>`
        - **Hiển thị thông tin chi tiết về gói**: `dpkg -s <package_name>`
        - **Danh sách tất cả các gói đã cài đặt**: `dpkg -l`
        - **Sửa chữa các gói bị hỏng** (nếu cài đặt với `dpkg` bị lỗi): `sudo apt --fix-broken install`
    - #### **Snap**
        - Snap là hệ thống quản lý gói mới của Ubuntu, được Canonical (nhà phát triển của Ubuntu) tạo ra để cung cấp các ứng dụng đóng gói và dễ dàng cài đặt trên mọi hệ điều hành Linux. Các gói Snap có thể chạy độc lập và không phụ thuộc vào các thư viện có sẵn trên hệ thống, giúp đơn giản hóa việc cài đặt phần mềm.
    - Các lệnh phổ biến với Snap:
        - **Cài đặt gói Snap**: `sudo snap install <package_name>`
        - **Cập nhật tất cả gói Snap**: `sudo snap refresh`
        - **Gỡ bỏ gói Snap**: `sudo snap remove <package_name>`
        - **Liệt kê các gói Snap đã cài đặt**: `snap list`
        - **Tìm kiếm gói Snap**: `snap find <package_name>`
    - #### **Flatpak**
        - **Flatpak** là một hệ thống quản lý gói tương tự như Snap, nhưng được phát triển bởi cộng đồng phần mềm mã nguồn mở. Flatpak cũng cung cấp các gói phần mềm độc lập, không phụ thuộc vào các thư viện hệ thống.
    - Các lệnh phổ biến với Flatpak:
        - **Cài đặt gói Flatpak**: `flatpak install <repository> <package_name>`
        - **Cập nhật tất cả gói Flatpak**: `flatpak update`
        - **Gỡ bỏ gói Flatpak**: `flatpak uninstall <package_name>`
        - **Liệt kê các gói Flatpak đã cài đặt**: `latpak list`
    - #### **PPA (Personal Package Archive)**
        - PPA là kho phần mềm được cung cấp bởi các nhà phát triển hoặc cộng đồng, ngoài kho chính thức của Ubuntu. PPAs cho phép bạn cài đặt phần mềm không có sẵn trong kho lưu trữ chính thức của Ubuntu.
    - Các lệnh phổ biến khi làm việc với PPA:
        - **Thêm PPA vào hệ thống**: `sudo add-apt-repository ppa:<ppa_name>`
        - **Cập nhật danh sách gói sau khi thêm PPA**: `sudo apt update`
        - **Gỡ bỏ PPA**: `sudo add-apt-repository --remove ppa:<ppa_name>`
    - #### **Ubuntu Software Center**
        - Ubuntu Software Center là giao diện đồ họa cho quản lý phần mềm trên Ubuntu. Bạn có thể sử dụng Ubuntu Software Center để cài đặt, cập nhật, và gỡ bỏ phần mềm mà không cần phải sử dụng dòng lệnh.
            - Mở **Ubuntu Software Center** từ menu ứng dụng, sau đó tìm kiếm phần mềm mà bạn muốn cài đặt hoặc gỡ bỏ.
- ### Sự khác biệt giữa apt và dpkg.
    |Tiêu chí  	   |APT	                                                                                                |dpkg                            |
    |--------------|----------------------------------------------------------------------------------------------------|--------------------------------|
    |Mục đích chính|Quản lý kho phần mềm, cài đặt, cập nhật, và nâng cấp gói từ kho phần mềm (bao gồm cả các phụ thuộc).|Quản lý các gói `.deb` riêng biệt.|
    |Quản lý kho phần mềm|Có, APT có thể tải và cài đặt gói phần mềm từ các kho phần mềm trực tuyến.|Không, dpkg chỉ làm việc với các gói `.deb` cục bộ. |
    |Quản lý phụ thuộc|Tự động xử lý phụ thuộc khi cài đặt hoặc nâng cấp gói phần mềm.|Không tự động xử lý phụ thuộc, bạn cần cài đặt các gói phụ thuộc thủ công.|
    |Cài đặt gói phần mềm|Cài đặt gói từ kho phần mềm hoặc từ PPA.|Cài đặt gói `.deb` cục bộ.|
    |Cập nhật gói phần mềm|Hỗ trợ cập nhật tất cả các gói phần mềm hệ thống từ kho phần mềm.|Không hỗ trợ cập nhật từ kho phần mềm, chỉ làm việc với các gói đã có.|
    |Quản lý nhiều gói cùng lúc|Có thể cài đặt, cập nhật và gỡ bỏ nhiều gói phần mềm cùng lúc.|Thường chỉ làm việc với một gói phần mềm mỗi lần.|
    |Lỗi và khôi phục|Tự động xử lý các vấn đề về phụ thuộc và cung cấp các phương thức khôi phục khi có lỗi.|Không hỗ trợ khôi phục tự động, phải giải quyết vấn đề thủ công.|
## 15. Tìm hiểu về Process trong Linux. Các loại process trên Linux (các lệnh quản lý process cơ bản: ps, sleep, kill, bg, fg,...)
- ### Khái Niệm
    - **Process** (tiến trình) trong Linux là một chương trình đang được thực thi. Mỗi process có một ID duy nhất gọi là **PID** (Process ID). Khi một chương trình được chạy, hệ điều hành sẽ tạo một process để quản lý và thực thi chương trình đó.
- ### Các loại Process trong Linux
    - **Parent Process**:
        - Mỗi process trong Linux được tạo ra bởi một **parent process**.
        - Parent process được nhận diện qua **PPID** (Parent Process ID).
    - **Child Process**:
        - Là process được tạo ra bởi một parent process.
        - Sử dụng lệnh `fork()` để tạo child process.
    - **Orphan Process**:
        - Khi **parent process** kết thúc trước, child process trở thành orphan process và được quản lý bởi process **init** (PID = 1).
    - **Zombie Process**:
        - Khi một child process kết thúc nhưng parent process chưa gọi lệnh `wait()` để thu hồi thông tin.
        - Zombie process không tiêu thụ tài nguyên nhưng vẫn giữ PID.
    - **Daemon Process**:
        - Là các tiến trình chạy ngầm để cung cấp các dịch vụ hệ thống (như `cron`, `sshd`).
        - Thường không có giao diện người dùng trực tiếp.
    - **Interactive Process**:
        - Các process được người dùng khởi chạy trực tiếp từ terminal.
    - **Batch Process**:
        - Các process chạy theo lô (batch), thường không cần sự tương tác trực tiếp.
- ### Quản lý Process bằng các lệnh cơ bản
    - **Xem thông tin process**
        - `ps`: Hiển thị thông tin các process đang chạy.
        - `top`: Hiển thị process theo thời gian thực.
        - `htop`: Giao diện đồ họa cho `top` (cần cài đặt thêm).
    - **Khởi chạy và tạm dừng process**
        - `sleep`: Tạo process ngủ trong một khoảng thời gian.
        - `ctrl+z`: Tạm dừng (pause) process đang chạy trong terminal.
        - `jobs`: Hiển thị danh sách các job đang chạy trong terminal.
        - `bg`: Tiếp tục chạy process bị dừng ở chế độ nền.
        - `fg`: Đưa process từ nền về foreground.
    - **Kết thúc process**
        - `kill`: Dừng một process dựa trên PID:
            - `kill PID`
            - `kill -9 PID`      # Gửi tín hiệu SIGKILL (dừng ngay lập tức)
        - `pkill`: Dừng process theo tên.
            - `pkill process_name`
        - `killall`: Dừng tất cả các process theo tên.
            - `killall process_name`
        - `xkill`: Kết thúc một cửa sổ GUI (cần cài đặt).
    - **Ưu tiên process**
        - `nice`: Chạy process với mức ưu tiên được chỉ định.
        - `renice`: Thay đổi mức ưu tiên của một process đang chạy.
    - **Kiểm tra cấu trúc process**
        - `pstree`: Hiển thị cấu trúc cây process.
- ### Các tín hiệu (signal) thường dùng với lệnh `kill`
    |Tín hiệu|Mã số|               Mô tả               |
    |--------|-----|-----------------------------------|
    |SIGTERM |15   |Dừng một cách nhẹ nhàng (mặc định).|
    |SIGKILL |9    |Dừng ngay lập tức (không thể chặn).|
    |SIGHUP  |1    |Khởi động lại process.             |
    |SIGSTOP |19   |Tạm dừng process.                  |
    |SIGCONT |18   |Tiếp tục process bị tạm dừng.      |
## 16. Tìm hiểu về Ram ảo hay là  SWAP trong Linux. Chúng có thực sự hữu ích ?
