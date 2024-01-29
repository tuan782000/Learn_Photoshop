# 26 Giới thiệu Blending Mode

## Blending Mode là cái gì?

Có 2 bức ảnh:

Lấy ảnh 2 copy bỏ qua ảnh 1

Sử dụng Blending mode để hòa trộn 2 background lại với nhau. Tạo ra 1 hiệu ứng mới


Tóm lại công dụng của Blending Mode giúp chúng ta hòa trộn 2 background lại với nhau. Tạo ra 1 hiệu ứng mới


Cách hoạt động của Blending mode

Ảnh 1 được hiểu Layer gốc

Ảnh 2 được hiểu là Layer blend

Ảnh 1 và 2 hòa trộn tạo ra 1 ảnh mới có hiệu ứng đẹp hơn

Blending mode giúp hòa trộn những layer lại với nhau để tạo ra những hiệu ứng, màu sắc đặc biệt.


Layer blend: nó có thể là các hiệu ứng tuyết, khói, ma thuật, sét,... nó là cái layer hiệu ứng và luôn luôn nằm ở trên.

Layer Gốc: là hình chính thức, luôn luôn nằm dưới cái layer blend.


## Blending Mode nó nằm ở đâu?

Nó nằm ở bảng Layer

Chưa có nhấn "F7"

Hiện tại Blending Mode có tổng cộng 27 cái.

Chỉ nên sử dụng những cái tiêu biểu, còn những cái còn lại tùy thuộc từng trường hợp thì tra để sử dụng

Có 6 Loại Blending Mode:

Normal: 
- Normal
- Dissolve

Darken:
- Darken
- Multiply 📚
- Color Bum
- Linear Bum
- Darker Color

Lighten:
- Lighten
- Screen 📚
- Color Dodge
- Linear Dodge (Add)
- Lighter Color

Constrast:
- overlay 📚
- soft light 📚
- hard light
- vivid light
- linear light
- pin light
- hard mix

Inversion:
- Difference
- Exclusion
- Subtract
- Divide

Component:
- Hue
- Saturation
- Color
- Luminosity


### Tìm hiểu về Normal:

Có dãi màu từ đen sang trắng, và chú ý thuật ngữ brightness (b)

nhấn phím "I" chuyển thanh công cụ chọn màu

brightness: độ sáng

để màu đen là 0

để màu trắng là 100

để ở giữa dải màu đen và trắng là xám: 50

Nhóm normal này hoàn toàn không có tác dụng gì nhiều. Trừ khi bạn giảm opacity của nó xuống

Đối với Normal thì mờ đi Layer blend và dần để lộ Layer gốc

Đối với Dissolve thì mờ đi nhưng nó kèm theo hiệu ứng phân rã ra.

### Tìm hiểu về nhóm Darken: 

Nhóm này làm cho hình chúng ta tối hơn. Đồng thời làm các màu trắng trở nên trong suốt.

Multiply: Màu trắng hoàn toàn b: 100% biến mất về để lộ diện ảnh gốc, giữ lại các màu đen có b là 0% 

Đối với các màu đen có độ b tăng dần lên 100 thì vùng càng ngày càng tối đi 

Các cái khác trong Darken cũng tương tự. Nhưng Multiply sử dụng nhiều nhất

### Tìm hiểu về nhóm Lighten:

Nhóm này hoàn toàn trái ngược với Darken. Làm cho hình sáng hơn. Đồng thời làm các màu tối trở nên trong suốt.

Screen: Màu đen thuần xóa đi hết, giữ lại màu trắng 100%, từ máu xám dần lên trắng sẽ làm sáng tư từ lên cho đến khi nào chạm tới ngưỡng màu trắng.


### Tìm hiểu về constrast:

constrast: tương phản

overlay: làm 3 điều màu xám 50% làm cho trong suốt, màu đen và trắng thì sẽ bị đẩy cái độ tương phản của nó lên. đen sẽ làm tối đi, trắng thì làm bị cháy sáng

Soft Light: Phiên bản nhẹ hơn của overlay, đen làm tối hơn xíu xíu trắng cũng đẩy tương phản lên xíu xíu. Xóa đị màu xám 50%













