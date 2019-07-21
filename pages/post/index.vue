<template>
    <div class="lygl">
        <!-- 左边 -->
        <div class="zuo"></div>

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
export default {
    
}
</script>

<style lang="less" scoped>
    .lygl{
        width: 1000px;
        margin: 0 auto;
        // background-color: #000;
        .zuo{
            width: 265;
            height: 300px;
            background-color: #333;
            margin: 0 0;
        }


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

