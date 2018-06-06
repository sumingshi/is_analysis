﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：getUserInfo  [返回](../README.md)

- 功能：
    查看用户的所有信息。
    
- 权限：
    学生/老师：查看自己的信息，必须先登录，不能查看其他用户的信息。    
    
- API请求地址： 
    接口基本地址/v1/api/getUserInfo/<student_id>

- 请求方式 ：
    GET
      
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |student_id|学生的ID号|
  
- 返回实例：

        {         
            "status": true,
            "info": null,
            "ID":"123456",  
            "studentNumber":20151041423"
            "name":"诗诗",
            "github":"https://github.com/sumingshi/is_analysis",
            "sex":"女",
            "class":"软件工程一班"
            "picture":"picture/20151041423.png"
        }
 
- 返回参数说明：    
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|
  |ID|自然主键|
  |studentNumber|学号|
  |name|用户的真实姓名|  
  |github|gitHub地址|
  |class|班级|
  |sex|性别|
  |picture|图片路径|

