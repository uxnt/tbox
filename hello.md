
## Tbox 数学运算
```tbox
import tbox.console;
func main() {
	num i = 1/4 + 4^2;
	console.print(i);
}
```
打印输出：

```
6
```


## Tbox 判断
```tbox
import tbox.console;
func main() {
    num x = 6;
	if(x > 5) {
		print("Well done!");
	}else{
		print("Maybe some errors!");
	}
}
```
打印输出：
```
Well done!
```


## Tbox 字符串
```tbox
import tbox.console;
func main() {
	string version = "0.0.1";
	string title = "Text Game";
	string text = "那天，这你来玩呢";
	print(text);
	print("你好，好耶，稍等");
	print("稍等...");
}
```
打印输出：

```
那天，这你来玩呢
你好，好耶，稍等
稍等...
```

## TBox 模块系统
```tbox
import tbox.console;
export func add (int a,int b):int{
	return a + b;
}
```

```tbox
import tbox.console;
import module;
func main(){
     console.print(module.add(1,2));
}
```

输出:
```
3
```


## Tbox 关键字

关键字|说明|支持
-|-|-
import|导入|√
0 |  | 
static|静态|√
0 |  | 
num|自动数的别称（int 整型/float 浮点型/double 双精度浮点型） |√
string|字符串|√
func|函数|√
bool|逻辑|√
true|真(1)|√
false|假(0)|√
null|空|√
return|返回|√
0 |  | 
if|如果|√
elif|如果否则|√
else|否则|√
0 |  | 
for|循环/计数循环|√
while|循环/计数循环|√
break|循环结束|√
0 |  | 


## Tbox 版本 0.0.1 关键字

关键字|说明|支持
-|-|-
of|取模块内容|？×
export|导出|？×
