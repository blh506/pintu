## 徽章（可以是使用的语言或者其他）  
javascript+css+html  
## 运行环境  
Chrome
## 编译方法  

## 使用方法  
主要函数：  
startAndStop():开始游戏  
reset():重置，将时间步数清空，打乱图片  
change():更换拼图图片  
pointer():向用户提示最小步数和路线  
cheater():用动画形式向用户演示  
judgeHaveSolution()：用逆序数的方式判断当前布局是否有解  
randomLayout()：随机打乱图片  
move(from_number):移动图片  
judge(): 判断是否进行强制交换或是否当前布局成功  
doubleBFS():利用双向广度搜索求解最小步数和最优路线  
enforce():随机选取两个非空白格的小块进行强制调换  
exchange():用户自定义两个小块进行交换
