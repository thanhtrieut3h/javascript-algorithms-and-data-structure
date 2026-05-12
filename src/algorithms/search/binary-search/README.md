# Tìm kiếm nhị phân

Trong khoa học máy tính, tìm kiếm nhị phân còn gọi là tìm kiếm nữa khoảng, tìm kiếm logarit hay binary chop, là thuật toán tìm kiếm vị trí của giá trị cần tìm trong một mảng đã sắp xếp. Tìm kiếm nhị phân so sánh giá trị cần tìm với phần tử ở giữa của mảng. Nếu hai giá trị không bằng nhau, phần nửa mảng không chứa giá trị cần tìm sẽ bị bỏ qua và tiếp tục tìm kiếm trên nửa còn lại, một lần nữa lấy phần tử ở giữa và so sánh với giá trị cần tìm, cứ thế lặp lại cho đến khi tìm thấy giá trị đó. Nếu phép tìm kiếm kết thúc khi nửa còn lại trống thì giá trị cần tìm không có trong mảng.

# Giải thích
Binary Search (Tìm kiếm nhị phân) là thuật toán tìm kiếm hiệu quả trên mảng đã được sắp xếp:

Chia đôi mảng và so sánh với phần tử ở giữa

Loại bỏ một nửa mảng sau mỗi lần so sánh

Độ phức tạp O(log n) - rất nhanh với dữ liệu lớn

# Minh hoạ 

![Binary Search](https://upload.wikimedia.org/wikipedia/commons/8/83/Binary_Search_Depiction.svg)

## Độ phức tạp

**Độ phức tạp thời gian** : `O(log(n)) - vì ta chia phần tìm kiếm thành hai phần sau mỗi lần lặp.

## Liên kết
- [Wikipedia](https://en.wikipedia.org/wiki/Binary_search_algorithm)
- [YouTube](https://www.youtube.com/watch?v=P3YID7liBug&index=29&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)
