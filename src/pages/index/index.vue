<template>
  <view class="index">
    <text>{{ msg }}</text>
    <AtButton type="primary">按钮文案</AtButton>
    <text>1234567</text>
  </view>
</template>
<script>
import { ref } from "vue";
// import { AtButton } from "taro-ui";
import "./index.scss";

export default {
  setup() {
    const msg = ref("Hello world");
    return {
      msg,
    };
  },
};
</script>
