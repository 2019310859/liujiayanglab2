# liujiayanglab2
实验二

# 实验目的
初步了解分析系统需求，从学生选课角度了解系统中的实体及其关系，学会定义类中的属性以及方法；
1.掌握面向对象的类设计方法（属性、方法）；
2.掌握类的继承用法，通过构造方法实例化对象；
3.学会使用super()，用于实例化子类；
4.掌握使用Object根类的toString（）方法,应用在相关对象的信息输出中。

# 实验内容
说明：学校有“人员”，分为“教师”和“学生”，教师教授“课程”，学生选择“课程”。从简化系统考虑，每名教师仅教授一门课程，每门课程的授课教师也仅有一位，每名学生选仅选一门课程。
对象示例：	人员（编号、姓名、性别……）
教师（编号、姓名、性别、所授课程、……）
			学生（编号、姓名、性别、所选课程、……）
			课程（编号、课程名称、上课地点、时间、授课教师、……）
以上属性仅为示例，同学们可以自行扩展（黄色背景的文字，不能原篇出现在实验报告中，需要进一步明确所有的属性）。

# 实验要求
1.编写上述实体类以及测试主类（注意类之间继承关系的适用）
2.在测试主类中，实例化多个类实体，模拟学生选课操作、打印课程信息（信息包括：编号、课程名称、上课地点、时间、授课教师 等）；模拟学生退课操作，再打印课程信息。
3.编写实验报告。

# 核心方法
1.分别设计四个类，课程、学生、老师、人员，学生老师都属于人员类。
2.用string给各种类赋值，包括姓名、性别、年龄、课程等。
3.通过String toString集合信息，方便输出
4.输出结果。

# 实验结果
  学生编号: 2019310849  姓名: 刘佳阳  性别: 男  所选课程:Java
  教师编号: 002004****  姓名: 张老师  性别: 男  教授课程:Java
  人员编号: 2019310849  姓名: 刘佳阳  性别: 男
  课程编号: 1  课程名称: Java  上课地点: 教306  上课时间:第9~10节  授课教师:张老师
  选课学生：刘佳阳  课程编号: 1  课程名称: Java  上课地点: 教306  上课时间:第9~10节  授课教师:张老师

# 实验感想
通过本次实验，学会了string字符串赋值的方法，强化了对“类”使用的理解，对return的用法也有了更准确的理解。我认为这将对我日后的编程提供较有力的支持。
