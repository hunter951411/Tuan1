# Tuan1
#Các bước thực hiện:

##Tạo project mới:
###$django-admin startproject Tuan1
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/yvvd6N1.png">
##Hệ thống file khi được tạo ra
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/CkH4jNq.png">
##Vao thu muc vua tạo rồi tạo app mới:

###$python manage.py  startapp Article

###$python manage.py  startapp Category

###$python manage.py  startapp Contact

<img src="http://img.prntscr.com/img?url=http://i.imgur.com/iKe6wC6.png">
#Hệ thống file được tạo ra
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/sD4fxFz.png">
##Tiếp theo chúng ta sửa các file models.py của các app vừa được tạo ra như sau:
##Sử dụng nano để sửa file models.py của app Article như sau:
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/FWqgoJx.png">
##Sử dụng nano để sửa file models.py của app Category như sau:

<img src="http://img.prntscr.com/img?url=http://i.imgur.com/7U3tghb.png">
##Sử dụng nano để sửa file models.py của app Contact như sau:

<img src="http://img.prntscr.com/img?url=http://i.imgur.com/XFXwUCV.png">
##Sau đố ta add tên app vào file setting.py như sau:

<img src="http://img.prntscr.com/img?url=http://i.imgur.com/9uJe7rn.png">
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/tI3kEP3.png">

##Sau đó ta chạy lệnh python manage.py makemigrations
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/52licj4.png">
##Tiếp theo ta chạy lệnh python manage.py migrate
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/aMK18qU.png">
##Ta tao superuser bằng lệnh sau:
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/V2aHbeQ.png">
##Tiếp theo ta runserver như sau: 
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/zdGNDyS.png">
##Vào đường dẫn 127.0.0.1:8000 để kiểm tra:
Thông báo It's Work là thành công
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/T59sap3.png">
##Vào đường dẫn 127.0.0.1:8000/admin để đằng nhập với username vừa tạo:
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/kvdu0qy.png">
<img src="http://img.prntscr.com/img?url=http://i.imgur.com/zttIc6U.png">
