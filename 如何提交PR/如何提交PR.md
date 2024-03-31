# **提交PR**



# 先fork那个项目

# PULL拉取最新代码

## 再复制项目地址

![image-20220317180325083](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317180325083.png)

## 在文件夹中打开GIT

![image-20220317180504096](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317180504096.png)

## 在命令行中输入克隆代码

```
git clone https://github.com/WLHSDXN/HowToCook.git

```

![image-20220317180623567](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317180623567.png)

## 等待克隆完成，可以在本地打开项目

![image-20220317181000023](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317181000023.png)

![image-20220317181016537](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317181016537.png)



# 创建新分支

## 切换到自己的新分支

```
git checkout -b newVegetable
```

![image-20220317181741198](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317181741198.png)

接下来就可以修改本地文件了！

# 提交到远程仓库

```
 git commit -a
```

![image-20220317183317169](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317183317169.png)

```
git push -u origin newVegetable
```

![image-20220317202129777](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317202129777.png)

# 提交PR（）

## 复制这个地址

```
https://github.com/WLHSDXN/HowToCook/pull/new/newVegetable
```

![image-20220317202255687](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317202255687.png)

## 在浏览器中打开

![image-20220317203819329](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317203819329.png)

## 点击创建

![image-20220317203913122](D:/%E7%8B%AC%E7%AB%8B%E9%A1%B9%E7%9B%AE/GIT/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR/%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4PR.assets/image-20220317203913122.png)

失败原因（这个github仓库有严格的检查机制，提交的代码未通过自动检查）

## 与主分支无冲突（在自己的github没有设置自动检查机制）

![image-20220612181306841](如何提交PR.assets/image-20220612181306841.png)

## 点击merge

![image-20220612181602427](如何提交PR.assets/image-20220612181602427.png)

## 成功提交！

![image-20220612181636084](如何提交PR.assets/image-20220612181636084.png)