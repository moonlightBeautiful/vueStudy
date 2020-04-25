#vue学习
1.简介
    是一套构建用户界面的渐进式框架，非常容易学习。
    就一个js文件。
    渐进式：只是个轻量视图而已，只做了自己该做的事，没有做不该做的事，仅此而已。可以用一部分，可以全部用。
    Vue 不支持 IE8 及以下版本，因为 Vue 使用了 IE8 无法模拟的 ECMAScript 5 特性。但它支持所有兼容 ECMAScript 5 的浏览器。
2.使用工具webstorm
	JavaScript 开发工具，“Web前端开发神器”、“最智能的JavaScript IDE”等
    一路安装，注册码破解。
    优化：
        搜索 unknown HTML tag attributes,将下面的指令复制到点开的窗口里
        v-text
        
        v-html
        
        v-once
        
        v-if
        
        v-show
        
        v-else
        
        v-for
        
        v-on
        
        v-bind
        
        v-model
        
        v-ref
        
        v-el
        
        v-pre
        
        v-cloak
        
        v-on:click
        
        v-on:keyup.enter
        
        v-on:keyup
        
        @click
        
        @change
        
        number
        
        debounce
        
        transition
        
        :is
3.helloVue
	1.引入vue的js文件，就一个
	2.
4.核心原理
    mvvm设计模式 
    核心就是 ViewModel（也就是vue） 里面有DOM监听以及数据绑定。
    Model也就是data里定义的
    View是页面数据展示 
5.安装谷歌调试工具vue devtools
    1.安装npm
        安装node.js就好。一路安装
    2.安装vue devtools
        1.下载 git clone https://github.com/vuejs/vue-devtools.git
        2.安装vue devtools 
            进入到vue devtools目录下的cmd 2种方式 1.ctrl+shift+右键 2.在地址栏直接输入cmd
            安装  npm instal
            修改vue devtools目录\shells\chrome\manifest.json文件 把"persistent":false改成true
            编译  npm run build
        3.Chrome插件
            Chrome浏览器 >  拓展程序 > 点击加载已解压程序按钮, 
            选择vue devtools目录\shells\chrome
        注意：
            1.页面引入vue.js才能使用vue-devtools，js文件名要叫做vue.js