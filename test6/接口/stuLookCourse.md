<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：stuLookCourse  [返回](../README.md)
用例： [学生查看课程](../用例/学生查看课程.md)

- 功能：
    学生查看自己选了哪些课程，并且能够查看任课老师的信息

- 权限：
    学生：必须先登录。

- API请求地址：
    接口基本地址/v1/api/stuLookCourse/<studentId>

- 请求方式 ：
    GET

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |studentId|学生id|

- 返回实例：

        {
            "course": {
                "courseNum": "1240",
                "name": "信息系统",
                "credit": "3.5",
                "time":"大一上学期"
            },
            "course": {
                "courseNum": "1241",
                "name": "信息系统2",
                "credit": "3.5",
                "time":"大一下学期"
            }
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------|
  |courseNum|课程号|
  |name|课程名称|
  |credit|学分|
  |time|开课时间|