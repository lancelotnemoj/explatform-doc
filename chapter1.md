# 需求分析

## Frontend

### 公共

* 显示解锁码

### 教师

* 查看自己的课程
* 查看课程下面的实验
* 开始实验
* 查看单个实验所有信息
* 查看实验报告
* 打分

### 学生

* 查看自己课程
* 查看课程下面实验
* 显示实验分数
* 编辑实验报告

## Backend

### 公共

* 提供解锁码
* 登录
* 登出

### 教师

* 根据教师获取课程
* 根据课程获取实验
* 根据实验获取所有学生的实验记录
* 根据学生和实验获取报告内容
* 修改学生实验记录（打分）

### 学生

* 根据学生获取课程
* 根据学生和课程获取实验信息
* 根据学生和实验提交报告

## Platform

### Mqtt

> mqtt负责和网关通信，间接控制开关盒子的上电

* 发出开始实验的信号



### Http

> http与打分机直接联系，负责实际业务流程



