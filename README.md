# 入门

Rxjs是一个库，它通过使用observable序列来编写异步和机遇时间的程序。它提供了一个核心类型Observable，附属类型（Observer、Schedulers、Subject）和受\[Array\#extras\]启发的操作符（map、filter、reduce、every 等等），这些数组操作符可以把异步事件作为集合来处理。

ReactiveX结合了观察者模式、迭代器模式和使用集合的函数式编程，以满足以一种理想方式来管理实序列所需要的一切。

在RxJS中用来解决异步事件管理的基本概念是：

* Observable: 表示一个概念。这个概念是一个可调用未来值或事件的集合。
* Observer:一个回调函数的集合，它知道如何去监听由Observable提供的值。
* Subscription:采用函数式编程风格的纯函数，使用像map、filter、concat、flatMap等这样的操作符来处理集合。
* Subject: 相当于EventEmitter，并且是将值或者事件多路推送给多个Observer的唯一方式。
* Scheduler: 用来控制并发并且是中央集权的调度员，允许我们在发生计算时进行协调，例如setTimeout或requestAnimationFrame或其他



## 



