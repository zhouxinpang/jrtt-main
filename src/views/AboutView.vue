<template>
    <div class="Outermost">

        <div class="home-banner-wrapper">
            <div class="home-banner">
                <video
                    src="https://lf9-static.bytednsdoc.com/obj/eden-cn/uhbfnupkbps/video/earth_v6.mp4"
                    autoplay
                    muted="muted"
                ></video>
                <div class="Navigatewai2">
                    <div class="Navigatewai">
                        <div class="Navigateleft">
                            <div class="fontleft">下载头条APP</div>
                            <div class="fontleft">添加到桌面 周丽丹2</div>
                            <div class="fontleft">关于头条</div>
                            <div class="fontleft">反馈</div>
                            <div class="fontleft">侵权投诉</div>
                        </div>
                        <div class="Navigateright">
                            <div class="fontleft">
                                <div class="Weather">
                                    <div class="Weather2">杭州</div>
                                    <img
                                        class="weatherchart"
                                        src="https://sf3-cdn-tos.douyinstatic.com/obj/eden-cn/pipieh7nupabozups/toutiao_web_pc/weather_white/0.png"
                                        alt=""
                                    />
                                    <div class="Weather2">晴</div>
                                    <div class="Weather2">35℃</div>
                                    <div class="Weather2">优</div>
                                </div>
                            </div>
                            <div class="fontleft">
                                <div class="publish">
                                    <i class="el-icon-bell"></i>消息
                                </div>
                            </div>
                            <div class="fontleft">
                                <div class="publish">
                                    <i class="el-icon-circle-plus-outline"></i
                                    >发布作品
                                </div>
                            </div>

                            <div class="fontleft">
                                <div class="buttonright">登录</div>
                            </div>
                        </div>
                    </div>

                    <div class="topic">
                        <div class="topic2">今日头条</div>
                        <div class="Search" style="margin-top: 15px">
                            <el-input placeholder="请输入内容" v-model="input4">
                                <template slot="append"
                                    ><i class="el-icon-search"></i
                                ></template>
                            </el-input>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="Outermostwai">
        <div>
        <div class="homepage">
            <div class="dh1">
                <div class="dhcontent">关注</div>
                <div class="dhcontent">推荐</div>
                <div class="dhcontent">
                    <el-dropdown>
                        <span class="el-dropdown-link">
                            杭州<i
                                class="el-icon-arrow-down el-icon--right"
                            ></i>
                        </span>
                        <el-dropdown-menu slot="dropdown">
                            <el-dropdown-item>1</el-dropdown-item>
                            <el-dropdown-item>2</el-dropdown-item>
                            <el-dropdown-item>3</el-dropdown-item>
                        </el-dropdown-menu>
                    </el-dropdown>
                </div>
                <div class="dhcontent">视频</div>
                <div class="dhcontent">财经</div>
                <div class="dhcontent">科技</div>
                <div class="dhcontent">热点</div>
                <div class="dhcontent">国际</div>
                <div class="dhcontent">更多</div>
            </div>
            <div class="News">
              <div class="Newsztwai">
                <div class="Newszt">
                    <img
                        src="https://lf-dw.toutiaostatic.com/obj/toutiao-duanwai/toutiao/toutiao_web_pc/svgs/subtract_logo.a9550d1b.svg"
                        alt=""
                    />
                    <div>要闻</div>
                    <div class="time">2025.08.14 星期四</div>
                </div>
                <div class="link2"><a class="link" href="https://www.toutiao.com/article/7538209461891039785/?log_from=6a6ba62d4c38f_1755165666377">加快推进人与自然和谐共生的现代化</a></div>
                <div class="link2"><a class="link" href="https://www.toutiao.com/article/7538036100598678025/?log_from=a9cf8762eef8e8_1755165737704">民营经济发展向好活力增强</a></div>
                <div class="link2"><a class="link" href="https://www.toutiao.com/article/7538233017517572662/?log_from=b942b5bfff0fb_1755165788370">巩固拓展经济回升向好势头</a></div>
                <div class="link2"><a class="link" href="https://www.toutiao.com/article/7538029299874513443/?log_from=df3e32166e88d8_1755165795347">“水稻+”绘就希望的田野好“丰”景</a></div>
                <div class="link2"><a class="link" href="https://api.toutiaoapi.com/feoffline/amos_subject/hotrio_subject_page_h5/html/main/index.html?amos_id=7517094888195260466&category_name=__all__&enable_native=1&group_id=7518729847124807206&style_id=30015&title=%E9%93%AD%E8%AE%B0%E5%8E%86%E5%8F%B2%2B%E7%BC%85%E6%80%80%E5%85%88%E7%83%88&log_from=83d18fb6fcaa38_1755165802931">铭记历史 缅怀先烈</a></div>
                </div>
            </div>
        </div>
        <div class="news" v-for="(item, index) in News" :key="item.id" @click="HomeView">
          <div class="description2">
            <div>{{item.title}}</div>
            <div class="description">
              <div class="descriptiontext">{{item.comments}}</div>
              <div class="descriptiontext">{{item.comments1}}</div>
              <div class="descriptiontext">{{item.comments2}}</div>
            </div>
          </div>
          <img class="newsmap" :src="item.img" alt="">
        </div>
