# Tag ต่างๆที่เกี่ยวกับ text หรือ ข้อความ

## Heading tag (h tag)

ใช้สำหรับเขียนหัวข้อ หรือหัวเรื่อง ประกอบด้วย h1 ถึง h6 โดย ไล่จากลำดับความสำคัญ จาก h1 สำคัญมากที่สุด ไปยัง h6 สำคัญน้อยที่สุด

### ตัวอย่าง

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

### หลักการใช้ Heading tag อย่างถูกต้อง

- ควรใช้ h1 เพียง 1 tag ต่อหน้าเว็บ 1 หน้าเท่านั้น หากใช้มากกว่านั้น Search engine อย่าง Google จะงง
- ใช้ Heading tag ต่างๆ ในการจัดลำดับความสำคัญเป็น Hierarchy ลึกลงไปเป็นชั้นๆ โดยไม่ต้องสนใจเรื่องขนาด Font มาก เพราะสุดท้ายเราปรับได้ด้วย CSS

## Paragraph tag (p tag)

เอาไว้ใช้สำหรับเขียนข้อความทั่วไป

### ตัวอย่าง

```html
<p>
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae
  earum fuga exercitationem consequuntur! Aperiam officia amet repellendus
  dolores temporibus ipsa!
</p>
```

## Strong tag

เอาไว้ใช้สำหรับเน้นสิ่งที่สำคัญ อยากให้สะดุดตาผู้อ่าน และมักสำคัญกว่าข้อความรอบข้าง มี style bold (ตัวหนา) ติดมาด้วย แต่สามารถปรับแต่งได้ด้วย CSS ภายหลัง

### ตัวอย่าง

```html
<p>
  ข้อความทั่วไป ข้อความทั่วไป ข้อความทั่วไป ข้อความทั่วไป <strong>ข้อความที่อยากเน้น</strong> ข้อความทั่วไป
</p>
```

## Emphasize tag (em tag)

เอาไว้ใช้เน้นข้อความ แต่ไม่เน้นเท่า strong tag มี style italic (ตัวเอียง) ติดมาด้วย แต่สามารถปรับแต่งได้ด้วย CSS ภายหลัง

### ตัวอย่าง

```html
<p>
  ข้อความทั่วไป ข้อความทั่วไป ข้อความทั่วไป ข้อความทั่วไป <em>ข้อความที่อยากเน้น</em> ข้อความทั่วไป
</p>
```
