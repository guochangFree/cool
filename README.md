# my-rpc
自定义rpc框架实现。
先说点其他的 java的反射
java.lang.reflect 包下 interface Member 类

![Member子类](https://github.com/guochangFree/my-rpc/raw/master/image/member1.png)

在Modifier类中 定义了一些常量 
 public static final int PUBLIC           = 0x00000001;
 
 public static final int PRIVATE          = 0x00000002;
 
 public static final int STATIC           = 0x00000008;
 
 public static final int FINAL            = 0x00000010;
 
 public static final int SYNCHRONIZED     = 0x00000020;
 ...
  
 int mod Member.getModifers(); // 返回上面的int值
 Modifers.isPublic(int mod); // 根据mod值判断是否为public
 还有其他一些方法：
 ![Member子类](https://github.com/guochangFree/my-rpc/raw/master/image/modifers.png)
 
 
 
 
 
  
