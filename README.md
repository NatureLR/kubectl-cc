# kubectl-cc

kubectl cc (change cluster)

[![asciicast](https://asciinema.org/a/ApsYXdOC0iNLPVhghcds9jOBS.svg)](https://asciinema.org/a/ApsYXdOC0iNLPVhghcds9jOBS)

- 将k8s配置文件放在`.kube/configs`下保存为xxx.yaml文件

- 将本脚本添加可执行权限放到path下即可使用kubectl cc 快速通过切换配置文件来切换集群

- 模糊搜索需要安装[fzf](https://github.com/junegunn/fzf)

## 安装

```shell
git clone https://github.com/NatureLR/kubectl-cc

cd kubectl-cc

mv kubectl-cc /usr/local/bin/
```
