Katacoda课程是通过创建路径文件来定义的。路径定义了哪些场景应该包含在课程中，以及显示它们的顺序。
Course: 指一系列场景的集合
scenarios：场景

The collection of examples contains two courses, one to describe all the Katacoda content and another to describe the key Katacoda environments.

## Clone Example

Clone the example repository with the command `git clone https://github.com/katacoda/scenario-examples.git katacoda-scenario-examples`{{execute}}

Within the root of a repository, a course has been created called `uilayouts`. The contents of the course have been defined as `katacoda-scenario-examples/uilayouts-pathway.json`{{open}}.

Within the JSON file, the courses element defines each scenario. For example:

<pre class="file">
{
    "course_id": "uilayout-terminal",
    "title": "Scenario with Terminal UI",
    "description": "Katacoda Scenario Example"
},
</pre>

The **course_id** is the scenario name directory within the course directory. For example `ls katacoda-scenario-examples/uilayouts/uilayout-terminal`{{execute}}. The **title** and **description** are shown on the course page.