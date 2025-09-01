<template>
    <div>
        <div class="navigation">
            <div class="dh">
                <div>
                    <img
                    src="https://lf-dw.toutiaostatic.com/obj/toutiao-duanwai/toutiao/toutiao_web_pc/svgs/logo_red.80c49156.svg"
                    alt="" />
                </div>
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
            </div>
            <div class="navigateright">
            <div class="search2">
                <el-input
                    class="input1"
                    v-model="inputTxt"
                    placeholder=""
                ></el-input>
                <div class="search">
                  <div class="linewai">
                  <div class="line">

                  </div>
                  </div>
                <div>
                  <i class="el-icon-search red"></i>
                </div>
                <div  class="red">搜索</div>
                </div>
                
            </div>
            <div class="message">
                <div>
                  <i class="el-icon-bell"></i>
                </div>
                <div>
                  消息
                </div>
                </div>
                <div class="message">
                <div>
                  <i class="el-icon-circle-plus-outline"></i>
                </div>
                <div>
                  发布
                </div>
                </div>
                <div class="message">
                  <div class="login">
                  登录
                  </div>
                </div>
                </div>
        </div>
         
        <div class="Outerframe">
            <div class="Outerframe1">
                <div>
                    <div class="zt">微视频｜建设现代化人民城市</div>
                    <div class="zt1">
                        <div class="zt2 font">2025-07-23 19:22</div>
                        <div class="zt2 font d">·</div>
                        <div class="zt2 font">新华社</div>
                    </div>
                </div>
                <div class="page">
                    <div>
                        <img
                            class="Image"
                            src="https://p3-sign.toutiaoimg.com/tos-cn-i-axegupay5k/fbf3f35f96cc4e21a6c7bef53380a164~tplv-tt-origin-web:gif.jpeg?_iz=58558&from=article.pc_detail&lk3s=953192f4&x-expires=1755402370&x-signature=RX71RVEL44i6gHXKy7lAyFrHLug%3D"
                            alt=""
                        />
                    </div>
                    <div class="Maintext">
                        中央城市工作会议7月14日至15日在北京举行。习近平总书记出席会议并发表重要讲话。
                    </div>
                    <div>
                        <img
                            class="Image"
                            src="https://p3-sign.toutiaoimg.com/tos-cn-i-axegupay5k/fbf3f35f96cc4e21a6c7bef53380a164~tplv-tt-origin-web:gif.jpeg?_iz=58558&from=article.pc_detail&lk3s=953192f4&x-expires=1755402370&x-signature=RX71RVEL44i6gHXKy7lAyFrHLug%3D"
                            alt=""
                        />
                    </div>
                    <div class="Maintext">
                        党的十八大以来，习近平总书记对城市工作作出一系列重要论述，深刻回答城市建设发展依靠谁、为了谁的根本问题，着力破解建设什么样的城市、怎样建设城市的重大命题，为新时代城市发展建设定向领航。
                    </div>
                    <div>
                        <img class="Image"
                            src="https://p3-sign.toutiaoimg.com/tos-cn-i-axegupay5k/fbf3f35f96cc4e21a6c7bef53380a164~tplv-tt-origin-web:gif.jpeg?_iz=58558&from=article.pc_detail&lk3s=953192f4&x-expires=1755402370&x-signature=RX71RVEL44i6gHXKy7lAyFrHLug%3D"
                            alt=""
                        />
                    </div>
                    <div class="Maintext">
                        要“见物”，也要“见人”。在2015年12月的中央城市工作会议上，总书记指出，全心全意为人民服务，为人民群众提供精细的城市管理和良好的公共服务，是城市工作的重头，不能见物不见人。
                    </div>
                    <div>
                        <img class="Image"
                            src="https://p3-sign.toutiaoimg.com/tos-cn-i-axegupay5k/fbf3f35f96cc4e21a6c7bef53380a164~tplv-tt-origin-web:gif.jpeg?_iz=58558&from=article.pc_detail&lk3s=953192f4&x-expires=1755402370&x-signature=RX71RVEL44i6gHXKy7lAyFrHLug%3D"
                            alt=""
                        />
                    </div>
                    <div class="Maintext">
                        要保护，也要传承。2020年10月，总书记在广东考察时强调，在改造老城、开发新城过程中，要保护好城市历史文化遗存，延续城市文脉，使历史和当代相得益彰。
                    </div>
                    <div>
                        <img class="Image"
                            src="https://p3-sign.toutiaoimg.com/tos-cn-i-axegupay5k/fbf3f35f96cc4e21a6c7bef53380a164~tplv-tt-origin-web:gif.jpeg?_iz=58558&from=article.pc_detail&lk3s=953192f4&x-expires=1755402370&x-signature=RX71RVEL44i6gHXKy7lAyFrHLug%3D"
                            alt=""
                        />
                    </div>
                    <div class="Maintext">
                        要“面子”，也要“里子”。2024年4月，总书记来到重庆市九龙坡区谢家湾街道民主村社区察看小区改造和便民服务情况时指出，老旧小区改造是城市更新的一个重点，也是一项民生工程，既要保留历史记忆和特色风貌，又要解决居民关切的实际问题
                    </div>
                    <div>
                        <img  class="Image"
                            src="https://p3-sign.toutiaoimg.com/tos-cn-i-axegupay5k/fbf3f35f96cc4e21a6c7bef53380a164~tplv-tt-origin-web:gif.jpeg?_iz=58558&from=article.pc_detail&lk3s=953192f4&x-expires=1755402370&x-signature=RX71RVEL44i6gHXKy7lAyFrHLug%3D"
                            alt=""
                        />
                    </div>
                    <div class="Maintext">
                        新时代，我国正建设创新、宜居、美丽、韧性、文明、智慧的现代化人民城市，走出一条中国特色城市现代化新路子。
                    </div>
                    <div>
                        <img
                            class="Image"
                            src="https://p3-sign.toutiaoimg.com/tos-cn-i-axegupay5k/fbf3f35f96cc4e21a6c7bef53380a164~tplv-tt-origin-web:gif.jpeg?_iz=58558&from=article.pc_detail&lk3s=953192f4&x-expires=1755402370&x-signature=RX71RVEL44i6gHXKy7lAyFrHLug%3D"
                            alt=""
                        />
                    </div>
                    <div class="Maintext">统筹：韩珅、王志斌</div>
                    <div class="Maintext">编导：李林欣、姬杨</div>
                    <div class="Maintext">综合新华社记者报道</div>
                    <div class="Maintext">配音：王帅龙</div>
                    <div class="Maintext">海报：单怡颖</div>
                    <div class="Maintext">新华社音视频部制作</div>
                </div>
            </div>
            <div>
              <div class="ysxw">
          <img class="cctv" src="https://sf3-cdn-tos.toutiaostatic.com/img/user-avatar/37e39b02e9329684d927ea6711abaed3~300x300.image" alt="">
        <div class="ysxwtext">央视新闻</div>
        <div class="introduce">中央广播电视总台央视新闻官方账号</div>
        <div class="concern">
          <div class="concern1">关注</div>
          </div>
        </div>
        <div class="title2">
        <div class="title">TA的热门作品</div>
        </div>
        <div class="populararea">
          <div ><img class="Popularimages" src="https://p3-sign.toutiaoimg.com/tos-cn-i-tjoges91tu/4894678180ed58bc211616c1c5b52633~720x380_cs.webp?_iz=31826&bid=10&from=article.pc_profile_article&gid=7537950188795691574&lk3s=06827d14&x-expires=1757658517&x-signature=OhXphh1Hoaq1CL1JcCP%2BILPID%2BU%3D" alt=""></div>
          <div class="opus">
            <div class="zptitle">玉渊谭天丨独家观察：美国如何给芯片安“后门”</div>
            <div class="zp">
              <div class="zp2">123阅读</div>
              <div class="zp2">35分钟前</div>
            </div>
          </div>
          
        </div>
        <div class="populararea">
          <div ><img class="Popularimages" src="https://p3-sign.toutiaoimg.com/tos-cn-i-tjoges91tu/2c0005a38dddcb485228cd91acf3582e~720x380_cs.webp?_iz=31826&bid=10&from=article.pc_profile_article&gid=7537940370504548915&lk3s=06827d14&x-expires=1757658517&x-signature=%2BisexFGwLn7In0dvqYDte344SRE%3D" alt=""></div>
          <div class="opus">
            <div class="zptitle">玉渊谭天丨独家观察：美国如何给芯片安“后门”</div>
            <div class="zp">
              <div class="zp2">123阅读</div>
              <div class="zp2">35分钟前</div>
            </div>
          </div>
          
        </div>
        <div class="populararea">
          <div ><img class="Popularimages" src="https://sf3-cdn-tos.toutiaostatic.com/img/user-avatar/37e39b02e9329684d927ea6711abaed3~300x300.image" alt=""></div>
          <div class="opus">
            <div class="zptitle">玉渊谭天丨独家观察：美国如何给芯片安“后门”</div>
            <div class="zp">
              <div class="zp2">123阅读</div>
              <div class="zp2">35分钟前</div>
            </div>
          </div>
          
        </div>
        <div class="tttop">
        <div class="tt">
        <div><img src="https://lf-dw.toutiaostatic.com/obj/toutiao-duanwai/toutiao/toutiao_web_pc/svgs/hot_board.e124faac.svg" alt=""></div>
        <div>头条热榜</div>
        </div>
        <div>
          <div class="hotlist"  v-for="(item, index) in essaylist"
                            :key="item.id">
            <div v-if="index==0"><img class="" src="https://lf9-static.bytednsdoc.com/obj/eden-cn/pipieh7nupabozups/toutiao_web_pc/icon_hot_board_stick.svg" alt=""></div>
            <div v-else :class=" index == 1 ? 'redcolor':index == 2 ?'orangecolor':index == 3 ? 'yellowcolor':'huicolor' " >{{ index }}</div>
          
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
    name: 'HomeView',
    data() {
        return {
          inputTxt: '',
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
              name:"金建希被捕前公开亮相走路踉跄"
            },
            {
               id: 5,
              name:"专家解答猫狗抓咬伤八大问题"
            }
          ]
        }
    },
    methods: {
        jofun() {}
    },
    mounted() {
        // let num = prompt("身高")
        // let rum = prompt("资产")
        // let bum = prompt("颜值满分一百")
        // if (num >= 180&&rum >= 1000&&bum>=100) {
        // alert('完美')
        // } else if (num >= 180||rum >= 1000||bum>=100) {
        // alert('良好')
        // } else {
        //   alert('差')
        // }
        // let num = prompt("输入成绩")
        // if (num>=100) {
        //   alert('奖励一台BWM')
        // }
        // else if (num >= 80) {
        //   alert('奖励一台iphone')
        // }
        // else if (num >=60) {
        //   alert('奖励一本书')
        // }
        // else {
        //   alert('没有奖励')
        // }
        // let num = prompt("请输入一个整数")
        //  if (num % 2 == 1) {
        //   alert('奇数')
        // }else if (num % 2 == 0){
        //   alert('偶数')
        // } else {
        //   alert('请输入整数')
        // }
    }
}
</script>

