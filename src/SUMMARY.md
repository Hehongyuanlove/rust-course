# Rust语言圣经

[Rust语言圣经](about-book.md)
[进入Rust编程世界](into-rust.md)

## Getting started

- [寻找牛刀，以便小试](first-try/intro.md)
    - [安装Rust环境](first-try/installation.md)
    - [墙推VSCode!](first-try/editor.md)
    - [认识Cargo](first-try/cargo.md)
    - [不仅仅是Hello world](first-try/hello-world.md)

## Rust学习三部曲

- [基本语法 doing](basic/intro.md)
    - [变量绑定与结构](basic/variable.md)
    - [基本类型](basic/base-type/index.md)
        - [数值类型](basic/base-type/numbers.md)
        - [字符、布尔、元类型](basic/base-type/char-bool.md)
        - [语句与表达式](basic/base-type/statement-expression.md)
        - [函数](basic/base-type/function.md)
    - [所有权和借用](basic/ownership/index.md)
        - [所有权](basic/ownership/ownership.md)
        - [引用与借用](basic/ownership/borrowing.md)
    - [复合类型](basic/compound-type/intro.md)
        - [字符串与切片](basic/scompound-type/tring-slice.md)
        - [元组](basic/compound-type/tuple.md)
        - [结构体](basic/compound-type/struct.md)
        - [枚举](basic/compound-type/enum.md)
        - [数组](basic/compound-type/array.md)
    - [流程控制](basic/flow-control.md)
    - [模式匹配](basic/match-pattern/intro.md)
        - [match和if let](basic/match-pattern/match-if-let.md)
        - [解构Option](basic/match-pattern/option.md)
        - [模式适用场景](basic/match-pattern/pattern-match.md)
        - [全模式列表](basic/match-pattern/all-patterns.md)
    - [方法Method(todo)](basic/method.md)
    - [泛型(todo)](basic/generitic.md)
    - [特征(todo)](basic/trait.md)
    - [类型转换 todo](basic/type-converse.md)
    - [返回、异常和错误(todo)](basic/exception-error.md)


    
- [进阶语法 todo](advance/intro.md)
    - [集合类型(todo)](advance/collection.md)
    - [格式化输出(todo)](advance/formatted-output.md)
    - [文档注释(todo)](advance/comment.md)
    - [包和模块(todo)](advance/crate-module.md)
    - [生命周期(todo)](advance/lifetime.md)
    - [迭代器(todo)](advance/interator.md)
    - [函数式编程(todo)](advance/functional-programing.md)
    - [智能指针(todo)](advance/smart-pointer.md)
    - [全局变量](advance/global-variable.md)

## 专题内容,每个专题都配套一个小型项目进行实践

- [错误处理 todo](errors/intro.md)
    - [panic!](errors/panic.md)
    - [适用Result返回错误](errors/result.md)
    - [自定义错误](errors/user-define.md)
    - [让错误输出更优雅](errors/pretty-format.md)
    - [会导致panic的代码](errors/panic-codes.md)

- [Cargo详解 todo](cargo/intro.md)
    - [常用命令](cargo/commands.md)
    - [项目结构](cargo/layout.md)
    - [Cargo.toml和Cargo.lock](cargo/cargo-toml-lock.md)
    - [依赖管理](cargo/dependency.md)
    - [构建缓存](cargo/cache.md)
    - [版本管理](cargo/version.md)
    - [工作空间](cargo/workspace.md)
    - [条件编译、条件依赖](cargo/feature.md)
    - [配置参数(todo)](cargo/manifest.md)
    - [自定义构建脚本](cargo/build-js.md)
    - [Cargo profile](cargo/profile.md)
    
- [测试 todo](test/intro.md)
    - [单元测试](test/unit.md)
    - [集成测试](test/intergration.md)
    - [性能测试](test/benchmark.md)
    - [持续集成](test/ci.md)

- [日志和监控 todo](monitor/intro.md)
    - [日志](monitor/log.md)
    - [可观测性](monitor/observability.md)
    - [监控(APM)](monitor/apm.md)

- [智能指针 todo](smart-pointer/intro.md)
    - [Box对象(todo)](smart-pointer/box.md)
    - [Deref和Drop特征(todo)](smart-pointer/deref-drop.md)
    - [Rc与RefCell(todo)](smart-pointer/rc-refcell.md)
    - [自引用与内存泄漏(todo)](smart-pointer/self-referrence.md)

- [常见特征解析 todo](traits/intro.md)
    - [类型转换From/Into](traits/from-into.md)
    - [AsRef, AsMut](traits/as-ref-as-mut.md)
    - [Borrow, BorrowMut, ToOwned](traits/borrow-family.md)
    - [Deref和引用隐式转换](traits/deref.md)
    - [写时拷贝Cow](traits/cow.md)
    
