<template>
  <main class="container">
    <style>
      {{styleShowText}}
    </style>
    <div class="fixed opacity-25 w-full h-full z-10 overflow-auto code-show">
      <pre class="block w-full h-full">
        {{ styleShowText }}
      </pre>
    </div>
    <article>
      <section class="intr">
        <h3>
          <img src="/images/me.png" alt="赖钟杰" class="block" />
        </h3>
        <ul>
          <li>
            <h1>赖钟杰</h1>
            <p>路在前面，永远要往前走，即使回头也只能作为回顾过往</p>
          </li>
          <li>
            <dl class="tags">
              <dd>重视原则</dd>
              <dd>开朗乐观</dd>
              <dd>积极向上</dd>
              <dd>90后</dd>
              <dd>佛系</dd>
            </dl>
          </li>
          <li>
            <dl>
              <dd>26岁</dd>
              <dd>汉族</dd>
              <dd>深圳市</dd>
              <dd>4年工作经验</dd>
              <dd>15815295342</dd>
              <dd>tuvs85@gmail.com</dd>
            </dl>
          </li>
        </ul>
      </section>
      <section class="career">
        <h3>求职意向</h3>
        <ul>
          <li>
            <dl>
              <dd>Web前端开发</dd>
              <dd>全职</dd>
              <dd>广东深圳</dd>
              <dd>薪酬面谈</dd>
              <dd>到岗时间待定</dd>
            </dl>
          </li>
        </ul>
      </section>
      <section class="background">
        <h3>教育背景：</h3>
        <ul>
          <li>
            <dl>
              <dd>华南理工大学（非统招）</dd>
              <dd>计算机应用</dd>
              <dd>大专</dd>
              <dd><time>2017.09-2020.01</time></dd>
              <dd>状态：已毕业</dd>
            </dl>
            <p>学信网可查</p>
          </li>
          <li>
            <dl>
              <dd>华南理工大学（非统招）</dd>
              <dd>计算机科学</dd>
              <dd>本科</dd>
              <dd><time>2020.03-2022.06</time></dd>
              <dd>状态：在读</dd>
            </dl>
            <p>学信网可查</p>
          </li>
        </ul>
      </section>
      <section class="work">
        <h3>工作经验：</h3>
        <div>
          <dl>
            <dt>
              <span>深圳市云逐科技有限公司</span>
              <span>Web前端开发</span>
              <span><time>2018.06-至今</time></span>
            </dt>
            <dd>
              ●
              项目提案时架构vue底层框架，编写各种功能组件，根据交互稿需求实现产品交互功能。
            </dd>
            <dd>
              ●
              配合后端实现数据交互，通过Api请求对后端返回数据进行处理和分配渲染，进行应用及系统整合，提升用户体验，解决各种兼容性问题；
            </dd>
            <dd>
              ●
              依据产品需求提高产品质量与用户体验，完成高质量的前端开发与维护，负责项目上的前端Bug修复，以及产品、运营需求增加的开发；
            </dd>
            <dd>● 项目提案时产品讨论交互稿，完善用户体验。</dd>
          </dl>
          <dl>
            <dt>
              <span>深圳市微聚科技有限公司</span>
              <span>Web前端开发</span>
              <span><time>2016.09-2018.5</time></span>
            </dt>
            <dd>
              ●
              根据UI设计图，快速运用HTML5、CSS3、JS等专业技术快速高效实现前端页面高质量语义化的网站架构以及页面实现，并且使用javascript编写交互功能，实现页面高质量的输出；
            </dd>
            <dd>
              ●
              运用AJAX通过Api对后端返回数据进行处理和分配和渲染后台数据，提升用户体验，解决各端的兼容性问题；
            </dd>
            <dd>
              ●
              依据产品需求提高产品质量与用户体验，完成高质量的前端开发与维护，负责一些项目的前端Bug修复，以及客户需求增加的开发
            </dd>
          </dl>
        </div>
      </section>
      <section class="project">
        <h3>项目经验：</h3>
        <div class="box">
          <dl>
            <dt>
              <span>Coindy交易所web端</span>
              <span>Web前端开发</span>
              <span><time>2019.6-2020.4</time></span>
            </dt>
            <dt>
              项目简介：
            </dt>
            <dd>Coindy区块链交易所</dd>
            <dd>● Coindy2.0 空投业务官网延伸业务</dd>
            <dd>● 规划作为东南亚区块链交易所运营</dd>
            <dt>项目构建：</dt>
            <dd>
              ● 使用vue-cli
              2版本快速搭建项目，根据业务需求分离官网端、h5端、业务端，大量使用es6，模块化分离复用、优化前端加载性能、项目开发周期中封装了一些npm包
            </dd>
            <dd>● 使用ant蚂蚁金服vue-design版Ui框架。</dd>
            <dd>● 高精度资产数据处理。</dd>
          </dl>

          <dl>
            <dt>
              <span>Coindy交易所APP(RN版)</span>
              <span>Web前端开发</span>
              <span><time>2019.9-2020.5</time></span>
            </dt>
            <dt>项目简介：</dt>
            <dd>
              Coindy区块链交易所App (react-native版) 作为交易所web版使用。
            </dd>
            <dt>项目构建：</dt>
            <dd>
              ●
              使用react-native0.59搭建，底层框架分别使用native-base、rn-ant-design作为ui框架，使用react-navigation作为路由功能、react-redux作为全局状态管理器、按项目需求分别实现ios、android原生k线图封装rn使用（原生（object-c，android）代码为github开源下载修改使用）
            </dd>
            <dd>
              ● 从纯前端开发到学习react-native
              App开发、接触一些原生（object-c，android）实现逻辑、封装一些react-native使用的npm包。
            </dd>
            <dd>● 复用性组建模块封装。</dd>
          </dl>
        </div>
      </section>
      <section class="self-evaluation">
        <h3>自我评价：</h3>
        <ul>
          <li>
            本人性格开朗，爱好运动，工作经历丰富，对Web前段开发有一定经验。
          </li>
          <li>
            对编程行业非常的热爱，闲余时间不断通过书籍、视频学习最新前沿的技术。
          </li>
          <li>
            多年的丰富经验让我能快速的完成项目需求和开发，工作执行力强，责任心强，善于思考和总结,乐观接受正确的批评。
          </li>
        </ul>
      </section>
      <section class="skill-list">
        <h3>技能列表：</h3>
        <ul>
          <li>
            ● 能够编写语义化的HTML，模块化的CSS，完成响应式、自适应等常见布局；
          </li>
          <li>
            ● 熟悉HTML5新增的API，熟练使用CSS3的过渡/变换/媒体查询等新特性；
          </li>
          <li>● 熟悉JavaScript的基本语法，了解原生的DOM和BOM；</li>
          <li>● 了解Ajax，能够基于Ajax实现数据异步加载；</li>
          <li>● 了解并会使用CSS预处理器SASS、LESS；</li>
          <li>● 掌握常见的前端兼容处理、性能优化知识和技巧；</li>
          <li>● 熟悉使用Es6新语法。</li>
          <li>● 熟练使用正则完成各种场景判断。</li>
          <li>● 熟悉MVVM（Vue）、熟练Vue-SSR(Nuxt)开发，并且熟练的使用。</li>
          <li>● 对后端nodeJs、python、mongoDB语言有非常深的兴趣。</li>
        </ul>
      </section>
      <section class="gallery">
        <h3>
          作品展示：
        </h3>
        <ul class="link">
          <li>
            <a href="https://github.com/tuvs85"> https://github.com/tuvs85</a>
          </li>
          <li>
            <a href="https://debug.ltd"> https://debug.ltd</a>
          </li>
        </ul>
      </section>
    </article>
  </main>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '~/components/Logo.vue'

