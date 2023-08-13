# homebrew-person
## 新增
- maven@3.5
## 安装
```
brew tap AlanSune/homebrew-person
# you can install maven@3.5
# brew install maven@3.5
```
## jenv配置
```
brew install jenv
echo 'export PATH="$HOME/.jenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(jenv init -)"' >> ~/.zshrc

# Set ${JAVA_HOME} by jenv
jenv enable-plugin export
exec $SHELL -l
```
