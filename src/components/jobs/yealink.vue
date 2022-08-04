<template>
    <fragment>
        <div class="content project-content">
            <p class="sec-title"><span class="dot"></span>厦门亿联网络技术股份有限公司（2019.7-2020.10）</p>
            <p class="link">
                <!-- <span class="chenjz-icon">&#xe611;</span> -->
                <span class="project-key-word">项目一：</span>
                <span class="project-item-name">亿联统一通信管理端平台</span>
                <!-- <a target="_blank" href="https://github.com/JAZI6/wyy-music-demo">源代码</a>
                    <a target="_blank" href="https://www.jianshu.com/p/72ea0b8c978d">项目总结</a> -->
            </p>
            <p class="text key-desc-bottom">
                <!-- <span class="chenjz-icon">&#xe60f;</span> -->
                <span class="project-key-word desc-title">概述：</span>
                <span class="key-desc">
                    企业统一通讯解决方案的管理端平台，主要包括视音频会议、IM和PBX配置、设备管理等功能。项目使用vue做前端，express
                    server做为静态资源容器同时也是服务端BFF层，redis做session缓存，nginx做反向代理服务器。
                </span>
            </p>
            <p class="text key-desc-bottom">
                <!-- <span class="chenjz-icon">&#xe60f;</span> -->
                <span class="project-key-word desc-title">职责：</span>
                <span class="key-desc">
                    2.4-2.5版本迭代的项目前端负责人，负责需求评审、讨论、开发，包括任务分配、技术支持、bug修改等相关流程杂活。
                </span>
            </p>
            <p class="text">
                <span class="iconfont"></span>
                <span>
                    <strong>灰度升级</strong>
                    <!-- ：本身服务端express使用了consul进行后端服务发现，于是利用了该逻辑进行相关修改，并且加上nginx的负载均衡粒度调整去实现了灰度。 -->
                </span>
            </p>
            <!-- <p class="text">
                    <span class="iconfont"></span>
                    <span> <strong>部分重构，抽取通用部分：</strong>封装输出管理端常用的组件、业务类、Mixin等 </span>
                </p> -->
        </div>
        <div class="content project-content">
            <p class="link">
                <!-- <span class="chenjz-icon">&#xe611;</span> -->
                <span class="project-key-word">项目二：</span>
                <span class="project-item-name">UC3.X（ PC / Mobile）</span>
                <!-- <a target="_blank" href="https://github.com/JAZI6/wyy-music-demo">源代码</a>
                    <a target="_blank" href="https://www.jianshu.com/p/72ea0b8c978d">项目总结</a> -->
            </p>
            <p class="text key-desc-bottom">
                <!-- <span class="chenjz-icon">&#xe60f;</span> -->
                <span class="project-key-word desc-title">概述：</span>
                <span class="key-desc">
                    一个类C端的团队即时协作应用，内嵌到UME终端中，用户可以各自创建、设置团队，每个团队的功能都包括话题、任务、文件。项目使用
                    vue + element-ui / vant-ui 做前端，socket做即时推送，egg
                    server做为静态资源容器同时也是服务端BFF层，redis做session缓存与事件消息的存储消费，nginx做代理服务器。
                </span>
            </p>
            <p class="text center key-desc-bottom">
                <!-- <span class="chenjz-icon">&#xe60f;</span> -->
                <span class="project-key-word desc-title">职责：</span>
                <span class="key-desc"> 项目中任务模块的开发，包括团队、个人任务。 </span>
            </p>
            <p class="text light-ponint-bottom">
                <span class="iconfont"></span>
                <span>
                    <strong>即时推送</strong>
                    <!-- ：服务端egg通过socket连接redis服务，以redis队列提供的方法，不断地消费其中的消息事件，然后进一步向前端派发事件通知。 -->
                </span>
            </p>
            <p class="text light-ponint-bottom">
                <span class="iconfont"></span>
                <span>
                    <strong>文件批量上传</strong>
                    <!-- ：任务上传附件使用；<strong>前端 </strong>基于HTML
                    file类型的input，和JS相关原生对象以及它们提供的api实现，包括显示上传的进度速率、<strong>并发上传</strong>、终止上传、重新上传；<strong
                        >node端</strong
                    >
                    依赖于相关引入模块完成大文件的 <strong>按流读取分片、管道流上传</strong>。 -->
                    <!-- FileReader、FormData、XMLHttpRequest -->
                    <!-- egg-multipart、stream-to-array、stream-wormhole、formstream -->
                </span>
            </p>
            <p class="text">
                <span class="iconfont"></span>
                <span>
                    <strong>简易富文本编辑框</strong>
                    <!-- ：任务添加评论使用；基于HTML的contenteditable属性，和JS原生对象Selection、Range及其相关api实现 -->
                </span>
            </p>
        </div>
        <div class="content project-content">
            <p class="link">
                <!-- <span class="chenjz-icon">&#xe611;</span> -->
                <span class="project-key-word">项目三：</span>
                <span class="project-item-name">UME扩展应用（ PC / Mobile）</span>
            </p>
            <p class="text key-desc-bottom">
                <!-- <span class="chenjz-icon">&#xe60f;</span> -->
                <span class="project-key-word desc-title">概述：</span>
                <span class="key-desc">
                    一个类C端的拓展应用，内嵌到UME终端中用于丰富其功能如：会议预约、投票、公告、短信等。项目使用 vue +
                    element-ui / vant-ui 做前端，express
                    server做为静态资源容器同时也是服务端BFF层，redis做session缓存，nginx做代理服务器。
                </span>
            </p>
            <p class="text center key-desc-bottom">
                <!-- <span class="chenjz-icon">&#xe60f;</span> -->
                <span class="project-key-word desc-title">职责：</span>
                <span class="key-desc"> 项目中短信模块的重构。 </span>
            </p>
            <p class="text light-ponint-bottom">
                <span class="iconfont"></span>
                <span>
                    <strong>运行、打包前先经过node生成模板</strong>
                    <!-- ：运行、打包时由于已经确定入口、路由以及一些配置差异，所以采取了<strong>执行前替换配置模板中占位符号的方式</strong>来生成当前需要的内容，并替换到关键的依赖文件中，借此完成了<strong
                        >同一项目中可运行 pc / mobile 端功能、</strong
                    ><strong>可单独打包各个功能模块对应 pc / mobile 端的静态资源</strong>。 -->
                </span>
            </p>
            <!-- <p class="text light-ponint-bottom">
                <span class="iconfont"></span>
                <span>
                    <strong>使用adapter、entity、view的方式组织代码：</strong
                    >由adapter层过滤格式化为使用上需要的数据格式，然后在entity层抽取 pc / mobile
                    端通用的业务类，那么view层上我们只需要关注UI上的界面样式和交互逻辑即可。
                    FileReader、FormData、XMLHttpRequest
                    egg-multipart、stream-to-array、stream-wormhole、formstream
                </span>
            </p> -->
            <p class="text">
                <span class="iconfont"></span>
                <span>
                    <strong>消息收发</strong>
                    <!-- ：使用socket通过nginx代理直连后端服务完成实时消息的接收发送。 -->
                </span>
            </p>
        </div>
    </fragment>
</template>

<script>
export default {};
</script>
