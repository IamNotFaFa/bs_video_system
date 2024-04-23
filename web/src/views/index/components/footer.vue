<template>
  <div class="footer-view">
    <div class="foot-link-box flex-view">
      <a href="https://github.com/IamNotFaFa/video_system/issues" class="foot-link" target="_blank">系统文档</a>
      <div class="link-split"></div>
      <a href="/admin" class="foot-link" target="_blank">后台管理</a>
      <div class="link-split"></div>
      <a href="" class="foot-link" target="_blank">关于我们</a>
    </div>
    <div class="footer-infos">
      <span>
        <a style="color: rgb(174, 174, 174);">学校：湖南工程职业技术学院</a>
      </span>
      <span>&nbsp;&nbsp;班级：2021031102&nbsp;&nbsp;学号：202003110233&nbsp;&nbsp;姓名：贺义花</span>
    </div>
    <div class="address">毕设选题：校园视频点播系统设计与实现&nbsp;&nbsp;指导老师：唐绍华</div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {}
  },
  methods: {}
}
</script>

<style scoped lang="less">
.flex-view {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.footer-view {
  max-width: 1108px;
  margin: 0 auto;
  padding: 24px 0 20px 54px;

  .foot-link-box {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    overflow: hidden;
    margin: 24px auto 16px;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    .foot-link {
      margin: 0 16px;
      color: #2a4f88;
    }
    a {
      background-color: transparent;
      text-decoration: none;
      color: var(--mid-blue);
    }
  }

  .footer-infos {
    height: 16px;
    line-height: 16px;
    font-size: 12px;
    padding-left: 63px;
    color: #aeaeae;
    margin-top: 16px;
    text-align: center;
  }
  .address {
    text-align: center;
    height: 16px;
    line-height: 16px;
    font-size: 12px;
    color: #aeaeae;
    margin-top: 8px;
  }
}
</style>
