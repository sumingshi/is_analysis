<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：lookExperiment  [返回](../README.md)

- 功能：
    查看学生完成的实验

- 权限：
    老师

- API请求地址：
    接口基本地址/v1/api/lookExperiment/<teacher_id>

- 请求方式 ：
    GET

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |teacher_id|老师id|

- 返回实例：

        {
            "row":{
                "cname":"C语言",
                "ename":"实验一",
                "github":"asdasd432as4d3.com"
            },
            "row":{
                "cname":"C语言",
                "ename":"实验一",
                "github":"asdasd432as4d3.com"
            }
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |cname|课程名|
  |ename|实验名|
  |github|github地址|

