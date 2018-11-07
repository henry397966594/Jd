<template>
  <div>
      <Panel title="极速借贷" :class="$style.panel">
          <section :class="$style.content">
              <router-link :to="{name:'home'}">
                  <img src="//img12.360buyimg.com/jrpmobile/jfs/t19756/137/1902911799/17823/e19ffe7b/5add9511Nf6984e89.jpg?width=750&height=200" >
              </router-link>
          </section>
      </Panel>
  </div>
</template>

<script>
import Panel from '../core/panel'
export default {
  data() {
    return {

    }
  },
  components: {
      Panel
  }
}
</script>

<style lang="scss" module>
@import "../../css/element.scss" ;
 .panel{
     @include panel;
     .content{
        padding-bottom: 40px;
        img{
            display: block;
            width: 100%
        }
     }
 }

</style>
