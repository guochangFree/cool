# my-rpc
自定义rpc框架实现。
先说点其他的 java的反射
java.lang.reflect 包下 interface Member 类

![Member子类](https://github.com/guochangFree/my-rpc/raw/master/image/member1.png)

在Modifier类中 定义了一些常量 
 public static final int PUBLIC           = 0x00000001;
 public static final int PRIVATE          = 0x00000002;
 public static final int PROTECTED        = 0x00000004;
 public static final int STATIC           = 0x00000008;
 public static final int FINAL            = 0x00000010;
 public static final int SYNCHRONIZED     = 0x00000020;
 public static final int VOLATILE         = 0x00000040;
 public static final int TRANSIENT        = 0x00000080;
 public static final int NATIVE           = 0x00000100;
 public static final int INTERFACE        = 0x00000200;
 public static final int ABSTRACT         = 0x00000400;
 public static final int STRICT           = 0x00000800;
 ...
  
 int Member.getModifers(); // 返回上面的int值
 例如
 Feild 类 
 public int getModifiers() {
    return modifiers;
 }
 
 
 
 
 
  
