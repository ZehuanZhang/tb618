### tb618自动领瞄币auto.js脚本
**仅用于个人学习，请勿作为非法工具使用**

**使用技巧**

@Marcusias 提出通过远程拉取页面，实现自动使用最新脚本的方法，若能够正常连接githubusercontent.com，可以考虑直接在autojs中使用以下代码运行脚本：
```
eval(http.get('https://raw.githubusercontent.com/ZehuanZhang/tb618/master/tb618.js').body.string());
```
若不能够正常使用github，或部分github连接受限，请考虑使用[gitee](https://gitee.com/mimr/tb618)上的镜像项目：
```
eval(http.get('https://gitee.com/mimr/tb618/raw/master/tb618.js').body.string())
```
**请注意：建议使用autojs 4.0以上的版本运行**

1. 使用本脚本前请安装auto.js软件
2. 下载该脚本并导入auto.js中
3. 确认已安装手机淘宝客户端
4. 在auto.js中运行本脚本

**特别说明**

**本脚本不掺杂任何协助点击、分享等内容，任何人可以自由使用，若移植或分享，请保留本脚本中的版权说明内容，尊重劳动成果**

**活动期间，由于界面经常变动，可能旧的脚本会失效，若想良好使用脚本功能，请随时关注更新**

-----
**更新说明**

> 最新更新

2020/06/13 Update3: 完全取消按钮进入活动主界面的操作，只使用搜索方案 #6

> 历史更新

2020/06/13 Update2: 加入代码版本号显示

2020/06/13 Update1: 同步首页层次更新

2020/06/12 Update1: 改进农场操作，改进部分判断

2020/06/12 Update1: 更新列表元素判断逻辑

2020/06/11 Update1: 修复部分错误

2020/06/10 Update1: 领喵币逻辑更新，支持多个位置进入618界面，新增多个窗口定位方法

2020/06/09 Update1: 当且仅当使用活动按钮进入界面失败时，尝试使用搜索方法进入618活动界面

2020/06/04 Update4: 支持手动关闭无障碍模式

2020/06/04 Update3: 部分优化，支持农场操作（最好手动操作使其超过2级）

2020/06/04 Update2: 支持去观看操作

2020/06/04 Update1: 修复不能正常进入领瞄币的问题，修复领取祝福的字符错误

2020/06/03 Update1: 若当天首次进入，支持自动领取祝福

2020/06/02 Update2: 修复部分情况下无法正常进入领瞄币界面的错误

2020/06/02 Update1: 优化部分操作逻辑，修复部分错误

2020/06/01 Update2: 再次优化按钮点击逻辑（淘宝最近页面更新的较快，经常有变动）

2020/06/01 Update1: 优化按钮点击进入逻辑

2020/05/31 Update2: 适配新活动布局，避免淘宝骚操作，导致返回主界面中断领瞄币，基本可以全自动完成大多数领瞄币操作

2020/05/31 Update1: 支持从多个位置开始领瞄币，支持自动判断浏览任务是否结束

2020/05/30 Update1: ~可自定义滑动浏览后的等待时间~（已在后续更新中删除）

2020/05/29 Update1: 首次上传脚本，可自动领瞄币
