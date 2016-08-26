## objective基础 第二版

### 记录

1. . 间接：编程里的哲学性？分层。
2. 方法（函数）与数据：过程式与OOM。举例：绘制图形：矩形，圆，等。消息，事件属于什么呢？
3. OOP，面向接口
4. 类簇 class cluster
5. 内存管理，属资源管理范畴；对象生命周期，对象所有权，自动释放，弱、强引用，保留与释放（release，retain），arc，对象池，自动释放池，内存管理规则（内存管理约定），临时对象、持有对象，_bridge桥接（void *,,id,,cgstringref ,, nsstring 类型）
6. ARC转换是个单向操作，不可逆。
7. @synthesize与代码生成，Xcode4.5后可以省略
8. 点表达式，属性获取和KVC在后台工作上没联系。
9. 类别：在该类的m文件最上是extension，类别声明中接口interface与实现implement写法是类似，都要有括号中，类别作用名；名称冲突的优先级：类别方法。无法容纳实例。却可以用全局字典来合作克服后者局限。又称为范畴
10. 类扩展，找到原有类，加入新增。利用类别分散实现代码。分类是个优雅的操作。前向引用，先声明后定义。
11. 非正式协议与委托：委托强调类别的另一个应用：被发送给对象的方法可以声明为nsobject的类别。创建nsobject的类别叫做创建一个非正式协议。在计算机术语中协议，是一组管理通信的规则。
12. 正式协议，protocol，委托方法。还有协议可以不带<NSObject>的？
13. shadow copy，deep copy，nscopying
14. id是一个范型类型，可以指向任意类型的对象。id后采用adopt协议，则约束了传输引用对象需要服从协议。
15. closure闭包：代码块，两种类型的绑定（自动绑定automatic bind，栈，托管绑定managed bind，堆），c语言函数指针，代码快被声明时会捕捉创建点的状态：context，
16. 类型声明，类型推导。
17. mutex：mutual exclusion
18. 并发性：同步，调度队列（连续队列，并发队列，主队列）
19. 本地持久化：属性列表类，编码对象（序列与反序列）nscoding，归档
20. 键值编码，键值快速运算（value forkey path），kvc的两个调用：批量处理（dictionaryWithValuesForKeys，等）
21. 静态分析器：要去体验一下
22. 谓词，NSPredicate，




