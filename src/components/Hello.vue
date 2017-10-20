<template>
  <div class="hello">
  <header class="bar bar-nav">
    <h1 class="title">卡片</h1>
  </header>
  <div class="content">
    <div class="content-block-title">简单卡片</div>
    <div class="card">
      <div class="card-content">
        <div class="card-content-inner">这是一个用纯文本的简单卡片。但卡片可以包含自己的页头，页脚，列表视图，图像，和里面的任何元素。</div>
      </div>
    </div>
    <div class="card">
      <div class="card-header">卡头</div>
      <div class="card-content">
        <div class="card-content-inner">头和尾的卡片。卡头是用来显示一些额外的信息，或自定义操作卡标题和页脚。</div>
      </div>
      <div class="card-footer">卡脚</div>
    </div>
    <div class="card">
      <div class="card-content">
        <div class="card-content-inner">这是一个用纯文本的简单卡片。但卡片可以包含自己的页头，页脚，列表视图，图像，和里面的任何元素。</div>
      </div>
    </div>
    <div class="content-block-title">风格卡片</div>
    <div class="card demo-card-header-pic">
      <div valign="bottom" class="card-header color-white no-border no-padding">
        <img class='card-cover' src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i3/TB10LfcHFXXXXXKXpXXXXXXXXXX_!!0-item_pic.jpg_250x250q60.jpg" alt="">
      </div>
      <div class="card-content">
        <div class="card-content-inner">
          <p class="color-gray">发表于 2015/01/15</p>
          <p>此处是内容...</p>
        </div>
      </div>
      <div class="card-footer">
        <a href="#" class="link" @click="zan">赞</a>
        <a href="#" class="link">更多</a>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
    export default {
        name: 'hello',
        data () {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        },
        methods: {
            zan() {
                $.alert('点个赞');
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