<style rel="stylesheet/scss" lang="css" scoped>
.navigation {
    position: sticky;
    top: 0px;
    background-color: #ffffff;
    display: flex;
    justify-content: space-between;
}
.dh {
    display: flex;
    height: 45px;
    align-items: center;
}
.dh1 {
    display: flex;
}
.dhcontent {
    font-size: 16px;
    color: #222;
    margin: 0 10px;
}
.Outerframe {
    margin: 40px 0 0 0;
    padding: 0 700px;
      width: 1130px;
    display: flex;
}
.zt {
    font-size: 37px;
    font-weight: bold;
}
.zt1 {
    display: flex;
}
.font {
    color: #707070;
}
.d {
    margin: 0 4px;
}
.Image {
    width: 100%;
    height: 50%;
}
.Maintext {
    margin: 20px 0;
    font-size: 20px;
}


::v-deep .input1 .el-input__inner {
    background-color: #f5f5f5;
    width: 400px;
}
.search{
display: flex;
  position: absolute;
  top: 5px;
  right: 10px;
}
.search2{
   position: relative;
}
.red{
  color: red;
  margin: 0 5px;
  
}
.line{
  height: 16px;
  width: 1px;
  background-color: #e8e8e8;

}
.linewai{
  display: flex;
  align-items: center;
}
.message{
  display: flex;
margin: 0 20px;

}
.navigateright{
  display: flex;
  padding-top: 10px;
}
.login{
  background-color: #ff0000;
color: rgb(255, 255, 255);
width: 60px;
height: 34px;
display: flex;
justify-content: center;
align-items: center;
border-radius: 8px;
}
.page{
  width: 676px;
}
.cctv{
  border-radius: 50%;
   width: 70px;
  height: 70px;
 
}
.ysxw{
  width: 318px;
  height: 200px;
  text-align: center;
}
.ysxwtext{
  margin: 8px 0 4px;
  
}
.introduce{
  color: #707070;
  font-size: 14px;
}
.concern{
  display: flex;
  justify-content: center;
  margin: 10px 0;
}
.concern1{
  width: 96px;
  height: 32px;
  background: #f04142;
  border-radius: 8px;
  color: #ffffff;
  display: flex;
  align-items: center;
  justify-content: center;
}
.title{
  font-size: 14px;

}
.title2{
display: flex;
justify-content: center;
width: 100%;
}
.Popularimages{
  width: 94px;
  height: 70px;

}
.zp{
  display: flex;
}
.zp2{
  margin: 5px 5px;
  font-size: 14px;

}
.populararea{
  display: flex;
  margin: 0 0px 0 40px;
  color: #999;
  width: 318px;
  padding: 12px;
}
.zptitle{
  color: #222;
}
.opus{
  margin: 0 0 0 10px;
}
.tt{
  display: flex;
}
.hotlist{
display: flex;
margin: 10px 0 0 0 ;
}
.hotlisttext{
margin: 0px 0 0 10px;
}
.tttop{
  margin: 0 0 0 50px;
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
.toplcun{
  height: 50px;
  width: 50px;
}

</style>