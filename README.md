## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径

- Auto Sign-in run successful on Sat Oct 12 02:35:54 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 01:48:57 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 01:45:53 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 01:44:43 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 01:44:50 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 01:43:27 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 01:43:54 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 01:41:56 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 01:50:52 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 01:46:10 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 01:44:44 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 01:43:11 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 01:43:15 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 01:44:20 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 01:40:51 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 01:49:33 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 01:48:00 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 01:45:48 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 01:44:41 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 01:45:42 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 01:51:31 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 01:42:03 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 01:50:06 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 01:46:19 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 01:42:03 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 01:41:30 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 01:41:40 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 01:42:06 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 01:39:07 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 01:47:00 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 01:44:06 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 01:43:13 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 01:43:02 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 01:43:04 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 01:49:01 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 01:47:14 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 01:53:38 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 01:51:16 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 01:48:58 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 01:47:52 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 01:47:43 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 01:48:56 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 01:44:58 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 01:55:55 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 01:50:59 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 01:49:35 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 01:51:16 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 01:50:49 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 01:50:39 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 01:47:49 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 02:06:34 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 01:54:46 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 01:52:56 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 01:53:24 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 01:53:11 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 01:52:06 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 01:50:57 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 01:59:58 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 01:56:19 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 01:54:41 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 01:53:12 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 01:52:50 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 01:54:11 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 01:49:19 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 01:59:48 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 01:56:33 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 01:52:35 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 01:48:47 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 01:49:31 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 01:44:28 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 01:41:56 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 01:50:33 UTC 2024
- Auto Sign-in run successful on Mon Dec 23 01:45:48 UTC 2024
- Auto Sign-in run successful on Tue Dec 24 01:43:24 UTC 2024
- Auto Sign-in run successful on Wed Dec 25 01:42:12 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 01:42:40 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 01:43:25 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 01:41:13 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 01:51:34 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 01:46:30 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 01:42:57 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 01:51:12 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 01:42:37 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 01:43:39 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 01:41:35 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 01:50:31 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 01:48:14 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 01:44:50 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 01:44:07 UTC 2025
- Auto Sign-in run successful on Thu Jan  9 02:10:58 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 01:46:23 UTC 2025
- Auto Sign-in run successful on Sat Jan 11 01:43:55 UTC 2025
- Auto Sign-in run successful on Sun Jan 12 01:52:30 UTC 2025
- Auto Sign-in run successful on Mon Jan 13 01:48:56 UTC 2025
- Auto Sign-in run successful on Tue Jan 14 01:39:33 UTC 2025
- Auto Sign-in run successful on Wed Jan 15 01:41:19 UTC 2025
- Auto Sign-in run successful on Thu Jan 16 01:40:46 UTC 2025