</div>
      <div class="rightpage">
        <div class="Loginnow">
          <div class="Loginnowdr">登录后，头条更懂你</div>
          <div class="Loginnowan">
            <div class="Loginnowan1">立即登录</div>
          </div>
        </div>
        <div>
        <div class="safeclassroom">
          <img src="https://lf-dw.toutiaostatic.com/obj/toutiao-duanwai/toutiao/toutiao_web_pc/svgs/security_icon.6e66438b.svg" alt="">
          <div>安全课堂</div>
        </div>
       <div>
        <img class="Antifraud" src="https://lf3-beecdn.bytetos.com/obj/ies-fe-bee/bee_prod/biz_1128/tos_07dcbd0f70eb5e52510dd5dc6abe7061.png" alt="">
        <img class="Antifraud" src="https://lf3-beecdn.bytetos.com/obj/ies-fe-bee/bee_prod/biz_1128/tos_16cfa7beceda1e131dacc5d5b525ab06.png" alt="">
        </div>
</div>
<div>
   <div>
    <div>头条热榜</div>
          <div class="hotlist"  v-for="(item, index) in essaylist"
                            :key="item.id">
            <div v-if="index==0"><img class="" src="https://lf9-static.bytednsdoc.com/obj/eden-cn/pipieh7nupabozups/toutiao_web_pc/icon_hot_board_stick.svg" alt=""></div>
            <div v-else :class="index == 1 ? 'redcolor':index == 2 ?'orangecolor':index == 3 ? 'yellowcolor':'huicolor'" > {{ index }} </div>

            <div class="hotlisttext">{{item.name}}</div>

             </div>
          </div>
</div>

      </div>
        </div>


    </div>
