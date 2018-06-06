<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：stuSelectCourse  [返回](../README.md)
用例： [学生添加课程](../用例/学生添加课程.md)

- 功能：
    学生选择要上的课程
    
- 权限：
    学生：必须先登录。
    
- API请求地址： 
    接口基本地址/v1/api/stuSelectCourse

- 请求方式 ：
    POST

- 请求实例：

        {
            "studentId":"12345679"
            "courseId":"1002,1035,2006"
        }
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |studentId|学生id|
  |courseId|课程号|
  
- 返回实例：

        {         
            "status": true,
            "info": null,    

        }
 
- 返回参数说明： 
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |status|bool类型，true表示正确的返回，