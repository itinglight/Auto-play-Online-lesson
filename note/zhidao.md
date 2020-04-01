​																				



[返回首页](https://github.com/kjyds/Auto-play-Online-lesson)

# **智慧树（手机app名称：知到）刷课教程**

## 第一步：登录[智慧树官网](https://onlineh5.zhihuishu.com/onlineWeb.html#/studentIndex)

## **第二步：**进入你要刷的课程，并播放。

## 第三步：按 F**12**  进入网页调试

## 第四步：复制第五步中的代码，粘贴到下图标记:two:的地方

![](C:\Users\bin07\Desktop\kejiyds\Auto-play-Online-lesson\img\fist-1.jpg)

## 第五步：选择下方合适的代码

**代码一**： 1.5倍播放速度+静音

```js
document.querySelector('.volumeIcon').click();//静音处理
document.getElementsByClassName('speedTab15')[0].click();//1.5倍速播放
setInterval(function(){//每3秒执行一次
        //判断播放进度是否到达100%
        if(document.getElementsByClassName('passTime')[0].style.width == '100%'){
            setTimeout(function(){
                //用js执行“下一集”按钮的点击事件，延迟1s执行
                document.getElementById('nextBtn').click();
         },1000);
        setTimeout(function () {
                //延迟4秒执行调节播放速率
            document.querySelector('.volumeIcon').click();
            document.getElementsByClassName('speedTab15')[0].click();//设置播放速率为1.5倍速
            },4000)
        }
             //更多代码关注微信公众号：科技优等生

     if(document.getElementsByClassName('bigPlayButton pointer')[0].style.display=='block')
        {//用于检测答题弹窗是否出现，并将其关闭
        document.getElementsByClassName('topic-item')[0].click()//只选A，弹窗题目不影响成绩，就不纠结选的对不对了
        document.getElementsByClassName('el-dialog__footer')[5].click()
        document.getElementsByClassName('el-dialog__headerbtn')[5].click()//点击按钮关闭
        document.getElementsByClassName('playButton')[0].click()//点击播放继续
        }
 
},3000);
 
```

**代码二**：1.25倍播放速度+不静音（适合刷客）

```js
document.getElementsByClassName('speedTab10')[0].click();//1.25倍速播放
setInterval(function(){//每3秒执行一次
        //判断播放进度是否到达100%
        if(document.getElementsByClassName('passTime')[0].style.width == '100%'){
            setTimeout(function(){
                //用js执行“下一集”按钮的点击事件，延迟1s执行
                document.getElementById('nextBtn').click();
         },1000);
        setTimeout(function () {
                //延迟4秒执行调节播放速率
            document.querySelector('.volumeIcon').click();
            document.getElementsByClassName('speedTab10')[0].click();//设置播放速率为1.25倍速
            },4000)
        }
             //更多代码关注微信公众号：科技优等生

     if(document.getElementsByClassName('bigPlayButton pointer')[0].style.display=='block')
        {//用于检测答题弹窗是否出现，并将其关闭
        document.getElementsByClassName('topic-item')[0].click()//只选A，弹窗题目不影响成绩，就不纠结选的对不对了
        document.getElementsByClassName('el-dialog__footer')[5].click()
        document.getElementsByClassName('el-dialog__headerbtn')[5].click()//点击按钮关闭
        document.getElementsByClassName('playButton')[0].click()//点击播放继续
        }
 
},3000);
 
```

**代码三**：1.5倍播放速度+不静音（适合刷客）

```js
document.querySelector('.volumeIcon').click();//静音处理
document.getElementsByClassName('speedTab15')[0].click();//1.5倍速播放
setInterval(function(){//每3秒执行一次
        //判断播放进度是否到达100%
        if(document.getElementsByClassName('passTime')[0].style.width == '100%'){
            setTimeout(function(){
                //用js执行“下一集”按钮的点击事件，延迟1s执行
                document.getElementById('nextBtn').click();
         },1000);
        setTimeout(function () {
                //延迟4秒执行调节播放速率
            document.querySelector('.volumeIcon').click();
            document.getElementsByClassName('speedTab15')[0].click();//设置播放速率为1.5倍速
            },4000)
        }
             //更多代码关注微信公众号：科技优等生

     if(document.getElementsByClassName('bigPlayButton pointer')[0].style.display=='block')
        {//用于检测答题弹窗是否出现，并将其关闭
        document.getElementsByClassName('topic-item')[0].click()//只选A，弹窗题目不影响成绩，就不纠结选的对不对了
        document.getElementsByClassName('el-dialog__footer')[5].click()
        document.getElementsByClassName('el-dialog__headerbtn')[5].click()//点击按钮关闭
        document.getElementsByClassName('playButton')[0].click()//点击播放继续
        }
 
},3000);
 
```

[返回首页](https://github.com/kjyds/Auto-play-Online-lesson)