##### webrtc channel connection

```tree
--
 | offer 
 | answer
```



1. 先打开 offer 页面，会生成一个信令（在控制台可以看到）
2. 将 offer 生成的信令 复制粘贴到 answer 源码中（具体修改的位置可参考源码）
3. 打开 answer 页面，会生成一个 answer 的信令（在控制台）
4. 切换到 offer 页面，在控制台中设置 answer 的信令
5. 在 offer 页面，在控制台中 执行发送
6. 如果没什么错误，就可以看到结果了
