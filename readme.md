# Typecho multi theme typecho多主题切换插件
## 使用方法
安装插件后，在插件的设置中配置参数，一共有三个配置项

### 决定主题切换的参数
如果设置了此项为 `lang` （当作多语言）, 则当 url 的参数中有 `lang` 时，`lang` 的值就是主题的目录名称，此时触发多主题切换，当前的主题会保存在 `__typecho_multi_theme` 的 `cookie` 中
### 默认主题
如果没有选择过主题，首次进入时使用此主题，这里的配置高过系统的自身主题配置
### 允许切换的主题
也许你有几十个主题，但只想切换其中几种，在这里勾选即可