</template>
<script>
export default {
    name: 'AboutView',
    data() {
      return {
        News:[
          {
            img: 'https://p3-sign.toutiaoimg.com/tos-cn-i-tjoges91tu/878a738602ebfb0131453720ca0cdc96~tplv-tt-cs0:1440:2560.jpg?_iz=31826&bid=11&from=article.headline&gid=7538401228439470643&lk3s=06827d14&x-expires=1757834341&x-signature=%2FJ2WDdw7rjQIJsexupfKZePYfp0%3D',
            title: '为转移群众被洪水冲走 怀柔村支书尹春燕遗体被找到 其丈夫遗体于8月4日被发现',
            comments: '生活帮',
            comments1: '30评论',
            comments2: '20小时前',

          },
         {
            img: 'https://p3-sign.toutiaoimg.com/tos-cn-i-qvj2lq49k0/cb113c786ef8452eba249105f20db56b~tplv-tt-cs0:619:483.jpg?_iz=31826&bid=10&from=article.headline&gid=7538795843336356379&lk3s=06827d14&x-expires=1757917040&x-signature=HSM%2B%2FqgT%2BSEK4knQskTxQRM%2FRFU%3D',
            title: '判了！周立人，死刑！',
            comments: '生活帮',
            comments1: '30评论',
            comments2: '20小时前',

          },
         {
            img: 'https://p6-sign.toutiaoimg.com/tos-cn-i-6w9my0ksvp/dbfac204e32b410a8c74df55c7f882fb~tplv-tt-cs0:1290:1962.jpg?_iz=31826&bid=10&from=article.headline&gid=7522032498805719591&lk3s=06827d14&x-expires=1757917040&x-signature=CNwSwLanxrjDdlVzgQjYhH0aYxQ%3D',
            title: '男子记错单元号装修了别人家的房子，因和房东协商无果，男子直接将房东和物业告上了法院！',
            comments: '生活帮',
            comments1: '30评论',
            comments2: '20小时前',

          },
         {
            img: 'https://p3-sign.toutiaoimg.com/tos-cn-i-6w9my0ksvp/adcf0af0ad4c433cad339f7997d970c1~tplv-tt-cs0:1080:3161.jpg?_iz=31826&bid=10&from=article.headline&gid=7537583295865864742&lk3s=06827d14&x-expires=1757917040&x-signature=WWX47n%2Fq1%2Bosif9MCUP39weaoRw%3D',
            title: '突然暴雷！总部人去楼空！多人已被抓',
            comments: '生活帮',
            comments1: '30评论',
            comments2: '20小时前',

          },
         {
            img: 'https://p3-sign.toutiaoimg.com/tos-cn-i-6w9my0ksvp/ab353f4390e24f0a807dfa7b8120cbd1~tplv-tt-cs0:1080:1729.jpg?_iz=31826&bid=10&from=article.headline&gid=7532082974523769384&lk3s=06827d14&x-expires=1757917040&x-signature=thbHUjJyONz8Z%2BHJQ1asFvB8u6o%3D',
            title: '工作间隙，我垫着木板，在废纸上练柳楷',
            comments: '生活帮',
            comments1: '30评论',
            comments2: '20小时前',

          },
         {
            img: 'https://p3-sign.toutiaoimg.com/tos-cn-i-6w9my0ksvp/7c82562bc6f64832815b7fe14888f5ea~tplv-tt-cs0:786:779.jpg?_iz=31826&bid=10&from=article.headline&gid=7536604214773072422&lk3s=06827d14&x-expires=1757917040&x-signature=QxKf8ELZ%2BlgIcG%2Fx9cmZoRyL3Rs%3D',
            title: '5万人大莲花合唱！谢霆锋一开口，全场泪崩：我的青春回来了！',
            comments: '生活帮',
            comments1: '30评论',
            comments2: '20小时前',

        },
        ],
        essaylist: [
            {
              id: 1,
              name:"习近平总书记40余年的牵挂"
            },
            {
               id: 2,
              name:"美驱逐舰擅闯黄岩岛 解放军警告驱离"
            },
            {
               id: 3,
              name:"金建希受审时念了句中国古诗"
            },
            {
               id: 4,
              name:"重温总书记讲述的抗战岁月"
            },
            {
               id: 5,
              name:"特朗普普京同车离开机场“不寻常”"
            },
            {
               id: 6,
              name:"7月经济发展“进”的步伐稳健"
            },
            {
               id: 7,
              name:"“续面事件”消费者共消费140.58元"
            },
            {
               id: 8,
              name:"唐驳虎：特普会匆忙结束饭都没吃"
            },
            {
               id: 5,
              name:"“董某莹肖某事件”19人被问责"
            },
            {
               id: 5,
              name:"辟谣榜｜海啸致上海转移30万人系谣言，辟谣"
            }
          ]

        }
    },
  methods: {
    HomeView() {
     this.$router.push({ name: 'HomeView' });
  },
  },

    mounted() {}
}
</script>

