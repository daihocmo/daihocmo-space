# 4. Sử dụng

## 4.1 - Tiêu đề

```markdown
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

Output:

# h1

## h2

### h3

#### h4

##### h5

###### h6

## 4.2 - Đoạn văn

Sử dụng 1 dòng trống để phân tách 1 or nhiều dòng text. Chú ý là ko được thụt về bằng space or tab nếu ko thì text đó chuyển thành Code block trong markdown. Ví dụ:

```markdown
Chào em

Em ăn khoai ko
```

Output:  
Chào em

Em ăn khoai ko

## 4.3 - Ngắt dòng

Để ngắt dòng thì ta sử dụng 2 or nhiều dấu cách ở cuối dòng mà bạn muốn cách. VD:

```markdown
Em như ánh mặt trời.   
Nhìn em anh đã muốn...
```

Output:  
Em như ánh mặt trời.  
Nhìn em anh đã muốn...

## 4.4 - Nhấn mạnh từ

### In đậm

Có 2 cách:

```markdown
Ai hay **Ảo tưởng**    
Thì bớt __Ảo Tưởng__ đi.
```

Output:  
Ai hay **Ảo tưởng**  
Thì bớt **Ảo Tưởng** đi.

### In nghiêng

Cách viết thì giống in nghiêng nhưng chỉ có 1 dấu sao và 1 gạch ngang ở trước và sau của từ.

### Đậm và nghiêng

Có 4 cách nhưng mình chỉ giới thiệu 2 cách mà mọi người hay dùng nhất:

```markdown
Chủ tịch ***Cuong***   
Vợ chủ tịch ___Ko biết___
```

Output:  
Chủ tịch _**Cuong**_  
Vợ chủ tịch _**Ko biết**_

## 4.5 - Blockquotes

Thêm > trước 1 đoạn văn.

```markdown
> Mùa đông lạnh thụt ...
```

Output:

> Mùa đông lạnh thụt ...

## 4.6 - Danh sách

Thụt 1 or nhiều item trong item cha để có 1 list lồng nhau.

### Có thứ tự

Các item trong list phải bắt đầu là 1 số + dấu chấm + dấu cách + tên item. **Chú ý**: số ở đây ko phải là số thứ tự của item ( tức là 1 số bất kì >= 0): VD :

```markdown
1. Sản phẩm
2. Liên hệ

6. Cháo lòng
5. Tiết cách
```

Output:

1. Sản phẩm
    
2. Liên hệ
    
3. Cháo lòng
    
4. Tiết canh
    

### Ko thứ tự

Các item bắt đầu bằng : 1 dấu * or + or - + dấu cách + tên item

```markdown
* Mùa xuân
- Mùa hạ
+ Mùa thu
* Mùa đông
```

Output:

- Mùa xuân

- Mùa hạ

- Mùa thu

- Mùa đông

### Thêm elements

Để thêm các thành phần khác vào trong 1 list mà vẫn duy trì được tính liên tục của list thì thành phần đó phải đc thụt lề bằng 4 dấu cách or 1 tab.

```markdown
* Xuân đã đến 
    bên em
 * Dáng xuân tuyệt vời
```

Output:

- Xuân đã đến  
    bên em
- Dáng xuân tuyệt vời

## 4.7 - Code block

Để định nghĩa, xác định 1 khối code thì ta thụt dòng bằng tab or 4 dấu cách. Đây là cách ko nên dùng vì nó hay gây nhầm lẫn.

```markdown
    Tết tết tết đến rồi
    Tao tao tao trắng túi rồi
