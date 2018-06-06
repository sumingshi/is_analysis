<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：teacherUpdateCourse  [返回](../README.md)

- 功能：
    新添加实验。

- 权限：
    老师:只能对自己已选课程添加实验

- API请求地址：
    接口基本地址/v1/api/teacherUpdateCourse

- 请求方式 ：
    POST

- 请求实例：

        {
            "cname":"C语言",
            "num":"2017",
            "time":"大三上学期",
            "credit":"4.0"
            }
        }

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |cname|课程名|
  |num|课程号|
  |time|开课时间|
  |credit|学分|

- 返回实例：

        {
            "status": true,
            "info": null,

        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，

