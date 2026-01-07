# C++ 第一个代码：你好世界
```
#include <iostream>
    using namespace std;
int main()
{
   cout << "hello world" << endl;
   return 0;
}
```
# 注释方法：
## 1.单行注释：使用 //  ，可放在该行代码前头或尾巴处
```
#include <iostream>
    using namespace std;

int main()
{
   // 这是一个注释
   cout << "Hello world";
   return 0;
}
```
```
#include <iostream>
    using namespace std;

int main()
{
   cout << "Hello World!"; // 输出 Hello World!

   return 0;
}
```
## 2.多行注释：使用 /*   */  ，要注释掉的部分放在中间
```
#include <iostream>
    using namespace std;

int main()
{
   /* 这是注释 */

   /* C++ 注释可以
      跨行
    */
   cout << "Hello world";
   return 0;
}
```
