<template>
  <div>
    <!--头部：简小头部，固定定位-->
    <div class="navbar navbar-inverse navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button class="navbar-toggle collapsed" type="button" data-toggle="collapse" data-target=".navbar-collapse">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="index.html">主页</a>
        </div>
        <div class="navbar-collapse collapse" role="navigation">
          <ul class="nav navbar-nav">
            <li><a href="xiaoa.html"  target="_blank">趣味资讯</a></li>
            <li><a href="game.html" target="_blank">畅爽游戏</a></li>
            <li><a href="products.html" target="_blank">物理提神</a></li>
            <li><a href="#" target="_blank">投稿</a></li>
            <li><a href="#" target="_blank">音视频剪辑指引</a></li>
            <li><a class="reddot" href="#" target="_blank">登陆</a></li>
          </ul>
          <ul class="nav navbar-nav navbar-right hidden-sm">
            <li><a href="#">关于</a></li>
          </ul>
        </div>
      </div>
    </div>
    <!--导航侧边栏，固定定位，小机器人->
    <!--banner区-->
    <div class="jumbotron">
      <div class="container">
        <h1>原型列表</h1>
        <!--这里有问题，缩小回让上面四个字消失-->
        <h2>阐述问题所用原型索引</h2>
        <p class="masthead-button-links">
        <!--  <a class="btn btn-lg btn-primary btn-shadow" href="xiaoa.html" target="_blank" role="button">提一下神</a>  -->
        </p>
        <ul class="masthead-links list-unstyled">
          <li>
           <!-- <a href="#" target="_blank" role="button">立即登陆提一下神</a> -->
          </li>
        </ul>
      </div>
    </div>
    <!--增加六个板块的页头介绍-->
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-sm-8 col-md-4 col-sm-offset-2 col-md-offset-4">
          <div class="page-header" style="text-align: center">
            <h1>问题原型</h1>
            <p>如下是对某个问题的展示原型</p>
          </div>
        </div>
      </div>
    </div>
    <!--提神醒脑六个板块介绍-->
    <div>
      <div class="container six">
      <div class="row">
        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="thumbnail tree">
            <!--<img src="../assets/img/410_240.png">-->
            <div class="caption">
              <h3>Vue-beforeRouteLeave</h3>
              <p>点击如下了解详情按钮</p>
              <p><router-link :to="{path:'/clickMaskA'}" class="btn btn-primary" role="button" target="_blank">了解详情</router-link></p>
            </div>
          </div>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="thumbnail tree">
            <!--<img src="../assets/img/410_240.png">-->
            <div class="caption">
              <h3>欢乐体</h3>
              <p>欢乐体裁的有趣微文，图片及短视频，会心一笑从点击这里开始！</p>
              <p><a href="xiaoa.html" class="btn btn-primary" role="button" target="_blank">了解详情</a></p>
            </div>
          </div>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="thumbnail tree">
            <!--<img src="../assets/img/410_240.png">-->
            <div class="caption">
              <h3>成人体</h3>
              <p>成人体裁的火辣微文，图片及短视频，个人中心验证身份后开启！</p>
              <p><a href="xiaoa.html" class="btn btn-primary" role="button" target="_blank">了解详情</a></p>
            </div>
          </div>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="thumbnail tree">
            <!--<img src="../assets/img/410_240.png">-->
            <div class="caption">
              <h3>新闻体</h3>
              <p>新闻体裁的图文资讯，轻松了解时事热点！</p>
              <p><a href="xiaoa.html" class="btn btn-primary" role="button" target="_blank">了解详情</a></p>
            </div>
          </div>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="thumbnail tree">
            <!--<img src="../assets/img/410_240.png">-->
            <div class="caption">
              <h3>社科体</h3>
              <p>社科体裁的图文资讯，足不出户认识大千世界！</p>
              <p><a href="xiaoa.html" class="btn btn-primary" role="button" target="_blank">了解详情</a></p>
            </div>
          </div>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4">
          <div class="thumbnail tree">
            <!--<img src="../assets/img/410_240.png">-->
            <div class="caption">
              <h3>音乐体</h3>
              <p>静谧时光，来点儿音乐提提神吧！</p>
              <p><a href="xiaoa.html" class="btn btn-primary" role="button" target="_blank">了解详情</a></p>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
    <!--简略底栏	-->
    <div class="panel panel-default footer">
      <div class="container">
        <div class="row">
          <div class="col-md-6 col-sm-6 col-xs-6">
            <h3>提神小a</h3>
            <p>我们致力于为大众提供短时提神娱乐平台！</p>
          </div>
          <div class="col-md-3 col-sm-3 col-xs-3">
            <div class="row">
              <div class="col-md-12 col-sm-12 col-xs-12"><h4>关于</h4></div>
            </div>
            <div class="row">
              <div class="col-md-12 col-sm-12 col-xs-12"><a href="#" class="text-info">关于我们</a></div>
            </div>
            <div class="row">
              <div class="col-md-12 col-sm-12 col-xs-12"><a href="#" class="text-info">广告合作</a></div>
            </div>
            <div class="row">
              <div class="col-md-12 col-sm-12 col-xs-12"><a href="#" class="text-info">友情链接</a></div>
            </div>
            <div class="row">
              <div class="col-md-12 col-sm-12 col-xs-12"><a href="#" class="text-info">招聘</a></div>
            </div>
          </div>
          <div class="col-md-3 col-sm-3 col-xs-3">
            <div class="row">
              <div class="col-md-12 col-sm-12 col-xs-12"><h4>联系方式</h4></div>
            </div>
            <div class="row">
              <div class="col-md-12 col-sm-12 col-xs-12"><a href="#" class="text-info">电子邮箱</a></div>
            </div>
            <div class="row">
              <div class="col-md-12 col-sm-12 col-xs-12"><a href="#"  class="text-info">微信公众号</a></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

</style>
