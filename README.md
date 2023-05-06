# GeoNames

Nation info: từ web service https://www.geonames.org/ định dạng trả về JSON. App hiển
thị LISTVIEW danh sách các quốc gia, mỗi item ứng với một quốc gia bao gồm hình ảnh
quốc kì, tên nước. Khi click vào item sẽ mở activity hiển thị thông tin chi tiết, gồm: hình
ảnh quốc kì, tên nước, dân số, diện tích (lưu ý format số và đơn vị đo) và hình ảnh bản đồ
của quốc gia đó. Yêu cầu có lazy load đối với hình ảnh quốc kì ở cả 2 activity.
