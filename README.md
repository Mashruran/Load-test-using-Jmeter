# Booking API Performance Testing with JMeter

## This repository contains a JMeter test plan (booking.jmx) designed to perform load testing and stress testing on the Restful-Booker API

### The testing covers:

- Authentication (Login)

- Booking Creation (with randomized data)

- Booking Search (using booking ID)

### Technical Scope
 - Install Apache JMeter 5.6+ → Download JMeter
 - Java 11 or higher

### How to run this project
1. Clone this repository
   ```https://github.com/Mashruran/Load-test-using-Jmeter```
2. Run Load Test 
   ```jmeter -n -t .\booking.jmx -l .\booking.jtl -e -o Reports```
3. Run Stress Test
   ```jmeter -n -t .\booking.jmx -l .\booking.jtl -e -o Reports```

### Test Reports:
### Load Test Report (excel): 
<img width="1037" height="433" alt="Screenshot 2025-09-20 145623" src="https://github.com/user-attachments/assets/672e7ccd-84e5-4aef-8a66-2a247db28489" />

### Load Test HTML Report: 
<img width="1532" height="816" alt="image" src="https://github.com/user-attachments/assets/b3eb02a4-0ed3-4b84-9acc-4dddd78d0afd" />

### Stress Test Report (excel): 
<img width="1177" height="643" alt="Screenshot 2025-09-20 145648" src="https://github.com/user-attachments/assets/4f3360a3-2d86-4ece-b7b3-1831cb7967c5" />

### Stress Test HTML Report: 
<img width="1537" height="814" alt="image" src="https://github.com/user-attachments/assets/75d6adb3-525b-4dee-850b-0804be26bc9f" />

