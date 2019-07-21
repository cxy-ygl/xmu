<template>
<div class="zuo">
    <div class="san">
        <div class="yi">
            <span>热门城市</span>
        </div>
        <div class="er">
            <span>推荐城市</span>
        </div>
        <div class="sen">
            <span>奔向海岛</span>
        </div>
        <div class="ser">
            <span>主题推荐</span>
        </div>
    </div>

    <div class="xm">
        <div class="tjcs">
            <span>推荐城市</span>
            <div class="imge">
                <img src="http://157.122.54.189:9093/images/pic_sea.jpeg" alt="">
            </div>
            
        </div>
    </div>
</div>

</template>

<script>
export default {
    
}
</script>

<style lang="less" scoped>
    .zuo{
        width: 265px;
        height: 300px;
        // background-color: #333;
        margin: 0 0;

        .san{
            margin-bottom: 15px;
            div{
                width: 100%;
                height: 40px;
                padding: 10px;
                font-size:14px;
                border: 1px #eee solid
            }
        }



        .xm{
            .tjcs{
                width: 265px;
                height: 300px;
                margin-right: 10px;
                span{
                    width: 100%;
                    border-bottom: 1px #ddd solid; 
                }
                .imge{
                    margin-top:10px; 
                    img{
                        width: 100%;
                        height: 100%;
                    }
                }


            }
        }
    }
</style>


