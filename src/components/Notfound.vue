<template>
    <div>
        <div class="not">当前页面不存在,请检查网址是否正确
        </div>
        <div class="back">
            <router-link to="/money">返回首页</router-link>
        </div>
    </div>

</template>

<script lang="ts">
  export default {
    name: 'Notfound'
  };
</script>

<style scoped lang="scss">
    .not{
        text-align:center;
    }
    .back{
        margin-left: 50%;
        left:50%;
    }
</style>