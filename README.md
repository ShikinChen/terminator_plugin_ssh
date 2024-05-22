### 系统:Ubuntu 22.04
### Terminator版本:2.1.3
### 对[my-terminator的ssh_connect_keyring.py插件](https://github.com/ANBUZHIDAO/my-terminator)在Ubuntu 22.04进行适配使用方法是一样
### 依赖安装

```shell
sudo apt -y install sshpass gir1.2-vte-2.91
pip3 install keyring
pip3 install PyGObject
pip3 install PyGObject-stubs
```
### 插件安装
复制 ssh_connect_keyring.py 到 ~/.config/terminator/plugins
```shell
mkdir -p ~/.config/terminator/plugins
cp ssh_connect_keyring.py ~/.config/terminator/plugins
```