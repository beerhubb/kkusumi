---
## @color[orange](**Markdown** คืออะไร?)
---@snap[north span-90 text-center]

### @color[orange](ทำไมต้องใช้ **Markdown**?)

@snapend

@snap[west span-40 text-center]
@ul[list-square-bullets striped-list-items](false)

# Hello

## Hi

- Apple
- Banana
- Orange

@snapend

@snap[east span-40 text-center]

### @color[orange](HTML)

@ul[list-square-bullets striped-list-items](false)

```html
<h1>Hello</h1>
<h2>Hi</h2>
<ul>
  <li>Apple</li>
  <li>Banana</li>
  <li>Orange</li>
</ul>
```

@snapend

+++

@snap[north span-90 text-center]

### @color[orange](ทำไมต้องใช้ **Markdown**?)

@snapend

@snap[east span-40 text-center]

### @color[orange](Markdown)

@ul[list-square-bullets striped-list-items](false)

```md
# Hello

## Hi

- Apple
- Banana
- Orange
```

@snapend

@snap[west span-40 text-center]
@ul[list-square-bullets striped-list-items](false)

# Hello

## Hi

- Apple
- Banana
- Orange

@snapend

---

@snap[north-west span-45 text-center]

### @color[orange](**การเขียน<br>หัวเรื่อง**)

@snapend

@snap[west span-55 text-center]
@ul[list-square-bullets striped-list-items](false)

```md
        # หัวเรื่อง 1

        ## หัวเรื่อง 2

        ### หัวเรื่อง 3

        #### หัวเรื่อง 4

        ##### หัวเรื่อง 5

        ###### หัวเรื่อง 6
```

@ulend
@snapend

@snap[east span-55 text-right]
@ul[list-square-bullets striped-list-items](false)

# @color[silver](หัวเรื่อง 1)

## @color[silver](หัวเรื่อง 2)

### @color[silver](หัวเรื่อง 3)

#### @color[silver](หัวเรื่อง 4)

##### @color[silver](หัวเรื่อง 5)

###### @color[silver](หัวเรื่อง 6)

@ulend
@snapend

---

@snap[north-west span-50 text-left]

### @color[orange](**รูปแบบตัวอักษร**)

@snapend

@snap[north-east span-50 text-center text-08]

## @color[orange](** ผลลัพธ์**)

@snapend

@snap[west span-30 text-center fragment]
@box[bg-black](`_ตัวเอียง_`)
@box[bg-black](`**ตัวหนา**`)
@snapend

@snap[east span-30 text-10 fragment]
@box[bg-black](_ตัวเอียง_)
@box[bg-black](**ตัวหนา**)
@snapend

---

### @color[orange](**การใช้ลิสด์มี 2 แบบ**)

---

@snap[north-west span-50 text-center]

### @color[orange](**แบบเรียงลำดับ**)

```md
       1. แมว
       1. หมา
       1. หมู
       1. ไก่
```

@snapend

@snap[south-west span-50 text-center]

```md
       1. จันทร์
       2. อังคาร
       3. พุธ
       4. พฤหัสบดี
```

@snapend

@snap[north-east span-50 text-center text-08]

## @color[orange](**ผลลัพธ์**)

1. แมว

####

2. หมา

####

3. หมู

####

4. ไก่  
   @snapend
   @snap[south-east span-50 text-center text-08]

1) จันทร์

####

2. อังคาร

####

3. พุธ

####

4. พฤหัสบดี  
   @snapend

---

@snap[north-west span-50 text-center]

### @color[orange](**แบบไม่เรียงลำดับ**)

```md
       - หนึ่ง
       - สอง
       - สาม
```

```md
       * สี่
       * ห้า
       * หก
```

```md
       + เจ็ด
       + แปด
       + เก้า
```

@snapend

@snap[north-east span-50 text-center text-08]

## @color[orange](ผลลัพธ์)

● หนึ่ง  
● สอง  
● สาม

####

● สี่  
● ห้า  
● หก

####

● เจ็ด  
● แปด  
● เก้า

####

@snapend

---

## @color[orange](ใส่รูปใน Markdown)

        ![imgae](https://www.google.co.th/images/branding/googlelogo_272x92dp.png)

**@color[orange](ผลลัพธ์)**

![Google](https://www.google.co.th/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

---

## @color[orange](ใส่ Video ใน Markdown)

        ![Video](https://www.youtube.com/embed/KmW0iSGlCgQ)

<iframe width="360" height="240" src="https://www.youtube.com/embed/KmW0iSGlCgQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## @color[orange](ใส่ link ใน Markdown)

                        [Google](https://www.google.com)

**@color[orange](ผลลัพธ์)**

[**Google**](https://www.google.com/)
