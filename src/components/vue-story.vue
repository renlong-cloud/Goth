<template>
  <div>
    <el-row>
      <el-col :span="24" class="story-img"></el-col>
    </el-row>
    <el-row class="story" v-for="(item, index) in storys" :key="index">
      <el-col :span="18" :offset="3">
        <h1>{{item.title}}</h1>
        <h3>{{item.author}}</h3>
        <p v-html="item.content"></p>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name: 'vue-story',
  data () {
    return {
      storys: [
        {
          title: '我在纽约',
          author: '郑倩',
          content:
            '对我而言，哥特更像是给了我一次看清自己的机会。把之前拥有的一切懒散习惯，一切不在意的小细节，一切埋藏在内心的压抑沮丧崩溃，一切不可能完成的梦想都颠覆，燃烧，摧毁，新生。在哥特的三年时光中，我重新探索，接受，模仿，找到刻在灵魂里的样子。就像许久以前听到的那一句名言，尔后一直回响在心中的呼喊：成为你自己。感恩哥特，让我知道，当我褪去身上的习惯和周围人的存在后，我可以找到我自己的模样，自信，开朗，乐观，积极向上。'
        },
        {
          title: '我在奥斯汀',
          author: '何维翼',
          content:
            '没有哥特，曾经的我大概认不出现在的我吧。但那些留在哥特的汗水，泪水，笑容，情绪都代替我记得。我在哥特的第一年就一直在期待着蜕变后我的样子，直至，今年，我入读了德州奥斯汀全美排名第一的机械工程专业，我如愿以偿地看到了自己幸福的模样。10年级的时候，因为课外活动贫乏，我每周穿梭在哥特的高尔夫球场游泳馆射击场，那时候的我乐此不彼却依然在期待11年级的我可以技压群雄。11年级的时候，每天在哥特早起背单词朗诵美文刷SAT，又在期待12年级的我可以轻松完成申请季。而完成了申请的12年级，仿佛一下子被抽出了齿轮的闹钟，失去了轴心，一动不动。静静回忆，过去的期待在哥特一点点被实现，这些美好的瞬间都让我留恋驻足，却又更好地推动我成为更好的自己。'
        },
        {
          title: '我在洛杉矶',
          author: '潘然',
          content:
            '哥特可以让我在Temple City High School如鱼得水，生龙活虎。准确来说，哥特从课程上帮助我提高了英语语言能力，并且同时也提高了我的数学物理化学成绩，另外呢，哥特引导和培养我的正确的学习方法，使我养成了良好的学习习惯。生活上，我在哥特学会了独立自主，打扫清洁缝纫烹饪，我现在样样拿手。在哥特的两年时光，我提前体验了美国高中生活，我的留美恐惧症不药而愈。偷偷告诉你们，哥特的每一个节日活动一定要参加，里面漂亮的小姐姐一不小心就是你未来学姐哟。'
        },
        {
          title: '我在芝加哥',
          author: '张希景',
          content: `说起哥特呀，那就说来话长了，<br/>\
                    让我各科成绩棒棒哒，<br/>它让我十八般武艺，酷炫技能吊炸天呀~<br/>\
                    正经说，正经说啊。<br/>最重要的一点当然是，哥特让我有机会来美国读书，那就可以和更多优秀的人一起学习生活了，让我可以眼界更加开阔，去尝试接触更多的新事物啊，认识更多的人，领略更美好的风景。并且，哥特让我可以更适应美国生活，提前认知中国学生留美可能遇到的危险和风险，做好万全生理心理准备，成功杀进美利坚。各位学弟学妹呀，学姐在芝加哥哥特等着你们哟。`
        },
        {
          title: '我在兰州',
          author: '陶岚',
          content:
            '我在哥特享受到了独一无二的风景，一路柳暗花明，登凌绝顶。其实，最开始，我是讨厌哥特的，我讨厌哥特的单调，为纠正一个发音让我练习上千遍；我讨厌哥特的冷漠，最冷的冬天都一大早把我叫出被窝；我讨厌哥特的苛刻，一个数学题要寻找多种解法；我讨厌哥特的喧闹，每个课外活动都人潮涌动。本以为没有去美国深造，继续留在国内就读，这段经历会让我倍加厌恶。然而，这段实则荆棘遍布、坎坷崎岖的美式旅程，当我越走越远，却恍然大悟，其实终点处风光无限，阳光明媚。而今，我竟开始怀念，怀念那种单调，怀念那种冷漠，怀念那种苛刻，怀念那种喧闹，更怀念那段专属美式历程，成就了现在更美好的我。'
        }
      ]
    }
  }
}
</script>

<style lang="less">
@media (max-width: 1100px) {
  .story-img {
    height: 600px !important;
    background: url("../assets/img/story.jpg") no-repeat !important;
    background-size: 100% 100%;
  }
  .story {
    display: block !important;
  }
}
.story-img {
  height: 1050px;
  background: url("../assets/img/story2.jpg") no-repeat center;
  background-size: 100% 100%;
}
.story {
  display: none;
  margin-top: -5px;
  background: #d2d3d5;
  h1 {
    font-size: 34px;
    padding: 50px 0 30px 0;
  }
  h3 {
    font-size: 24px;
    padding: 10px 0;
  }
  p {
    line-height: 30px;
  }
  .no-indent {
    text-indent: 0;
  }
}
.story:last-child {
  padding-bottom: 50px;
}
</style>
