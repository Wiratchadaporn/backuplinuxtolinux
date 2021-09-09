# backuplinuxtolinux


1. สร้างโฟลเดอร์ linuxtolinux ไว้ที่ /mnt (/mnt/linuxtolinux)
   เครื่องที่2 สร้างโฟลเดอร์ชื่อ backuptolinux (/mnt/backuptolinux)
   
   
![1  ต้นทาง 132](https://user-images.githubusercontent.com/89773987/132617589-fba3bc0d-af28-4364-a199-9dfb9fef17ff.png)

![1  ปลายทาง 136](https://user-images.githubusercontent.com/89773987/132617925-4947063a-f627-43d7-82f4-ecae0b643e04.png)



2. backup ไฟล์ fonts.conf ใน /etc และโฟลเดอร์ /etc/fonts ทั้งหมด ไปไว้ที่ /mnt/linuxtolinux   เขียนเป็น shell script


backup ไฟล์ fonts.conf
![1  ไฟร์ fonts conf](https://user-images.githubusercontent.com/89773987/132618192-97fe784a-f379-4145-be60-97f359c5cc26.png)

![1  bat fonts conf](https://user-images.githubusercontent.com/89773987/132618215-674f7df1-7473-44f3-aeef-0728f769cd2a.png)







backup โฟลเดอร์ fonts

![2  โฟรเดอร์ fonts](https://user-images.githubusercontent.com/89773987/132618227-44c40103-ab14-42cd-afdd-c6742426ef21.png)



![2 bat โฟรเดอร์ fonts](https://user-images.githubusercontent.com/89773987/132618240-5d8a8060-3b6a-4c0c-b3b7-b1d347213cda.png)



เช็คไฟล์และโฟลเดอร์ที่Backup
![3 เช็คไฟล์ทั้ง 2](https://user-images.githubusercontent.com/89773987/132618479-e3921d19-e470-49d2-a8a3-a93550fa45ff.png)





3. สร้าง Key แล้วส่งไปยังเครื่องที่2 แล้วแสดงคำสั่ง




key ต้นทาง
![1  keygen ต้นทาง](https://user-images.githubusercontent.com/89773987/132618706-34f51548-506c-478c-930c-a505d277b4e8.png)






key ที่ส่งไปยังปลายทาง
![1  ส่ง keygen จากต้นทางมาปลายทาง](https://user-images.githubusercontent.com/89773987/132618775-a6600563-dc4d-4e95-918c-f101fff7a220.png)








4. Backup ไฟล์ fonts.conf ของ linux เครื่องที่1 มาไว้ใน /mnt/backuptolinux ของเครื่องที่2 เขียนเป้น shell script


shell script
![02 shell script](https://user-images.githubusercontent.com/89773987/132619138-743ab6a7-74a2-42ef-9e45-0a0efd58e297.png)


Run shell script
![01 วิธีการ backup ไฟล์](https://user-images.githubusercontent.com/89773987/132619118-6e516abd-4041-4c39-880e-a373e635a0a9.png)


ส่งไฟล์ fonts.conf ไปถึงเครื่องปลายทาง
![03 อีกวิธี](https://user-images.githubusercontent.com/89773987/132619150-d9292609-c321-4f63-b703-f0cd405064e1.png)






5. Backup ไฟล์ /mnt/linuxtolinux/fonts ของ linux เครื่องที่1 มาไว้ใน /mnt/backuptolinux ของเครื่องที่2 เขียนเป้น shell script


shell script
![1  shell scirpt โฟล์เดอร์ fpnts](https://user-images.githubusercontent.com/89773987/132619705-f5113510-69d2-4995-acf1-8b29d0915cc2.png)



Run shell script
![2 backup สำเร็จ](https://user-images.githubusercontent.com/89773987/132619758-668e36d7-da50-4fb0-9477-ebbd28055b00.png)




ส่งไฟล์ fonts.conf ไปถึงเครื่องปลายทาง
![4 สำเร็จ](https://user-images.githubusercontent.com/89773987/132619805-b242a8d5-1e8b-43fb-898e-48aed7d872e0.png)




7. แสดงผลลัพธ์ของเครื่อง2



![แสดงผล เครือง 2](https://user-images.githubusercontent.com/89773987/132619974-1bf596f4-b462-45b1-88ef-4cf9412a1ad9.png)









