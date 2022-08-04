<template>
    <fragment>
        <div class="content project-content">
            <p class="sec-title"><span class="dot"></span>厦门铃盛软件有限公司（2020.10-至今）</p>
            <p class="link">
                <span class="project-key-word">项目：</span>
                <span class="project-item-name">Ringcentral Web管理端平台</span>
            </p>
            <p class="text key-desc-bottom">
                <span class="project-key-word desc-title">概述：</span>
                <span class="key-desc">
                    服务管理端平台，主要包括用户管理，PBX配置、设备管理，视频会议，套餐购买等功能。项目使用React做前端，nginx
                    server作为静态资源容器运行。
                </span>
            </p>
            <p class="text center key-desc-bottom">
                <span class="project-key-word desc-title">职责：</span>
                <span class="key-desc"> 20.4-22.4版本项目开发者 </span>
            </p>
            <p class="text">
                <span class="iconfont"></span>
                <span>
                    <strong>灰度升级：</strong
                    >本身服务端express使用了consul进行后端服务发现，于是利用了该逻辑进行相关修改，并且加上nginx的负载均衡粒度调整去实现了灰度。
                </span>
            </p>
        </div>
    </fragment>
</template>

<script>
export default {};
</script>
