<template>
  <div id="About">
    <article>
      <h2>ABOUT ME</h2>
      <p>帅气这个形容词，大概就是为我而创造的吧😏</p>
      <p>谢谢你这么好看还这么关注我鸭！我叫阿飞，你可以亲切的叫我赛飞。</p>
      <p>有必要强调一下！我还没有脱发！大概是写的代码还不够多...</p>
    </article>
    <article>
      <h2>ABOUT SITE</h2>
      <p class="code"><code>前 &nbsp;端：</code><span>Vue + Element</span></p>
      <p class="code"><code>后 &nbsp;端：</code><span>Node + Nuxt + Express + Mongodb</span></p>
      <p class="border"><code>服务器：</code><a href="https://www.aliyun.com/1111/new?userCode=xqfx5ty6" target="_blank">阿里云ECS</a></p>
      <p>这个博客我在从2020开始学习并编写，因为种种原因，磨磨蹭蹭的终于在2022年完成了！我真棒！😂</p>
      <p>这不能怪我...真的...毕竟在学校里抽的时间一边学习和练习确实不多，可能也是因为我太懒了。</p>
    </article>
    <article>
      <h2>ABOUT COPYRIGHT</h2>
      <p>源码开源：<a href="https://github.com" target="_blank">希望未来我也能为开源做贡献。</a></p>
      <p>在注明出处的前提下，本站文章允许非商业用途的转载。</p>
    </article>
    <article>
      <h2>OTHER</h2>
      <p>我是一名还在学习努力提升自己的前段开发工程师，如果有相关事宜的话，可以通过 <a href="/#contact">contact me</a> 联系我。或者可以在👈左侧边栏找到我的联系方式哦。</p>
    </article>
  </div>
</template>

<script>
export default {
  name: "About"
}
</script>

<style lang="less" scoped>

#About{
  article{
    box-sizing: border-box;
    width: 100%;
    margin-bottom: 15px;
    box-shadow: 0 0 4px #ddd;
    padding: 25px 20px;
    background-color: #fff;
    font-family: Quicksand,Microsoft YaHei,sans-serif;
    h2{
      margin-bottom: 15px;
      font-size: 20px;
      letter-spacing: 3px;
      line-height: 24px;
      border-left: 5px solid #73b899;
      text-indent: 10px;
    }
    p{
      text-indent: 2em;
      color: #444;
      font-size: 14px;
      letter-spacing: 4px;
      line-height: 30px;
      code{
        font-family: Quicksand,Microsoft YaHei,sans-serif;
        letter-spacing: 4px;
      }
      a{
        color: #409eff;
        &:hover{
          text-decoration: underline;
        }
      }
    }
    p.code span{
      color: #bd4147;
      background-color: rgba(27,31,35,.05);
      font-weight: 700;
    }
    p.border{
      border-bottom: 1px dotted rgb(170, 170, 170);
    }
  }
}

</style>














