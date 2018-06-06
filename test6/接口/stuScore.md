<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：stuScore  [返回](../README.md)
用例： [学生查看成绩](../用例/学生查看成绩.md)

- 功能：
   查看学生的成绩
   可以按照学期，课程，实验来查看

- 权限：
    学生：必须先登录。

- API请求地址：
    接口基本地址/v1/api/stuScore/<student_id>

- 请求方式 ：
    GET

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |student_id|学生id|

- 返回实例：

        {
            "row": {
                "courseName","C语言",
                "exeperimentName": "实验一",
                "completeScore":"90",
                "complexeScore": "70",
                "answerScore":"80"
            },
            "row": {
                "courseName","C语言",
                "exeperimentName": "实验二",
                "completeScore":"60",
                "complexeScore": "80",
                "answerScore":"80"
            }
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------|
  |row|一行数据|
  |courseName|课程名|
  |exeperimentName|实验名|
  |completeScore|复杂度得分|
  |complexeScore|完成度得分|
  |answerScore|答辩得分|