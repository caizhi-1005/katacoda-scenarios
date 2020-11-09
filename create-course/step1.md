Katacoda课程是通过创建路径文件来定义的。路径定义了哪些场景应该包含在课程中，以及显示它们的顺序。
Course: 指一系列场景的集合
scenarios：场景


## 克隆示例代码

克隆官方示例代码仓库命令 `git clone https://github.com/katacoda/scenario-examples.git katacoda-scenario-examples`{{执行}}

示例代码中，通过json文件找到对应的文件夹，profile-pathway.json，可以看到格式为
<pre class="file">
{
    "courses": [
      {
        "title": "Katacoda UI Layouts Example",
        "description": "Example of different Katacoda UI Layouts. Also, an example of creating a Katacoda Course!",
        "id": "uilayouts"
      }
    ],
    "scenarios": [
      {
        "title": "Creating a Katacoda Course",
        "description": "Learn how to create a collection of Katacoda scenarios into a course",
        "id": "create-course"
      },
      {
        "title": "Markdown Extensions",
        "description": "Examples of how the Katacoda Markdown Extensions",
        "id": "markdown-extensions"
      },
      {
        "title": "Interactive Quiz",
        "description": "Verify understand and key points by using an interactive quiz",
        "id": "quiz"
      }
    ]
  }
</pre>
其中，课程（courses)和场景（scenarios）都可以为多个，
title为页面显示的题目，description为课程的描述，
id则与你自己github仓库中文件夹的名字一一对应，相当于课程文件夹中场景的字典。