```

Output:  
Do trên viblo ko hỗ trợ code block bằng thụt lề thì các bạn thử ở [đây](https://stackedit.io/app#)

## 4.8 - Thước ngang

Có 3 cách để thước ngang: 3 dấu *** or - - - or ___

```markdown
***
- - -
___
```

Output:

---

## 4.9 - Links

Xem ví dụ cho rễ hình dung:

```markdown
Muốn hiểu sâu, nhớ sâu, sau này quên thì hãy viết 1 blog trên [Viblo](https://viblo.asia)
```

Output:  
Muốn hiểu sâu, nhớ sâu, sau này quên thì hãy viết 1 blog trên [Viblo](https://viblo.asia)

### Thêm titles

Nó xuất hiện 1 cái tooltip khi bạn hover vào link.

```markdown
Hãy viết bài trên [Viblo](https://viblo.asia "Viblo việt nam")
```

Output:  
Hãy viết bài trên [Viblo](https://viblo.asia "Viblo việt nam")

### urls & email address

Để nhanh chóng chuyển 1 url or email thành 1 link thì đặt chúng trong <> (cách viết ngắn gọn hơn trên nhưng ko đc thẩm mỹ và dài ![😊](https://twemoji.maxcdn.com/v/14.0.2/72x72/1f60a.png)![😊](https://twemoji.maxcdn.com/v/14.0.2/72x72/1f60a.png))

```markdown
<https://www.markdownguide.org>
<fake@example.com>
```

Output:  
[https://www.markdownguide.org](https://www.markdownguide.org)  
[fake@example.com](mailto:fake@example.com)

### Format links

Tức là làm cho links in đậm hay nghiêng.

```markdown
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
```

Output:  
I love supporting the **[EFF](https://eff.org)**.  
This is the _[Markdown Guide](https://www.markdownguide.org)_.

### Links kiểu tham chiếu

Hiểu đơn giản là làm cho link mà mình viết trong markdown nó đẹp hơn, gọn gơn thay vì bạn hay để cả url vào trong 1 đoạn text như này:

```markdown
Ngày xửa ngày xưa có 1 anh tên [mạng xã hội lotus](https://lotus.vn/w/) vừa mới ra mắt đã bị chê lên chê xuống vì người việt ko ủng hộ hàng việt....
```

Thì giờ ta có kiểu khác:

```markdown
(a) = Ngày xửa ngày xưa có 1 anh tên [mạng xã hội lotus][1] vừa mới ra mắt đã bị chê lên chê xuống vì người việt ko ủng hộ hàng việt....

(b) = [1]: <https://lotus.vn/w/> = (or)
[1]: <https://lotus.vn/w/> "Mạng xã hội lotus việt nam" = (or)
[1]: https://lotus.vn/w/ = (or)
[1]: https://lotus.vn/w/  "Mạng xã hội lotus việt nam" 
```

Output: Ngày xửa ngày xưa có 1 anh tên [mạng xã hội lotus](https://lotus.vn/w/ "Mạng xã hội lotus việt nam") vừa mới ra mắt đã bị chê lên chê xuống vì người việt ko ủng hộ hàng việt....

Chú ý: (b) trong đoạn code trên thì bạn có thể đặt ở bất kì đâu trong tài liệu mà bạn đang viết, nếu (b) được đặt ngay sau (a) thì (b) phải cách (a) 1 dòng trống, [1] trong (a) và (b) phải giống nhau và số 1 trong [1] là duy nhất ( chỉ có [1] xuất hiện 1 lần ) nếu tồn tại 2 [1] thì link nó chọn [1] đầu tiên, nếu cái [1] đầu tiên lỗi thì nó chọn cái thứ 2. Các bạn chạy thử để xem nó như nào nhé tại [đây](https://stackedit.io/app#)

## 4.10 - Images

Cú pháp:

```markdown
![giá trị alt](Đường dẫn tuyệt đối (absolute-path tên khác là 1 cái url đầy đủ) or đường dẫn tương đối (relative-path : home/views...) "titile - có hoặc ko có title cũng đc")
```

Cụ thể nha các bạn:

```markdown
![Xinh thế em ơi!](https://znews-photo.zadn.vn/w660/Uploaded/....68232_n_1.jpg "Xinh thật sự <3")
```

Output:  
![Xinh thế em ơi!](https://znews-photo.zadn.vn/w660/Uploaded/cqdhmdxwp/2019_10_18/22196045_1812118665468264_7078060295852768232_n_1.jpg "Xinh thật sự <3")

### Linking Images

Cú pháp ảnh ở trên thì ta cho vào ngoặc vuông [] + (trong này là url đến 1 page nào đấy), ví dụ nuôn cho nó rễ hiểu.

```markdown
[![Xinh như tó thế em ơi!](https://znews-photo.zadn.vn/w660/Uploaded/...)](https://news.zing.vn/dan-trai-xinh-gai-dep-chiem-spotlight-nho-loat-anh-mac-dong-phuc-post1003190.html)
```

Output:  
[![Xinh như tó thế em ơi!](https://i.pinimg.com/originals/47/4a/32/474a32757e5d8a3df1858fbcb67a8164.jpg "Xinh hết phần người khác")](https://news.zing.vn/dan-trai-xinh-gai-dep-chiem-spotlight-nho-loat-anh-mac-dong-phuc-post1003190.html)

## 4.11 - Escaping characters

Escaping characters tức là giải thoát cho [các ký tự dùng để định dạng trong markdown](https://www.markdownguide.org/basic-syntax/#characters-you-can-escape). Ví dụ, khi bạn muốn hiển thị như lày: *Ngọc Trinh* thì trong markdown bạn viết như vậy là nó in nghiêng cái từ _Ngoặc Trinh_, để hiện thị như bạn muốn thì thêm ký tự: \ vào trước cái mà bạn muốn hiển thị.

```markdown
\*Bưởi to lắm Trinh ê*
```

Output:  
*Bưởi to lắm Trinh ê*![😜](https://twemoji.maxcdn.com/v/14.0.2/72x72/1f61c.png)![😜](https://twemoji.maxcdn.com/v/14.0.2/72x72/1f61c.png)

## 4.12 - Tables

Để tạo bảng ta sử dụng 3 or nhiều dấu gạch ngang (---) và sử dụng pipes (|) để tách các cột.

```markdown
|Họ và tên | Giới tính|
|---|----------------|
|Andrea | Nam|
|Marin  | Nữ |
```

Output:

|Họ và tên|Giới tính|
|---|---|
|Sùng a bái|Nam|
|Lò a hính|Nữ|

### Căn chỉnh

Để căn chỉnh text trong cột sang trái, phải or giữa thì thêm dấu 2 chấm ":" vào trước or sau or cả trước và sau.

```markdown
|Họ và tên | Giới tính|
|:---:|:----------------:|
|Andrea | Nam|
|Marin  | Nữ |
```

Output:

|Họ và tên | Giới tính|
|:---:|:----------------:|
|Andrea | Nam|
|Marin  | Nữ |
### Format text

Định dạng text bên trong bảng. Ví dụ, Bạn có thể thêm [links](https://www.markdownguide.org/basic-syntax/#links), [code](https://www.markdownguide.org/basic-syntax/#code) (chỉ có từ hoặc cụm từ trong (``) và ko có [code blocks](https://www.markdownguide.org/basic-syntax/#code-blocks)), và [emphasis](https://www.markdownguide.org/basic-syntax/#emphasis) (nhấn mạnh) : in đậm, in nghiêng...

Ko được thêm headings, blockquotes, lists, horizontal rules, images, and HTML tags.

### Escaping pipe characters

Bạn có thể sử dụng (|) trong bảng bằng cách dùng mã kí tự HTML của nó là: `&#124;`

## 4.13 - Fenced code blocks

Ta có cách để tạo 1 code blocks trong markdown là dùng 4 dấu cách or tab nhưng cách này nó ko tiện lợi, rễ gây nhầm lẫn . Thay vào đó ta sử dụng hàng rào (fence) để tạo code blocks thay vì thụt lề như trước. Phụ thuộc vào Markdown processor or editor của bạn mà chọn fence phù hợp. Sử dụng 3 (```) or 3 (~~~) ở trước và sau 1 code block.

```json
{
"firstname":"cuong",
"lastname":"Nguyen",
"age":20
}
```

Output:  
Xem chi tiết tại [đây!](https://www.markdownguide.org/extended-syntax/#fenced-code-blocks)

### Systax highlight

Nhiều Markdown processor trợ giúp systax highlighting cho đoạn code đc rào chắn ( fenced code blocks). Tức là thêm các màu nổi bật cho các đoạn mã đc viết bằng của các ngôn ngữ khác nhau. Chỉ định ngôn ngữ mà bạn viết trong code block vào sau 3 ``` ở phía trước đoạn code. Tham khảo tại [đây!](https://www.markdownguide.org/extended-syntax/#syntax-highlighting)

## 4.14 - Heading IDs

- Nhiều Markdown processor trợ giúp ID tùy chỉnh cho tiêu đề (heading) - 1 vài processor thì tự động thêm ID cho heading. Thêm ID này thì ta có link trực triếp đến tiêu đề mà ta đặt ID này và ID này thì ta cũng chỉnh sửa được chúng với CSS.
- Cú pháp : #(##,###...) + tên heading + {# + ten-ID}
- Xem VD ở [Heading IDs](https://www.markdownguide.org/extended-syntax/#heading-ids)

### Linking to Heading IDs

Bạn click vào link là nó nhảy đến heading mà có ID trùng với ID trong link của bạn.  
Xem chi tiết ở [Linking to Heading IDs](https://www.markdownguide.org/extended-syntax/#linking-to-heading-ids) khi bạn click vào Heading IDs trong bảng là nó nhảy lên tiêu đề Heading IDs.

## 4.15 - Strikethrough

Sử dụng (~~) trước và sau 1 từ or cụm từ.

```markdown
I am a ~~lazy~~ student.
```

Output:  
I am a ~~lazy~~ student.

