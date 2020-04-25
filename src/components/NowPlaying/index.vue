<template>
    <div class="movie_body">
        <ul>
            <li>
                <div class="pic_show"><img src="@/assets/LordOfTheFlies.jpeg" alt=""></div>
                <div class="info_list">
                    <h2>蝇王</h2>
                    <p>观众评<span class="grade">9.2</span></p>
                    <p>主演：Chris Furrh，Danuel Pipoly</p>
                    <p>今天55家影院放映607场</p>
                </div>
                <div class="btn_mall">
                    购票
                </div>
            </li>
            <li>
                <div class="pic_show"><img src="@/assets/TheGodFather.jpeg" alt=""></div>
                <div class="info_list">
                    <h2>教父</h2>
                    <p>观众评<span class="grade">9.9</span></p>
                    <p>主演：马龙·白兰度，阿尔·帕西诺</p>
                    <p>今天55家影院放映907场</p>
                </div>
                <div class="btn_mall">
                    购票
                </div>
            </li>
            <li>
                <div class="pic_show"><img src="@/assets/LordOfTheFlies.jpeg" alt=""></div>
                <div class="info_list">
                    <h2>蝇王</h2>
                    <p>观众评<span class="grade">9.2</span></p>
                    <p>主演：Chris Furrh，Danuel Pipoly</p>
                    <p>今天55家影院放映607场</p>
                </div>
                <div class="btn_mall">
                    购票
                </div>
            </li>
            <li>
                <div class="pic_show"><img src="@/assets/TheGodFather.jpeg" alt=""></div>
                <div class="info_list">
                    <h2>教父</h2>
                    <p>观众评<span class="grade">9.9</span></p>
                    <p>主演：马龙·白兰度，阿尔·帕西诺</p>
                    <p>今天55家影院放映907场</p>
                </div>
                <div class="btn_mall">
                    购票
                </div>
            </li>
            <li>
                <div class="pic_show"><img src="@/assets/LordOfTheFlies.jpeg" alt=""></div>
                <div class="info_list">
                    <h2>蝇王</h2>
                    <p>观众评<span class="grade">9.2</span></p>
                    <p>主演：Chris Furrh，Danuel Pipoly</p>
                    <p>今天55家影院放映607场</p>
                </div>
                <div class="btn_mall">
                    购票
                </div>
            </li>
            <li>
                <div class="pic_show"><img src="@/assets/TheGodFather.jpeg" alt=""></div>
                <div class="info_list">
                    <h2>教父</h2>
                    <p>观众评<span class="grade">9.9</span></p>
                    <p>主演：马龙·白兰度，阿尔·帕西诺</p>
                    <p>今天55家影院放映907场</p>
                </div>
                <div class="btn_mall">
                    购票
                </div>
            </li>
            <li>
                <div class="pic_show"><img src="@/assets/LordOfTheFlies.jpeg" alt=""></div>
                <div class="info_list">
                    <h2>蝇王</h2>
                    <p>观众评<span class="grade">9.2</span></p>
                    <p>主演：Chris Furrh，Danuel Pipoly</p>
                    <p>今天55家影院放映607场</p>
                </div>
                <div class="btn_mall">
                    购票
                </div>
            </li>
            <li>
                <div class="pic_show"><img src="@/assets/TheGodFather.jpeg" alt=""></div>
                <div class="info_list">
                    <h2>教父</h2>
                    <p>观众评<span class="grade">9.9</span></p>
                    <p>主演：马龙·白兰度，阿尔·帕西诺</p>
                    <p>今天55家影院放映907场</p>
                </div>
                <div class="btn_mall">
                    购票
                </div>
            </li>
        </ul>
    </div>
</template>
<script>
    export default {
        name: 'NowPlaying'
    }
</script>
<style scoped>
    #content .movie_body{flex:1;overflow:auto;}
    .movie_body ul{margin:0 12px;overflow: hidden;}
    .movie_body ul li{margin-top:0px;display: flex;align-items:center;border-bottom:1px #e6e6e6 solid; padding-bottom:10px;}
    .movie_body .pic_show{width:64px;height: 90px;}
    .movie_body .pic_show img{width:100%;}
    .movie_body .info_list{margin-left:10px; flex:1;position:relative;}
    .movie_body .info_list h2{font-size:17px;line-height:22px;width:200px;overflow:hidden;white-space: nowrap;text-overflow: ellipsis;}
    .movie_body .info_list p{font-size: 13px;color:#666;line-height: 22px;width: 200px;overflow: hidden;white-space: nowrap; text-overflow:ellipsis;}
    .movie_body .info_list .grade{font-weight: 700; color: #faaf00;font-size: 15px;}
    .movie_body .info_list img{width: 50px;position: absolute;right: 10px;top: 5px;}
    .movie_body .btn_mall, .movie_body .btn_pre{width: 47px;height: 27px;line-height: 28px;text-align: center; background-color:#fff ;}
    .movie_body .btn_pre{background-color: #3c9fe6;}
</style>