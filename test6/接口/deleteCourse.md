<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：deleteCourse  [返回](../README.md)

- 功能：
    查看用户的所有信息。

- 权限：
    学生/老师

- API请求地址：
    接口基本地址/v1/api/deleteCourse/<courseId>

- 请求方式 ：
    DELETE

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |courseId|课程id|

- 返回实例：

        {
            "status": true,
            "info": null,

        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|

