<template>
    <div class="left">
        <div class="logo">
            <div class="avator">
                <img src="../assets/logo.jpg" alt />
            </div>
            <div class="name">
                <p>陈嘉志</p>
                <p class="position">求职意向：前端开发岗位</p>
            </div>
        </div>
        <div class="info">
            <p class="title-top">
                <span class="title-cn">教育背景</span>
            </p>
            <p>
                <span class="icon">&#xe62b;</span>
                <span class="title">个人信息：</span>
                <span class="text">男 / 25岁</span>
            </p>
            <p>
                <span class="icon">&#xe68d;</span>
                <span class="title">学历相关：</span>
                <span class="text">福州大学（211）</span>
                <br />
                <span class="text" style="padding-left: 117px">计算机科学与技术</span>
                <span class="text" style="padding-left: 117px">CET-4</span>
            </p>
            <p>
                <span class="icon">&#xe67b;</span>
                <span class="title">就读时间：</span>
                <span class="text">2015.7-2019.7</span>
            </p>
            <p>
                <span class="chenjz-icon">&#xe63d;</span>
                <span class="title">获奖经历：</span>
                <span class="text">一次国家奖学金</span>
                <span class="text" style="padding-left: 117px">多次校奖学金</span>
                <span class="text" style="padding-left: 117px">专业排名前35%</span>
            </p>
        </div>
        <div class="contact">
            <p class="title-top">
                <span class="title-cn">联系方式</span>
            </p>
            <p>
                <span class="icon">&#xe6c8;</span>
                <span class="title">电话：</span>
                <span class="text">13110519029</span>
            </p>
            <p>
                <span class="icon">&#xe61d;</span>
                <span class="title">邮箱：</span>
                <span class="text">2322492240@qq.com</span>
            </p>
        </div>
        <!-- <div class="link">
      <p class="title-top">
        <span class="title-cn">相关链接</span>
      </p>
      <p>
        <a href="https://github.com/JAZI6" target="_blank" class="icon">&#xe69f;</a>
        <a href="https://github.com/JAZI6" target="_blank" class="title">GitHub</a>
      </p>
      <p>
        <a href="https://www.jianshu.com/u/4c2ab03a73e4" target="_blank" class="icon">&#xe66a;</a>
        <a href="https://www.jianshu.com/u/4c2ab03a73e4" target="_blank" class="title">个人简书博客</a>
      </p>
    </div> -->
        <div class="hobby">
            <p class="title-top">
                <span class="title-cn">关于我</span>
            </p>
            <p>1.较强的学习能力</p>
            <p>2.良好的协作能力</p>
            <p>3.较好的抗压能力，独立承担工作</p>
            <p>4.轻微强迫症，注意代码书写的规范</p>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.left {
    width: 320px;
    padding-top: 30px;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    .logo {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        .avator {
            width: 170px;
            height: 170px;
            overflow: hidden;
            border-radius: 50%;
            border: 2px solid #fff;
            img {
                width: 166px;
                height: 220px;
                margin-top: -10px;
            }
        }
        .name {
            margin-top: 10px;
            text-align: center;
            p:nth-child(1) {
                font-size: 32px;
                letter-spacing: 10px;
                font-weight: 500;
            }
        }
        .position {
            font-size: 20px;
            letter-spacing: 2px;
        }
    }
    .info,
    .contact,
    .link,
    .hobby {
        width: 100%;
        text-align: left;
        margin-top: 30px;
        p {
            margin-bottom: 5px;
            letter-spacing: 1px;
            .title {
                font-weight: 700;
                letter-spacing: 1px;
            }
            .icon,
            .chenjz-icon {
                font-size: 20px;
            }
        }
        .title-top {
            letter-spacing: 1px;
            margin-bottom: 10px;
            .title-cn {
                font-size: 24px;
            }
        }
    }
    .link {
        p {
            display: flex;
            align-items: center;
            margin: 0;
            .icon {
                font-size: 24px;
                margin-right: 5px;
            }
        }
    }
    .code {
        margin-top: 30px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        p {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 10px;
        }
        img {
            width: 150px;
            height: 150px;
        }
    }
}
</style>