export default Vue.extend({
  components: {
    Logo
  },
  data() {
    return {
      styleShowIndex: 0,
      styleShowText: '',
      styleText: `
* {
  transition: all 0.5s;
  color: #333;
}
img {
  display: block;
  transition: all 0.5s;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  font-size: 12pt;
}
/*关于我*/
.intr {
  display: flex;
  margin-bottom: 40px;
}
.intr h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.intr img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
}
.intr h1 {
  font-size: 20pt;
  font-weight: bold;
}
.intr dl {
  width: 100%;
  margin-bottom: 40px;
}
.intr dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.intr .tags {
}
.intr .tags dd {
  width: 90px;
  height: 30px;
  text-align: center;
  padding: 2px 10px;
  margin-right: 10px;
  border-radius: 14px;
  border: 1px solid #333;
}
.intr li {
  margin-bottom: 8px;
}
.intr li dl {
  display: flex;
  margin-bottom: 0;
}
.intr li dd {
  margin-right: 20px;
}
/*关于我 end*/
/*求职意向*/
.career {
  display: flex;
  margin-bottom: 40px;
}
.career h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.career dl {
  width: 100%;
  margin-bottom: 40px;
}
.career dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.career li {
  margin-bottom: 8px;
}
.career li dl {
  display: flex;
  margin-bottom: 0;
}
.career li dd {
  margin-right: 20px;
}
/*求职意向 end*/
/*教育背景*/
.background {
  display: flex;
  margin-bottom: 40px;
}
.background h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.background dl {
  width: 100%;
  margin-bottom: 40px;
}
.background dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.background li {
  margin-bottom: 8px;
}
.background li dl {
  display: flex;
  margin-bottom: 0;
}
.background li dd {
  margin-right: 40px;
}
/*教育背景 end*/
/*工作经验*/
.work {
  display: flex;
  margin-bottom: 40px;
}
.work h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.work dl {
  width: 100%;
  margin-bottom: 40px;
}
.work dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.work dt span {
  margin-right: 100px;
}
/*工作经验end*/
/*项目经验*/
.project {
  display: flex;
  margin-bottom: 40px;
}
.project h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.project dl {
  width: 100%;
  margin-bottom: 40px;
}
.project dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.project dt span {
  margin-right: 100px;
}
.project .box {
  display: flex;
  flex-direction: column;
}
/*项目经验 end*/
/*自我评价*/
.self-evaluation {
  display: flex;
  margin-bottom: 40px;
}
.self-evaluation h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.self-evaluation li {
  margin-bottom: 8px;
}
.self-evaluation dl {
  width: 100%;
  margin-bottom: 40px;
}
.self-evaluation dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
/*自我评价 end*/
/*技能列表*/
.skill-list {
  display: flex;
  margin-bottom: 40px;
}
.skill-list h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.skill-list li {
  margin-bottom: 8px;
}
.skill-list dl {
  width: 100%;
  margin-bottom: 40px;
}
.skill-list dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
/*技能列表 end*/
/*作品展示*/
.gallery {
  display: flex;
  margin-bottom: 40px;
}
.gallery h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.gallery li {
  margin-bottom: 8px;
}
.gallery .link {
  background: #eee;
  width: 100%;
  border-radius: 10px;
  padding: 10px;
}
.gallery .link a {
  color: #31a5ff;
}
/*作品展示 end*/

.container {
  width: 1200px;
  padding: 40px;
}
html {
  background: #ddd;
}
.container {
  background: #fff;
}
html {
  overflow: auto;
}
.code-show {
  opacity: 0;
  display: none;
}
`
    }
  },
  mounted(): void {
    this.wr()
  },
  methods: {
    wr() {
      const _this: any = this
      if (_this.styleShowIndex < _this.styleText.length) {
        setTimeout(() => {
          _this.styleShowText += _this.styleText[_this.styleShowIndex]
          _this.styleShowIndex++
          _this.wr()
        }, 8)
      }
    }
  }
})
</script>
<!--
/* Sample `apply` at-rules with Tailwind CSS
  .container {
    @apply min-h-screen flex justify-center items-center text-center mx-auto;
  }
  */
