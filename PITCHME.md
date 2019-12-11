---?color=linear-gradient(to top left, #bdc3c7, #2c3e50)
# @color[orange](Markdown)

---?color=linear-gradient(180deg, #003366 25%, white 25%)
@snap[north]

## @color[orange](Markdown)

@snapend

@color[black](Markdown คือ ภาษาคอมพิวเตอร์ ที่มนุษย์สามารถอ่านเข้าใจได้ง่าย)
@color[black](และด้วยความง่ายนี้มันก็สามารถแปลงกลับมาเป็นภาษาอื่นๆได้ง่ายด้วยกันเช่น HTML, XHTML และด้วยความง่ายเช่นนี้จึงมีเจ้าอื่นนำไป Customize)@color[black](ให้เป็นของตัวเองเช่น github ก็อาจจะเพิ่มพวก feature เข้าไปเช่น task list, mention และอื่นๆ)

---?color=linear-gradient(to top left, #bdc3c7, #2c3e50)

## @color[orange](เริ่มเขียน Markdown)

---?color=linear-gradient(80deg, #003366 50%, #E8E8E8 50%)

@snap[north-west span-40 text-center]
### @color[white](การเขียนหัวเรื่องในขนาดต่างๆ)
#### @color[white](Syntax)

```php
        # (หัวเรื่อง 1)

        ## (หัวเรื่อง 2)

        ### (หัวเรื่อง 3)

        #### (หัวเรื่อง 4)

        ##### (หัวเรื่อง 5)

        ###### (หัวเรื่อง 6)
```

@snapend

@snap[north-east span-60 text-08]

## @color[black](**ผลลัพธ์**)

# @color[black](หัวเรื่อง 1)

## @color[black](หัวเรื่อง 2)

### @color[black](หัวเรื่อง 3)

#### @color[black](หัวเรื่อง 4)

##### @color[black](หัวเรื่อง 5)

###### @color[black](หัวเรื่อง 6)

@snapend

---?color=linear-gradient(90deg, white 50%, black 50%)

@snap[north-west span-50 text-center]
### @color[black](**รูปแบบอักษรประกอบไปด้วย**)
#### @color[black](Syntax)

```php
        ตัวเอียง     _ตัวเอียง_

        ตัวหนา     **ตัวหนา**

        ขีดฆ่า       ~~ ขีดฆ่า ~~

```

@snapend

@snap[north-east span-50]

### ผลลัพธ์

@snapend

@snap[east span-30 text-08]

@box[bg-white](**@color[black](สวัสดี)**)
@box[bg-white](_@color[black](สวัสดี)_)
@box[bg-white](~~@color[black](สวัสดี)~~)

@snapend

---?color=linear-gradient(to top left, #bdc3c7, #2c3e50)

@snap[north span-50]

### @color[orange](**ลิสต์ list**)

@snapend

@snap[midpoint span-50]

#### มีทังหมด 2 แบบประกอบด้วย

#### 1.ลิสต์แบบเรียงลำดับ (Ordered List)

#### 2.ลิสต์แบบไม่เรียงลำดับ (Unordered List)

@snapend

---?color=linear-gradient(90deg, white 50%, black 50%)

@snap[north-west span-50 text-center]
### @color[black](**ลิสต์แบบเรียงลำดับ**)
#### @color[black](Syntax)

```php
       1. สวัสดี

       1. ฉัน

       1. ชื่อ

       1. อะไร
```

@snapend

@snap[north-east snap-50]

### **ผลลัพธ์**

@snapend

@snap[east snap-50]

1. สวัสดี
#### 
2. ฉัน
#### 
3. ชื่อ
#### 
4. อะไร
@snapend

---?color=linear-gradient(90deg, white 50%, black 50%)

@snap[north-west span-50 text-center]

### @color[black](**ลิสต์แบบไม่เรียงลำดับ**)

@snapend

@snap[west- span-50]

#### @color[black](Syntax)

```php
       - สวัสดี

       * สวัสดี

       + สวัสดี

       * สวัสดี
```

@snapend

@snap[north-east span-100]

### ผลลัพธ์

@snapend

@snap[east span-50]

- สวัสดี  

* สวัสดี  

+ สวัสดี  

* สวัสดี  

@snapend

---?color=linear-gradient(180deg, #2c3e50 52%, white 52%)

## @color[orange](ใส่รูปภาพใน Markdown)

#### @color[orange](Syntax)

            ![Google](https://sv1.picz.in.th/images/2019/12/05/iZyaHz.jpg)

**@color[orange](ผลลัพธ์)**

### ![Google ](https://www.google.co.th/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

---?color=linear-gradient(180deg, #2c3e50 52%, white 52%)

## @color[orange](ใส่ Video ใน Markdown)

#### @color[orange](Syntax)

            ![Video](https://youtu.be/KmW0iSGlCgQ)
**@color[orange](ผลลัพธ์)**

<iframe width="360" height="240" src="https://www.youtube.com/embed/KmW0iSGlCgQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---?color=linear-gradient(180deg, #2c3e50 59%, white 59%)

## @color[orange](ใส่ link ใน Markdown)
#### @color[orange](Syntax)

    [Leanpub](https://leanpub.com/courses/leanpub/markdown1/read/1?published=true)

**@color[orange](ผลลัพธ์)**

@box[bg-gold]([@size[2em](@color[black](Leanpub))](https://leanpub.com/courses/leanpub/markdown1/read/1?published=true))