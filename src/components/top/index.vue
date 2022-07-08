<template>
  <view class="content">
    <text class="title">
      {{ title }}
    </text>
  </view>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data() {
    return {
      title: 'Hello',
    }
  },
  onLoad() {},
  methods: {},
})
</script>

<style>
.title {
  display: flex;
  align-items: center;
  justify-content: center;
}

.title {
  font-size: 36rpx;
  color: #8f8f94;
}
</style>
