# Rust.exercise
Rust small exercise 
2) Structs 2) 结构体
Use and extend the prepared file src/main.rs and build everything with cargo .
使用并扩展准备好的文件 src/main.rs 并使用 cargo 构建所有内容。 A) Create own types A)创建自己的类型
Transform the code and convert the tuples into struct types
转换代码并将元组转换为结构类型
Make sure to give your new types a meaningful name ( Author , Book ) 确保为您的新类型指定一个有意义的名称( Author 、 Book )
Make sure to name your fields properly
确保正确命名您的字段
Initialize everything properly and pretty-print it
正确初始化所有内容并漂亮地打印它
          (
              "The Da Vinci Code",
              2003,
              (
"Dan Brown",
1964, ),
)
B) Introduce constructor functions B) 引入构造函数
Introduce constructor functions for your types
为您的类型引入构造函数
Replace the current initialization with function calls
用函数调用替换当前的初始化
Can we give an Author to the Book constructor?
我们可以给 Book 构造函数一个 Author 吗? Initialize everything properly and pretty-print it 正确初始化所有内容并漂亮地打印它
C) Associated functions C) 相关功能
Convert your constructors into associated functions
将构造函数转换为关联函数
Think about the differences between Self and self
考虑一下 Self 和 self 之间的区别 Initialize everything properly and pretty-print it 正确初始化所有内容并漂亮地打印它
D) Make it updatable D) 使其可更新
Extend both type implementations so, that we can update our field values
扩展这两种类型的实现，以便我们可以更新字段值
Write some setter methods
编写一些setter方法
Test them, e.g. changing title and year of our book 测试它们，例如更改书名和年份
At the end, pretty-print the updated Book instance 最后，漂亮地打印更新后的 Book 实例
E) Reuse existing data E) 重用现有数据
Create a second Book written by Dan Brown 创建第二个由 Dan Brown 编写的 Book
Use the already existing Author instance again for the new book
为新书再次使用现有的 Author 实例
At the end, pretty-print both Book instances 最后，漂亮地打印两个 Book 实例
F) Extend your program F) 扩展你的计划
Extend your program so, that you can create a set of all 5 books from the "Robert Langdon" series 扩展您的程序，以便您可以创建“罗伯特·兰登”系列中所有 5 本书的一套
You'll need a loop and a proper break condition
您需要一个循环和适当的中断条件
You'll need read_line() and trim() already known from last exercise
您需要从上次练习中已知的 read_line() 和 trim()
For simplicity, we pre-create the Author instance and reuse it (same as task 5) 为了简单起⻅，我们预先创建 Author 实例并重用它(与任务 5 相同)
Theoretical question: To save memory, can we just work with a reference instead of duplicating for each Book ?
理论问题:为了节省内存，我们可以只使用引用而不是对每个 Book 进行复制吗? At the end, pretty-print all 5 Book instances
最后，漂亮地打印所有 5 个 Book 实例
Help/Hints 帮助/提示
In order to create a set of items we can use a Vector (will be explained in a later exercise).
为了创建一组项目，我们可以使用向量(将在后面的练习中解释)。
let mut books = Vec::new();
