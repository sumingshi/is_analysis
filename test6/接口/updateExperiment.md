<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：updateExperiment  [返回](../README.md)

- 功能：
    新添加实验。

- 权限：
    老师:只能对自己已选课程添加实验

- API请求地址：
    接口基本地址/v1/api/updateExperiment

- 请求方式 ：
    POST

- 请求实例：

        {
            "cname":"C语言基础",
            "ename":"实验一",
            "github":"www.XXX....COM"
            }
        }

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |cname|课程名|
  |ename|实验名|
  |github|实验的github地址|

- 返回实例：

        {
            "status": true,
            "info": null,

        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，