-->
<!--
<style>
* {
  transition: all 0.5s;
  color: #333;
}
img {
  display: block;
  transition: all 0.5s;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  font-size: 12pt;
}
/*关于我*/
.intr {
  display: flex;
  margin-bottom: 40px;
}
.intr h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.intr img {
  width: 120px;
  border-radius: 50%;
}
.intr h1 {
  font-size: 20pt;
  font-weight: bold;
}
.intr dl {
  width: 100%;
  margin-bottom: 40px;
}
.intr dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.intr .tags {
}
.intr .tags dd {
  width: 90px;
  height: 30px;
  text-align: center;
  padding: 2px 10px;
  margin-right: 10px;
  border-radius: 14px;
  border: 1px solid #333;
}
.intr li {
  margin-bottom: 8px;
}
.intr li dl {
  display: flex;
  margin-bottom: 0;
}
.intr li dd {
  margin-right: 20px;
}
/*关于我 end*/
/*求职意向*/
.career {
  display: flex;
  margin-bottom: 40px;
}
.career h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.career dl {
  width: 100%;
  margin-bottom: 40px;
}
.career dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.career li {
  margin-bottom: 8px;
}
.career li dl {
  display: flex;
  margin-bottom: 0;
}
.career li dd {
  margin-right: 20px;
}
/*求职意向 end*/
/*教育背景*/
.background {
  display: flex;
  margin-bottom: 40px;
}
.background h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.background dl {
  width: 100%;
  margin-bottom: 40px;
}
.background dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.background li {
  margin-bottom: 8px;
}
.background li dl {
  display: flex;
  margin-bottom: 0;
}
.background li dd {
  margin-right: 40px;
}
/*教育背景 end*/
/*工作经验*/
.work {
  display: flex;
  margin-bottom: 40px;
}
.work h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.work dl {
  width: 100%;
  margin-bottom: 40px;
}
.work dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.work dt span {
  margin-right: 100px;
}
/*工作经验end*/
/*项目经验*/
.project {
  display: flex;
  margin-bottom: 40px;
}
.project h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.project dl {
  width: 100%;
  margin-bottom: 40px;
}
.project dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
.project dt span {
  margin-right: 100px;
}
.project .box {
  display: flex;
  flex-direction: column;
}
/*项目经验 end*/
/*自我评价*/
.self-evaluation {
  display: flex;
  margin-bottom: 40px;
}
.self-evaluation h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.self-evaluation li {
  margin-bottom: 8px;
}
.self-evaluation dl {
  width: 100%;
  margin-bottom: 40px;
}
.self-evaluation dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
/*自我评价 end*/
/*技能列表*/
.skill-list {
  display: flex;
  margin-bottom: 40px;
}
.skill-list h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.skill-list li {
  margin-bottom: 8px;
}
.skill-list dl {
  width: 100%;
  margin-bottom: 40px;
}
.skill-list dt {
  font-size: 14pt;
  margin-bottom: 6px;
}
/*技能列表 end*/
/*作品展示*/
.gallery {
  display: flex;
  margin-bottom: 40px;
}
.gallery h3 {
  flex-shrink: 0;
  width: 140px;
  height: 100%;
  font-size: 18pt;
  font-weight: bold;
}
.gallery li {
  margin-bottom: 8px;
}
.gallery .link {
  background: #eee;
  width: 100%;
  border-radius: 10px;
  padding: 10px;
}
.gallery .link a {
  color: #31a5ff;
}
/*作品展示 end*/

.container {
  width: 1200px;
  padding: 40px;
}
html {
  background: #ddd;
}
.container {
  background: #fff;
}
html {
  overflow: auto;
}
.code-show {
  opacity: 0;
  display: none;
}
</style>
-->
