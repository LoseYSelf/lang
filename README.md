from https://github.com/DoctorWkt/acwj



data.h PutBack作用 
   在scan.cpp获取数据下标后 会再次取一个字符
   如果不是数字类型 就需要保留这个字符 PutBack作用就是用来保留这个字符
   留到下次判断的时候继续使用


!!!没办法直接调用其他cpp的方法 只能通过.h文件定义然后其他cpp方法实现定义的方法

通过引入.h文件来调用方法