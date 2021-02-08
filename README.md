# 常用js插件库

#移动端调试H5页面插件

    一、vconsole 插件
    
    1、CDN方式引入
    引入 <script src="https://cdn.bootcss.com/vConsole/3.3.4/vconsole.min.js"></script>
    初始化 var vConsole = new VConsole(); console.log('Hello world');
    
    2、 npm install vconsole
        或者
        cnpm install vconsole
        或者
        yarn add vconsole
 
        然后设置个环境变量作为区分线上线下环境，比如：
        import VConsole from 'vconsole';
        const isDebug = true;
        // 本地开发调试注入vConsole
        if (isDebug) {new VConsole();}

    
    