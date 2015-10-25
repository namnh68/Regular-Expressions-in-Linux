# Regular-Expressions-in-Linux
## Tìm hiểu về Regular Expressions trong Linux có công dụng đặc biệt như thế nào trong viết Bash shell
=========

```
cat nam.txt  | grep -v ^# | grep -v ^$
```

Đã bao giờ bạn tự hỏi cái kí tự lằng ngoằng **^#** bản chất nó là cái gì chưa ? =)) Nếu chưa hôm nay tôi sẽ giải thích cho các bạn nó là cái gì và nếu ta làm chủ được nó thì ta có thêm sức mạnh như thế nào trong khi viết Bash shell nhé. Lets Go !!!

#### 1. Khái niệm:

Cái kí tự lằng ngoằng khi tôi nó ở trên đó chính là Regular Expressions trong Linux, đây là những khái niệm nâng cao được dùng trong viết Bash shell và nó thực sự rất có ích cho người quản trị Linux, giúp cho người quản trị có thể lọc ra những thông tin cần thiết trong quá trình viết Bash shell.

Regular Expressions được chia ra làm 3 loại:
- Basic Regular Expressions 
- Interval Regular Expressions
- Extended Regular Expressions

Những loại câu lệnh nào có thể sử dụng được Regular Expressions này bao gồm: grep, sed, awk, perl, python ( trong khuôn khổ bài viết này tôi sẽ sử dụng nó với grep )

Bây giờ chúng ta sẽ đi vào từng loại Regular Expressions

##### 1.1 Basic Regular Expressions

Bao gồm các kí tự **^, $, *, ., [], [^char], <word>** 


