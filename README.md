CSDN:
账号ID：weixin_47438336
用户名：Wzzz哲


- 安装组件库
    npm install wz-vue-ui

- 全局导入
    import WzUi from 'wz-vue-ui'
    import 'wz-vue-ui/dist/wz-vue-ui.css'

    Vue.use(wzUi)


使用文档：
参数支持：

|:参数名:|	|:参数描述:|	|:参数类型:|	|:默认值:|
|:type:|	|:按钮类型（primary/success/warning/danger/info）:|	|:string:|	|:default:|
|:plain:|	|:是否是朴素按钮:|	|:boolean:|	|:false:|
|:round:|	|:是否是圆角按钮:|	|:boolean:|	|:false:|
|:circle:|	|:是否是圆形按钮:|	|:boolean:|	|:false:|
|:disabled:|	|:是否禁用按钮:|	|:boolean:|	|:false:|
|:icon	|:图标类名:|	|:string:|	|:无:|
事件支持：

|:事件名	|:事件描述:|
|:click	|:点击事件:|
