# DesignPatterns

> Java版设计模式学习







## 附录

### 附录 A: 常见问题及其解决

#### 无法忽略`*.iml`文件

按照以下命令依次执行即可解决：
```shell
git rm -r --cached .
git add .
git commit -m "delete *.iml"
git push
```