- [多线程 todo](multi-threads/intro.md)
    - [线程管理(todo)](multi-threads/thread.md)
    - [消息传递(todo)](multi-threads/message-passing.md)
    - [数据共享Arc、Mutex、Rwlock(todo)](multi-threads/ref-counter-lock.md)
    - [数据竞争(todo)](multi-threads/races.md)
    - [Send、Sync(todo)](multi-threads/send-sync.md)

- [深入内存 todo](memory/intro.md)
    - [指针和引用(todo)](memory/pointer-ref.md)
    - [未初始化内存(todo)](memory/uninit.md)
    - [内存分配(todo)](memory/allocation.md)
    - [内存布局(todo)](memory/layout.md)
    - [虚拟内存(todo)](memory/virtual.md)

- [网络和异步编程 todo](networking/intro.md)
    - [TCP和网络原理(todo)](networking/tcp.md) 
    - [并发与并行(todo)](networking/concurrency-parallelism.md)
    - [异步编程](networking/async/intro.md)
        - [async/await语法](networking/async/async-await.md)
        - [future详解](networking/async/future/into.md)
            - [何为Future](networking/async/future/future.md)
            - [任务调度](networking/async/future/task-schedule.md)
            - [任务执行器](networking/async/future/task-excutor.md)
            - [系统IO](networking/async/future/system-io.md)
            - [执行多个Future](networking/async/future/multi-futures.md)
        - [Pin、Unpin(todo)](networking/async/pin-unpin.md)
        - [遇到不支持的异步特性?](networking/async/future/workarounds.md)
        - [HTTP Client/Server](networking/async/http.md)
        - [定海神针-tokio包](networking/async/tokio/intro.md)
            - [基本用法](networking/async/tokio/basic.md)
            - [异步消息流](networking/async/tokio/stream.md)

- [常见陷阱 todo](traps/intro.md)

- [代码规范 doing](style-guide/intro.md)
    - [命名规范](style-guide/naming.md)
    - [代码风格(todo)](style-guide/code.md)
    - [代码标记](style-guide/mark.md)
    - [Clippy](style-guide/clippy.md)
    
- [面向对象 todo](object-oriented/intro.md)
    - [为何OO(todo)](object-oriented/characteristics.md)
    - [特征对象](object-oriented/trait-object.md)
    - [设计模式](object-oriented/design-pattern.md)

- [不安全Rust todo](unsafe/intro.md)
    - [原生指针(todo)](unsafe/raw-pointer.md)
    - [修改全局变量](unsafe/modify-global-var.md)
    - [FFI外部语言用](unsafe/ffi.md)

- [对抗编译检查 todo](fight-with-compiler/intro.md)
    - [幽灵数据(todo)](fight-with-compiler/phantom-data.md)
    - [生命周期(todo)](fight-with-compiler/lifetime.md)
    - [类型未限制(todo)](fight-with-compiler/unconstrained.md)
    
- [宏编程 todo](macro/intro.md)
    - [过程宏(todo)](macro/procedure-macro.md)

- [性能调优 todo](performance/intro.md)
    - [Clone和Copy](performance/clone-copy.md)
    - [Benchmark性能测试(todo)](performance/benchmark.md)
    - [减少Runtime check(todo)](performance/runtime-check.md)

- [编译器 todo](compiler/intro.md)
    - [常见属性标记](compiler/attributes.md)

- [标准库解析 todo](std/intro.md)
    - [如何寻找你想要的内容](std/search.md)
    

- [常用三方库 todo](libraries/intro.md)
    - [JSON](libraries/json/intro.md)
        - [serde(todo)](libraries/json/serde.md)
    - [HTTP](libraries/http/intro.md)
        - [reqwest(todo)](libraries/http/reqwest.md)
    - [命令行解析](libraries/command/intro.md)
        - [structopt(todo)](libraries/command/structopt.md)
        
## 场景模版
- [场景模版 todo](templates/intro.md)
    - [文件操作](templates/files/intro.md)
        - [目录(todo)](templates/files/dir.md)
    - [Http请求(todo)](templates/http/intro.md)


## 附录
- [附录](appendix/intro.md)
    - [A-关键字](appendix/keywords.md)
    - [B-运算符与符号](appendix/operators.md)
    - [C-派生特征derive](appendix/derive.md)
    - [D-Rust版本发布](appendix/rust-version.md)
    - [E-Rust自身开发流程](appendix/rust-dev.md)