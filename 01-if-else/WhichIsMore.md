**โปรแกรมเปรียบเทียบจำนวนเต็มบวกหรือศูนย์ 2 จำนวน**

**ข้อมูลเข้า:** ให้รับค่าจำนวนเต็มบวกหรือศูนย์ 2จำนวน

**ข้อมูลออก:** จะแสดงผลดังนี้

- หากตัวเลขทั้งสองมีค่าเท่ากันจะแสดงผลว่า It is equal.

- หากตัวเลขทั้งสองมีค่าไม่เท่ากันจะแสดงผลว่า It is not equal. และในบรรทัดต่อมาให้แสดงผลว่าค่าใดที่มากกว่า ตัวอย่างเช่น รับตัวเลข A และ B จะแสดงผลว่า A is more than B.

- หากค่าที่รับมาตัวใดตัวหนึ่งเป็นจำนวนเต็มลบหรือมีค่าน้อยกว่าศูนย์จะแสดงผลว่า Error.

**หมายเหตุ:** จำนวนเต็มที่รับเข้ามาจะต้องมีค่าไม่เกิน 2,147,483,647

**Test Case:**

```
5
8
It is not equal.
8 is more than 5.
```
```
100
100
It is equal.
```
```
-54540
0
Error.
```
