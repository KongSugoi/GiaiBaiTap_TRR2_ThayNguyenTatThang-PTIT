1. Đồ thị vô hướng G = <V,E>, trong đó:
- V (vertext) là tập hợp các đỉnh, các đối tượng, object
- E (Edge) là tập hợp các cặp không có thứ tự gồm 2 phần tử khác của V gọi là các cạnh.

2. Đồ thị có hướng G = <V,E>, trong đó:

- V (vertext) là tập hợp các đỉnh, các đối tượng, object
- E là tập các cạnh có thứ tự gồm 2 phần tử của V gọi là các cung.

3. Hai đỉnh kề nhau trong 1 đồ thị vô hướng, 1 đồ thị có hướng

- Hai đỉnh u,v được gọi là kề nhau trong 1 đồ thị vô hướng khi cạnh (u,v) thuộc đồ thị đó.

 - Hai đỉnh u,v được gọi là kề nhau trong 1 đồ thị có hướng khi cạnh (u,v) là cung của đồ thị đó.

4. Bậc của 1 đỉnh trong đồ thị vô hướng

- Ta gọi bậc của đỉnh 𝑣 trong đồ thị vô hướng là số cạnh liên thuộc với nó và ký hiệu là deg(𝑣)

5. Bán bậc của 1 đỉnh trong đồ thị có hướng


Ta gọi bán bậc ra của đỉnh 𝑣 trên đồ thị có hướng là số cung của đồ thị đi ra khỏi 𝑣 và ký hiệu là 𝑑𝑒𝑔+ (𝑣). 

      2. Ta gọi bán bậc vào của đỉnh 𝑣 trên đồ thị có hướng là số cung của đồ thị đi vào 𝑣 và ký hiệu là 𝑑𝑒𝑔− (𝑣)

6. Đường đi, chu trình trong đồ thị vô hướng; trong đồ thị có hướng
+ Đồ thị vô hướng

o Đường đi độ dài 𝑛 từ đỉnh 𝑢 đến đỉnh 𝑣 trên đồ thị vô hướng 𝐺 = < 𝑉, 𝐸 > là dãy 𝑥0 , 𝑥1 , ..., 𝑥𝑛−1, 𝑥𝑛 , trong đó: 𝑛 là số nguyên dương, 𝑥0 = 𝑢, 𝑥𝑛 = 𝑣, (𝑥𝑖 , 𝑥𝑖+1) ∈ 𝐸, 𝑖 = 0, 1, 2, ..., 𝑛 - 1. 

Đường đi như trên còn có thể biểu diễn thành dãy các cạnh (𝑥0 , 𝑥1 ), (𝑥1 , 𝑥2 ), ..., (𝑥𝑛−1, 𝑥𝑛 ). 

Đỉnh 𝑢 là đỉnh đầu, đỉnh 𝑣 là đỉnh cuối của đường đi. 

o Đường đi có đỉnh đầu trùng với đỉnh cuối hay 𝑢 = 𝑣 được gọi là chu trình. 

o Đường đi hay chu trình được gọi là đơn nếu như không có cạnh nào lặp lại

Đồ thị có hướng

Đường đi độ dài 𝑛 từ đỉnh 𝑢 đến đỉnh 𝑣 trên đồ thị có hướng 𝐺 = < 𝑉, 𝐸 > là dãy 𝑥0 , 𝑥1 , ..., 𝑥𝑛−1, 𝑥𝑛 , trong đó: 𝑛 là số nguyên dương; 𝑥0 = 𝑢, 𝑥𝑛 = 𝑣, (𝑥𝑖 , 𝑥𝑖+1) ∈ 𝐸, 𝑖 = 0, 1, 2, ..., 𝑛 − 1. 

 Đường đi như trên còn có thể biểu diễn thành dãy các cung (𝑥0 , 𝑥1 ), (𝑥1 , 𝑥2 ), ..., (𝑥𝑛−1, 𝑥𝑛 ). 

Đỉnh 𝑢 là đỉnh đầu, đỉnh 𝑣 là đỉnh cuối của đường đi. 

Đường đi có đỉnh đầu trùng với đỉnh cuối hay 𝑢 = 𝑣 được gọi là chu trình.

Đường đi hay chu trình được gọi là đơn nếu như không có cạnh nào lặp lại

7. Đồ thị vô hướng liên thông
Đồ thị vô hướng được gọi là liên thông nếu luôn tìm được đường đi giữa hai đỉnh bất kỳ của nó 

Trong trường hợp đồ thị 𝐺 = < 𝑉, 𝐸 > không liên thông, ta có thể phân rã 𝐺 thành một số đồ thị con liên thông mà chúng đôi một không có đỉnh chung.

Mỗi đồ thị con như vậy được gọi là một thành phần liên thông của đồ thị 𝐺. 

Như vậy, đồ thị liên thông khi và chỉ khi số thành phần liên thông của nó là 1 

Trong đồ thị vô hướng, nếu tồn tại đỉnh 𝑢 ∈ 𝑉 sao cho 𝑢 có đường đi đến tất cả các đỉnh còn lại của đồ thị thì đồ thị là liên thông.

8. Cạnh cầu, đỉnh trụ; cho ví dụ bằng hình vẽ đồ thị vô hướng
Cạnh 𝑒 ∈ 𝐸 được gọi là cầu nếu loại bỏ e làm tăng thành phần liên thông của đồ thị. 

Đỉnh 𝑢 ∈ 𝑉 được gọi là đỉnh trụ nếu loại bỏ 𝑢 cùng với các cạnh nối với 𝑢 làm tăng thành phần liên thông của đồ thị. 

Ví dụ: 

Các cạnh (5, 9), (5, 10), … là cầu; 

Các đỉnh 5, 6, … là trụ<br>
<image src="./img/1.png"></image>


9. Đồ thị có hướng liên thông mạnh và đồ thị có hướng liên thông yếu; cho ví dụ bằng hình vẽ đồ thị có hướng
Đồ thị có hướng 𝐺 = < 𝑉, 𝐸 > được gọi là liên thông mạnh nếu giữa hai đỉnh bất kỳ 𝑢 ∈ 𝑉, 𝑣 ∈ 𝑉 đều có đường đi từ 𝑢 đến 𝑣. 

Đồ thị có hướng 𝐺 = < 𝑉, 𝐸 > được gọi là liên thông yếu nếu đồ thị vô hướng ứng với nó là liên thông

<image src="./img/2.png"></image>