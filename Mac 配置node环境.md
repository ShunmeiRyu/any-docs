# Mac 配置 node 环境

## nodebrew 安装
```
brew install nodebrew
nodebrew setup
```

## nodebrew 的 path 追加
```
echo 'export PATH=$HOME/.nodebrew/current/bin:$PATH' >> ~/.zshrc
source ~/.zshrc
```

## Node 可用版本查看
```
nodebrew ls-remote
```

## 安装指定版本
```
mkdir -p ~/.nodebrew/src
nodebrew install v18.15.0
```

## 查看已安装版本
```
nodebrew ls
```

## 当前版本切换
```
nodebrew use v18.15.0
```

## npm 安装
```
npm install -g npm
```