<style rel="stylesheet/scss" lang="css" scoped>
.Navigateleft {
    display: flex;
}
.Navigateright {
    display: flex;
    margin-right: 20px;
}
.Navigatewai {
    z-index: 999;
    position: absolute;
    top: 20px;
    left: 0px;
    display: flex;
    justify-content: space-between;
    width: 100%;
}

.fontleft {
    color: #ffffff;
    margin-left: 20px;
}
.home-banner-wrapper video {
    position: relative;
    z-index: 1;
    width: 100%;
    height: 100%;
    -o-object-fit: cover;
    object-fit: cover;
}
video {
    object-fit: contain;
    overflow-clip-margin: content-box;
    overflow: clip;
}
.home-banner-wrapper {
    position: relative;
    overflow: hidden;
    height: 312px;
    height: 39vh;
    max-height: 360px;
    min-height: 273px;
    background: #222;
}
.home-banner {
    transform: translate3d(0px, 0px, 0px);
}
.home-banner-wrapper .video-poster {
    position: absolute;
    top: 0;
    left: 0;
}
.home-banner-wrapper .static-img,
.home-banner-wrapper .video-poster {
    width: 100%;
    height: 100%;
    background: transparent no-repeat 50%;
    background-size: cover;
}
.buttonright {
    background: #ff0000;
    width: 52px;
    height: 28px;
    display: flex;
    justify-content: center;
    border-radius: 5px;
}
.publish {
    display: flex;
    align-items: center;
}
.weatherchart {
    width: 10%;
}
.Weather {
    display: flex;
}
.Weather2 {
    margin-right: 10px;
    font-size: 14px;
}
.Navigatewai2 {
}
.topic {
    position: absolute;
    top: 70px;
    left: 0px;
    width: 100%;
    z-index: 999;
}
.topic2 {
    display: flex;
    justify-content: center;
    font-size: 45px;
    color: #ffffff;
    font-weight: bold;
}
.Search {
    width: 30%;
    margin: 0 auto;
}
.dh1 {
    display: flex;
    justify-content: space-between;
}
.dhcontent {
    font-size: 16px;
    color: #222;
    margin: 0 10px;
}
.homepage {
    width: 658px;
    height: 100%;

}
.News {
    width: 658px;
    height: 222px;
    background: #fff4f4;
}
.Newszt{
  display: flex;
  align-items: center;

}
.time{
  font-size: 14px;
  color: #c1c1c1;
  margin-left: 10px;
}
.Newsztwai{
 padding: 20px 32px;
}
.link{
  color: #000;
   text-decoration: none;
}
.link2{
  margin-top: 10px;
}
.Outermost{

}
.Outermostwai{
  margin: 0 738px;
width: 1060px;
height: 234px;
display: flex;
}
.description{
  display: flex;
 margin-top: 30px;
}
.description2{
  width: 482px;
}
.newsmap{
  width: 155px;
  height: 104px;
  object-fit: cover;
object-position: center;
}
.news{
  display: flex;
  padding: 16px 0;
}
.descriptiontext{
  font-size: 14px;
  color: #999;
  margin-right: 20px;
}
.Loginnow{
  width: 302px;
  height: 56px;
  background: rgba(244, 245, 247, .5);
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-radius: 8px;
}
.Loginnowan{
  width: 80px;
  height: 28px;
  background-color: #ff403a;
 margin-right: 20px;
 border-radius: 8px;
}
.Loginnowan1{
  color: #ffffff;
  display: flex;
  justify-content: center;
}
.Loginnowdr{
   margin-left: 20px;
   color: #999;
}
.safeclassroom{
  display: flex;
}
.Antifraud{
  width: 40%;
 margin: 5px;
}
.rightpage{
  margin-left: 40px;
}
.hotlist{
display: flex;
margin: 10px 0 0 0 ;
}
.redcolor{
color: red;
}
.orangecolor{
color: orange;
}
.yellowcolor{
color: yellow;
}
.huicolor{
  color: #939393;
}
.hotlisttext{
margin: 0px 0 0 10px;
}

</style>