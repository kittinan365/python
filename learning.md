###### การเรียนรู้เขียนโปรแกรม ####
ctrl+j เปิดปิดเทอมิเนอ
ctrl+b 
ctrl+w เปิดปิดแท็ป
dir แสดงไฟล์
mkdir สร้างไฟล์ ตามด้วยชื่อเว้นวรรค
cd \ 
cd ..
ctrl+shift+n เปิดไฟล์
shift+alt+     ลง
ctrl+shift+n ลบปัจจุบัน
alt ขึ้นลง โค้ด
shift+alt ค้างไว้ เขียนทุกบรรทัด
ctrl+d
ctrl+f2 เลือกทั้งหมด
ctrl+p เปอดไฟล์เร็ว
ctrl+ฃ
ctrl+w ปิดจอ
###### คณิตศาสตร์ ####
+ 1+3
- 3-3
x 2 *3 
หาร 
ยกกำลัง
หารตัดทศนิยม
print(6%2) #เอาค่าเศษ
print(2**4) #คูณกันตามจำนวน
print(100//9) #หาร9
##### สินค้าาาาา ####
point = int(input("point :"))
if point ==20:
    print("โค้ก")
elif point == 30:
    print("เลย์")
elif point == 40:
    print("โออิชิ")
elif point == 50:
    print("มาม่า")
elif point == 10:
    print("น้ำเปล่า")
elif point == 100:
    print("น้ำส้ม")
else:
    print("ไม่ใช่")

    for i in range(1,200):
    if i % 2==1:
        print(i)

###### week 3 ####
i = 200
# i น้อยกว่าหรือเท่ากับ 100 จริงไหม
while i <= 100:
#    i mod 2 จริงไหม
    if i % 2 == 1 :
        print(i)
    
    i += 1
<!-- อาร์เรย์ -->
    fruits = ["โน้ต","เอิร์น","พีท","ปลั๊ก","ก้อง"]
# เก็บตัวแปรอาร์เรย์
for x in fruits:
# แสดงตัวแปรอาร์เรย์ ทีละคำ ปริ้นx 
    print(x)
##### พารามิเตอร์ ####
def addvolumn(num,num2) :
    print ("เพิ่มเสียง")
    print (num)
    print(num2)
def dowvolumn(num,num2) :
    print ("ลดเสียง")
    print (num)
    print (num2)
def turn_off_TV() :
    print ("ปิด")
def turn_or_TV() :
    print ("เปิด")
def home():
    print ("ปุ่มโฮม")

addvolumn(5,10)
dowvolumn(5,10)
addvolumn(15,20)
turn_off_TV()
turn_or_TV()
home()

//////////////////
def plus(num,num2) :
    print ("บวก")
    print (num+num2)
def minus(num,num2) :
    print ("ลบ")
    print (num-num2)
def multiply(num,num2) :
    print ("คูณ")
    print (num*num2)
def divide(num,num2) :
    print ("หาร")
    print (num/num2)


plus(5,10)
minus(5,10)
multiply(15,20)
divide(40,20)
