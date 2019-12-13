---?image=audience.png
## @color[orange](**Markdown** คืออะไร?)

---?image=audience.png
@snap[north span-90 text-center]
### @color[orange](ทำไมต้องใช้ **Markdown**?)

@snapend

@snap[west span-40 text-center]
@ul[list-square-bullets striped-list-items](false)

# Hello
## Hi
 * Apple
 * Banana
 * Orange

@snapend

@snap[east span-40 text-center]
@ul[list-square-bullets striped-list-items](false) 
```html
        HTML

<h1> Hello </h1>
 <h2> Hi </h2>
 <ul>
   <li>Apple</li>
   <li>Banana</li>
   <li>Orange</li>
 </ul>  
  
```
@snapend  

+++?image=audience.png
@snap[north span-90 text-center]
### @color[orange](ทำไมต้องใช้ **Markdown**?)

@snapend

@snap[east span-40 text-center]
@ul[list-square-bullets striped-list-items](false)  

```md
        Markdown

# Hello
## Hi
 * Apple
 * Banana
 * Orange

```
@snapend  

@snap[west span-40 text-center]
@ul[list-square-bullets striped-list-items](false)

# Hello
## Hi
 * Apple
 * Banana
 * Orange

@snapend

---?image=audience.png

@snap[west span-45 text-center]
### @color[orange](**การเขียน<br>หัวเรื่อง**)  
@snapend

@snap[east span-55 text-center]
@ul[list-square-bullets striped-list-items](false)

```md
        # หัวเรื่อง 1
```
```md
        ## หัวเรื่อง 2
```
```md
        ### หัวเรื่อง 3
```
```md
        #### หัวเรื่อง 4
```
```md
        ##### หัวเรื่อง 5
```
```md
        ###### หัวเรื่อง 6

```

@ulend
@snapend

+++?image=audience.png

@snap[west span-45 text-center]
## @color[orange](**ผลลัพธ์**) 
@snapend

@snap[east span-55 text-center]
@ul[list-square-bullets striped-list-items](false)

# @color[silver](หัวเรื่อง 1)

## @color[silver](หัวเรื่อง 2)

### @color[silver](หัวเรื่อง 3)

#### @color[silver](หัวเรื่อง 4)

##### @color[silver](หัวเรื่อง 5)

###### @color[silver](หัวเรื่อง 6)

@ulend
@snapend

---?image=audience.png

@snap[north-west span-50 text-left]
### @color[orange](**รูปแบบตัวอักษร**)
@snapend

@snap[north-east span-50 text-center text-08]
## @color[orange](**    ผลลัพธ์**)
@snapend

@snap[west span-30 text-center fragment]
@box[bg-black](`_ตัวเอียง_`)
@box[bg-black](`**ตัวหนา**`)
@snapend

@snap[east span-30 text-10 fragment]
@box[bg-black](_ตัวเอียง_)
@box[bg-black](**ตัวหนา**)
@snapend



---?image=audience.png

### @color[orange](**การใช้ลิสด์มี 2 แบบ**)

---?image=audience.png

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
       1. แมว  
       2. หมา  
       3. หมู  
       4. ไก่  
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
## @color[orange](**ผลลัพธ์**)

1. แมว  
####  
2. หมา  
####  
3. หมู  
####  
4. ไก่  
@snapend

---?image=audience.png

@snap[north-west span-50 text-center]

### @color[orange](**แบบไม่เรียงลำดับ**)  

```md
       - จันทร์
       - จันทร์
       - จันทร์
```

```md
       * อังคาร
       * อังคาร
       * อังคาร
```

```md
       + พุทธ
       + พุทธ
       + พุทธ
```
@snapend

@snap[north-east span-50 text-center text-08]

## @color[orange](ผลลัพธ์)  

● จันทร์  
● จันทร์  
● จันทร์  
#### 
● อังคาร  
● อังคาร  
● อังคาร  
#### 
● พุทธ  
● พุทธ  
● พุทธ  
#### 
 
@snapend

---?image=audience.png 

## @color[orange](ใส่รูปภาพใน Markdown)

            ![Google](https://sv1.picz.in.th/images/2019/12/05/iZyaHz.jpg)

**@color[orange](ผลลัพธ์)**

### ![Google ](https://www.google.co.th/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

---?image=audience.png

## @color[orange](ใส่ Video ใน Markdown)

            ![Video](https://youtu.be/KmW0iSGlCgQ)
**@color[orange](ผลลัพธ์)**

<iframe width="360" height="240" src="https://www.youtube.com/embed/KmW0iSGlCgQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---?image=audience.png 

## @color[orange](ใส่ link ใน Markdown)

    [Leanpub](https://leanpub.com/courses/leanpub/markdown1/read/1?published=true)

**@color[orange](ผลลัพธ์)**

[**Google**](https://www.google.com/)