**โจทย์**
มีรถแข่งทั้งหมด 10 คัน คุณต้องการค้นหารถแข่งคันที่มีคุณสมบัติตรงตามเงื่อนไขต่อไปนี้
- ความเร็วอยู่ระหว่าง 210 ถึง 230 กิโลเมตรต่อชั่วโมง

จากนั้นทำการแสดงชื่อของรถที่มีความเร็วตามเงื่อนไข

จงเขียนโปรแกรมโดยใช้ Linear Search เพื่อค้นหารถแข่งคันดังกล่าว และแสดงผลของรถคันนั้น

**ตัวอย่างโค้ด**
```py
arr = [1, 3, 5, 7, 9]
target = 5

hash_value = hash(target)
index = 0
while index < len(arr):

    # ถ้าค่าของ Hash ตรงกันก็แสดงว่าพบข้อมูลที่ต้องการค้นหา
    if hash(arr[index]) == hash_value:
        print(index)
        break

    # เลื่อนตำแหน่งไปทีละตำแหน่ง
    index += 1
```

**ผลลัพธ์ที่ต้องการ**
`
Supra 180 km/h
`