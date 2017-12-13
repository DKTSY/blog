  ### 用Java语言来实现ipv4代码识别过程
 
  ### Java中int，Integer区别是什么？
   > - int是基本类型，Integer是对象类型。
   > - 函数调用时，int是传递值，Integer传递引用。
   > - 初始化时，int为0，Integer初始化为null。
   > - int装箱后获得Integer，Integer拆箱后得int。装箱与拆箱有缓存，JVM默认缓存-128~127范围内的，缓存最大值可以通过-XX:AutoBoxCacheMax参数调整。
   
  ### Java多线程中，synchronized和Lock有什么异同点；
  > - 都是用来解决多线程中[race condition](https://en.wikipedia.org/wiki/Race_condition)的问题。
  > - synchronized是Java关键字，可以修饰方法及代码块。修饰静态方法或代码块时，锁的对象是当前类的class对象，非静态时则是当前对象。
  > - Lock是Java1.5后的一个接口，JDK中的实现有ReentrantLock、ReentrantReadWriteLock、StampedLock。
  > - synchronized是隐式锁，Lock是显式锁，需要显式获取和释放。

|功能| synchronized|ReentrantLock|ReentrantReadWriteLock|StampedLock|
|----|----|----|----|----|
|支持重入|是|是|是|是|
支持乐观锁|否|||


 ###java中锁的种类各自使用的场景；
 
 ###java内存泄漏的定位与分析
 
 ###jdk7和jdk8中有哪些新特性；jdk9又有哪些值得期待的特性；
 
 
