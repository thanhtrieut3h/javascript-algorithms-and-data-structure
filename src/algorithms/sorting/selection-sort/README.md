# Sắp xếp chọn

Sắp xếp chọn (Selection Sort) là một thuật toán sắp xếp đơn giản, hoạt động dựa trên nguyên tắc: liên tục chọn phần tử nhỏ nhất (hoặc lớn nhất) từ phần chưa được sắp xếp và đưa nó về vị trí đúng.

# Giải thích

Sắp xếp chọn là một thuật toán sắp xếp, cụ thể là sắp xếp so sánh tại chỗ. Nó có độ phức tạp thời gian là O (n2), khiến nó không hiệu quả với các danh sách lớn và thường hoạt động kém hơn so với các thuật toán sắp xếp tương tự. 

Sắp xếp chọn được quan tâm vì tính đơn giản của nó và lợi thế về hiệu suất so với các thuật toán phức tạp hơn trong một số tình huống nhất định, đặc biệt khi bộ nhớ phụ bị hạn chế.

# Minh hoạ 

Mảng ban đầu: [64, 25, 12, 22, 11]

Bước 1 (i=0): Tìm min trong [64,25,12,22,11] -> min=11
  Hoán đổi 64 và 11 -> [11, 25, 12, 22, 64]

Bước 2 (i=1): Tìm min trong [25,12,22,64] -> min=12
  Hoán đổi 25 và 12 -> [11, 12, 25, 22, 64]

Bước 3 (i=2): Tìm min trong [25,22,64] -> min=22
  Hoán đổi 25 và 22 -> [11, 12, 22, 25, 64]

Bước 4 (i=3): Tìm min trong [25,64] -> min=25
  Hoán đổi 25 và 25 (không đổi) -> [11, 12, 22, 25, 64]

Kết quả: [11, 12, 22, 25, 64]

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/b/b0/Selection_sort_animation.gif)

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/9/94/Selection-Sort-Animation.gif)

## Độ phức tạp

| Name                  | Best            | Average             | Worst               | Memory    | Stable    | Comments  |
| --------------------- | :-------------: | :-----------------: | :-----------------: | :-------: | :-------: | :-------- |
| **Selection sort**    | n<sup>2</sup>   | n<sup>2</sup>       | n<sup>2</sup>       | 1         | No        |  
|

## So sánh Bubble Sort vs Selection Sort

| Đặc điểm	      | Bubble Sort	            | Selection Sort
|
|-----------------| :---------------------: | :--------------------------------:
| Nguyên lý       |	Đổi chỗ các cặp liền kề	| Chọn phần tử nhỏ nhất đưa về đầu
|-----------------| :---------------------: | :--------------------------------:
| Số lần so sánh  | Luôn là O(n²)	          | Luôn là O(n²)
|-----------------| :---------------------: | :--------------------------------:
| Số lần hoán đổi |	Nhiều (O(n²))	          | Ít (O(n))

## Liên kết

[Wikipedia](https://en.wikipedia.org/wiki/Selection_sort)
