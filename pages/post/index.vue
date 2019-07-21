<template>
    <div class="lygl">
        <!-- 左边 -->
        <Zuo/>

        <!-- 右边 -->
        <div class="you">
            <!-- 上面 -->
            <div class="sm">
                
            </div>
            <!-- 下面 -->
            <div class="xm">

            </div>
        </div>
    </div>


</template>

<script>

import Zuo from "@/components/post/zuo.vue";

export default {
    components: {
        Zuo,
    }
}
</script>

<style lang="less" scoped>
    .lygl{
        width: 1000px;
        margin: 15px auto;
        // background-color: #000;

        .you{
            width: 735px;
            height: 1000px;
            background-color: #0094ff;
            margin: -300px 265px;

            .sm{
                width: 765px;
                height: 140px;
                background-color: red;
            }

            .xm{ 
                width: 765px;
                height: 1000px;
                background-color: #97a87f;
            }
        }
    }
</style>

