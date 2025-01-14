## BreadcrumbsStocastic-and-Minibatch-GD
# Objective
* ทดสอบการ run Stochastic Gradient descent และ Mini Batch Gradient descent เพื่อเปรียบเทียบความเร็วและผลลัพท์ในการ run ด้วยข้อมูลชุดเล็ก
# เครื่องมือที่ใช้
* Multiple linear regression by Stochastic Gradient descent
* Multiple linear regression by Mini Batch Gradient descent
# Dataset (Sample Data)
* x = np.array([[0,1],[2,6],[3,8]]) # x1, x2
* y = np.array([1,1,4])
# Result
1. Stochastic Gradient descent
   * y predict =  [[12.99925781]]
     time: 3.27 s (started: 2024-08-27 16:19:54 +00:00)
2. Mini Batch Gradient descent
   * y predict =  [[12.99872249]]
     time: 4.14 s (started: 2024-08-27 16:21:04 +00:00)
    
