# ImageCoverter

## ChagtGPT指令

### 1  创建路由

Code for Python, Flask server.
Add route “/” with GET method and return index.html
Add route “/jpgtopng” with GET method and return jpgtopng.html
Add route “/pngtojpg” with GET method and return pngtojpg.html
Add route “/webptopng” with GET method and return webptopng.html
Add route “/bmptopng” with GET method and return bmptopng.html
Add route “/pngtopdf” with GET method and return pngtopdf.html



### 2  编写index.html

Code for index.html file. Create a div and add these 5 links as list in it with href= appropiate route from our flask server.
JPG to PNG converter
PNG to JPG converter
WEBP to PNG converter
BMP to PNG converter
PNG to PDF converter


### 3  编写转换页面

Code for jpgtopng.html file.
Display input form, so user can select image from their computer.
Also add a “Convert to PNG” button.
onclick button, check if image is selected and image is jpg format and less than 5 MB
If true then send POST request to route “/api/jpgtopng” with image as parameter.
else show relevant error like select a image or image is not jpeg format

Code for pngtojpg.html file.
Display input form, so user can select image from their computer.
Also add a “Convert to JPG” button.
onclick button, check if image is selected and image is png format and less than 5 MB
If true then send POST request to route “/api/pngtojpg” with image as parameter.
else show relevant error like select a image or image is not png format

Code for webptopng.html file.
Display input form, so user can select image from their computer.
Also add a “Convert to PNG” button.
onclick button, check if image is selected and image is webp format and less than 5 MB
If true then send POST request to route “/api/webptopng” with image as parameter.
else show relevant error like select a image or image is not webp format

Code for bmptopng.html file.
Display input form, so user can select image from their computer.
Also add a “Convert to PNG” button.
onclick button, check if image is selected and image is bmp format and less than 5 MB
If true then send POST request to route “/api/bmptopng” with image as parameter.
else show relevant error like select a image or image is not bmp format

Code for pngtopdf.html file.
Display input form, so user can select image from their computer.
Also add a “Convert to PDF” button.
onclick button, check if image is selected and image is png format and less than 5 MB
If true then send POST request to route “/api/pngtopdf” with image as parameter.
else show relevant error like select a image or image is not png format



### 4  编写服务端代码

For flask server, create a route “/api/jpgtopng” with POST method.
convert jpg image from parameter into png format, don’t save the image on server. just return png image as downloadable  attachment.
For flask server, create a route “/api/pngtojpg” with POST method.
convert png image from parameter into jpg format, don’t save the image on server. just return jpg image as downloadable  attachment.
For flask server, create a route “/api/webptopng” with POST method.
convert webp image from parameter into png format, don’t save the image on server. just return png image as downloadable  attachment.
For flask server, create a route “/api/bmptopng” with POST method.
convert bmp image from parameter into png format, don’t save the image on server. just return png image as downloadable  attachment.
For flask server, create a route “/api/pngtopdf” with POST method.
convert png image from parameter into pdf format, don’t save the pdf on server. just return pdf file as downloadable  attachment.



### 5 添加css

css code for pngtopdf.html file. Display form input in middle and add some background color.
Add styles to the form element or the input element to change the appearance of the form. And css for convert button.
