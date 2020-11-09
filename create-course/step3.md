Katacoda 还提供了命令行工具，可帮助创建课程和 scenarios 等所需的文件。
当然，如何熟悉了课程和场景的编写语法（markdown格式）和规则，你可以选择不通过命令行来创建。

安装CLI 命令:
`npm i katacoda-cli --global`{{execute}}

如果需要帮助，你可以执行以下命令
`katacoda --help`{{execute}}


举例创建一个课程：

```
cd katacoda-scenario-examples
katacoda courses:create
```{{execute}}

The CLI will prompt you a few questions about:
- **Title:** title of the course, displayed on the intro screen
- **Description:** description of the course, displayed on the intro screen
- **Friendly-url:** here you will type `test-course`. This attribute will determine the name of the folder of your course, and the URL to access it, so, should not contain spaces, should be lower case, etc. For example, if your username is *test-username* and your course was called *test-course* the URL to point the course in the platform will be https://katacoda.com/你的katacoda名字/courses/刚刚创建的katacoda课程名字/

After that the CLI will create the pathway file and the folder.
`ls test-course*`{{execute}}

You can see the definition of the empty course in `katacoda-scenario-examples/test-course-pathway.json`{{open}}

<pre class="file">
{
  "title": "test-course",
  "description": "Example course",
  "courses": []
}
</pre>