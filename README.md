基于MVP模式的快速开发框架

主要功能有：网络访问、图片加载、View注解、异步通信等

说明：

网络框架：基于Volley的二次封装.

图片加载：Facebook的Fresco.

View注解：Butterknife.

异步通信：EventBus.

自定义ActionBar.

MVP模式的演示源码, 请查阅LoginActivity.

封装了AbsBaseFragment、AbsBaseFragmentActivity，增加代码的复用性，易于维护、扩展.

自定义了Activity的回退栈, 便于管理Activity，请查阅ActivityManager源码.

基于gradle构建，配置了多渠道打包.

更多集成，敬请期待^_^
