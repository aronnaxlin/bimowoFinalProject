# 技术规范

## 分组安排

1. Index 首页
2. Character 角色
3. Introduction 介绍
4. AI 人工智能助手
5. PPT & Documents
6. Universal 统筹

## 命名规范

1. 每个组在命名class, id, 函数名称时，使用驼峰命名法，且在名字前加入组别，如Index组的html容器应为`indexContainer`以方便后期整理

2. 尽量在每一个块之后跟上注释以方便后期文档和整合操作，如：

   ```html
   <div class="indexNavBar"> <!--导航栏容器-->
   ...
   </div>
   ```

## 字体规范

1. 非艺术字使用Arial系列，应在css最顶部包含如下内容

   ```css
   body{
     font-family: Arial, Helvetica, sans-serif;
   }
   ```

2. 艺术字参考如下网站中的字体

   [LOL英雄联盟必备字体](https://www.leagueoflegends.com/en-us/league-of-legends-downloads/)

   并在该样式css下标注font-family，如果有使用，要告知统筹的同学

   ```css
   .indexNavBarContent{
     font-family: BeaufortforLOL-Heavy /* 使用BeaufortforLOL-Heavy字体 */
   }
   ```

## 配色规范

LOL游戏官网使用的配色有

- #CFBC91 金色

- #75BFDB 蓝色

尽量多使用这两个颜色而非页面示例的颜色，以提高网站颜值

## 其他资源规范

1. 可以使用F12扒取英雄联盟官网的素材
2. 同样可以参考[LOL Downloads](https://www.leagueoflegends.com/en-us/league-of-legends-downloads/)
3. 可以访问[Bimowo Final Project](https://github.com/aronnaxlin/bimowoFinalProject/tree/main)仓库获取我陆续扒的资源

## 如果你需要访问GitHub

1. 你可以私下问问会用的舍友怎么访问
2. 使用Steam++的GitHub加速服务[官网](https://steampp.net/)