<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：teacherLookScore  [返回](../README.md)
用例： [查看成绩](../用例/查看成绩.md)

- 功能：
   老师查看自己教学课程下的所有学生成绩

- 权限：
    老师：必须先登录。

- API请求地址：
    接口基本地址/v1/api/teacherLookScore/<teacher_id>

- 请求方式 ：
    GET

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |teacher_id|老师id|

- 返回实例：

        {
            "row": {
                "studentNumber",201510414117",
                "name": "诗诗",
                "class": "软工一班",
                "a":"90",
                "b":"70",
                "c":"80",
                "avg":"80"
            },
            "row": {
                "studentNumber",201510414117",
                "name": "诗诗",
                "class": "软工一班",
                "a":"90",
                "b":"70",
                "c":"80",
                "avg":"80"
            }
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------|
  |studentNumber|学号|
  |name|学生姓名|
  |class|班级|
  |a|完成度成绩|
  |b|复杂度成绩|
  |c|答辩成绩|
  |avg|平均成绩|