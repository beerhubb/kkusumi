---?image=audience.png
# @color[orange](**Markdown**)

---?image=audience.png
@snap[north]

## @color[orange](Markdown)

@snapend

@snap[text-silver]
Markdown คือ ภาษาคอมพิวเตอร์ ที่มนุษย์สามารถอ่านเข้าใจได้ง่าย
และด้วยความง่ายนี้มันก็สามารถแปลงกลับมาเป็นภาษาอื่นๆได้ง่ายด้วยกันเช่น HTML, XHTML และด้วยความง่ายเช่นนี้จึงมีเจ้าอื่นนำไป Customizeให้เป็นของตัวเองเช่น github ก็อาจจะเพิ่มพวก feature เข้าไปเช่น task list, mention และอื่นๆ
@snapend

---?image=audience.png

## @color[orange](เริ่มเขียน Markdown)

---?image=audience.png

@snap[north-west span-50 text-center]
### @color[orange](**การเขียนหัวเรื่อง**)  

```php
        ## (หัวเรื่อง 2)

        ### (หัวเรื่อง 3)

        #### (หัวเรื่อง 4)

        ##### (หัวเรื่อง 5)

        ###### (หัวเรื่อง 6)


```

@snapend

@snap[north-east span-50 text-08]

## @color[orange](**ผลลัพธ์**)

## @color[silver](หัวเรื่อง 2)

### @color[silver](หัวเรื่อง 3)

#### @color[silver](หัวเรื่อง 4)

##### @color[silver](หัวเรื่อง 5)

###### @color[silver](หัวเรื่อง 6)

@snapend

---?image=audience.png

@snap[north-west span-50 text-center]
### @color[orange](**รูปแบบตัวอักษร**)

```php
        ตัวเอียง     _สวัสดี_

        ตัวหนา     **สวัสดี**

        ขีดฆ่า       ~~ สวัสดี ~~

```

@snapend

@snap[north-east span-50 text-center text-08]

## @color[orange](**ผลลัพธ์**)

**@color[silver](สวัสดี)**  
_@color[silver](สวัสดี)_  
~~@color[silver](สวัสดี)~~  

@snapend

---?image=audience.png

@snap[north-west span-50 text-center]
### @color[orange](**แบบเรียงลำดับ**)

```php
       1. สวัสดี  


       1. สวัสดี  


       1. สวัสดี  


       1. สวัสดี  

```

@snapend

@snap[north-east span-50 text-center text-08]
## @color[orange](**ผลลัพธ์**)

1. สวัสดี  
#### 
2. สวัสดี  
#### 
3. สวัสดี  
#### 
4. สวัสดี  
@snapend

---?image=audience.png)

@snap[north-west span-50 text-center]

### @color[orange](**แบบไม่เรียงลำดับ**)  

```php
       - สวัสดี  


       * สวัสดี  


       + สวัสดี  


       * สวัสดี  

```
@snapend

@snap[north-east span-50 text-center text-08]

## @color[orange](ผลลัพธ์)  

- สวัสดี  
#### 
* สวัสดี  
#### 
+ สวัสดี  
#### 
* สวัสดี  
  
@snapend

---?image=audience.png

## @color[orange](ใส่รูปภาพใน Markdown)

#### @color[orange](Syntax)

            ![Google](https://sv1.picz.in.th/images/2019/12/05/iZyaHz.jpg)

**@color[orange](ผลลัพธ์)**

### ![Google ](https://www.google.co.th/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

---?image=audience.png

## @color[orange](ใส่ Video ใน Markdown)

#### @color[orange](Syntax)

            ![Video](https://youtu.be/KmW0iSGlCgQ)
**@color[orange](ผลลัพธ์)**

<iframe width="360" height="240" src="https://www.youtube.com/embed/KmW0iSGlCgQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---?image=audience.png 

## @color[orange](ใส่ link ใน Markdown)
#### @color[orange](Syntax)

    [Leanpub](https://leanpub.com/courses/leanpub/markdown1/read/1?published=true)

**@color[orange](ผลลัพธ์)**

@box[bg-gold]([@size[2em](@color[black](Leanpub))](https://leanpub.com/courses/leanpub/markdown1/read/1?published=true))