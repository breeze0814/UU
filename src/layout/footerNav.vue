<template>
  <div class="footer">
    <p class="intro rflex">
      <span>UU Admin</span>
      
    </p>
    <p class="beian">沪ICP备1008611号</p>
  </div>
</template>

<script>
import { github } from '@/utils/env'

export default {
  name: 'footerNav',
  data() {
    return {
      github: github,
    }
  },
  methods: {},
}
</script>

<style lang="less">
.footer {
  width: 100%;
  padding: 10px 0;
  font-size: 12px;
  text-align: center;
  background: #fff;
  p {
    line-height: 30px;
  }
  .intro {
    width: 240px;
    margin: 0 auto;
    justify-content: space-between;
    align-items: center;
  }
}
</style>
