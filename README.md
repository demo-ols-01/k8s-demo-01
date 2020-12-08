# k8s-demo-01

- การใช้งาน manifest yaml file

kubectl apply -f filename.yaml    

- การแก้ใขค่า config ต่างๆ ของไฟล์ที่ run ไปแล้ว ให้ Apply ทับลงไปได้เลย  

คำสั่งพื้นฐานเบื้องต้น  

kubectl get,describe,delete resource-name -option 

ตัวอย่างการ show node list + node IP  

kubectl get node -o wide 

ตัวอย่างการ show pod ที่อยู่ใน namespace demo 

kubectl get node -n demo

ตัวอย่างการ show service (ตัวย่อ svc) ที่อยู่ใน namespace demo 

kubectl get svc -n demo
