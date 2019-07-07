<template>
  <div class="">
    <div class="container">
      <div w-750-400 aspectratio aspect-ratio="750/400">
        <div aspectratio-content>
          <img src="https://ysm.onedisme.com/daycms/public/uploads/427a8abe4a53101271d755500261e869.jpg" alt="">
          <!--<img src="//gw.alicdn.com/imgextra/i1/82/TB2M_c0jmB0XKJjSZFsXXaxfpXa_!!82-0-luban.jpg_q50.jpg" alt="">-->
        </div>
      </div>
      <div class="nav-wrap">
        <ul>
          <li w-180>
            <img src="https://ysm.onedisme.com/daycms/public/uploads/d6eedd2261da3be0cea99c36f222605b.png" alt="">
            <p>中考培训</p>
          </li>
          <li w-180>
            <img src="https://ysm.onedisme.com/daycms/public/uploads/de3f1c1448408462aa80a4ae07e5595e.png" alt="">
            <p>艺术培训</p>
          </li>
          <li w-180>
            <img src="https://ysm.onedisme.com/daycms/public/uploads/d6eedd2261da3be0cea99c36f222605b.png" alt="">
            <p>高考速成</p>
          </li>
          <li w-180>
            <img src="https://ysm.onedisme.com/daycms/public/uploads/d6eedd2261da3be0cea99c36f222605b.png" alt="">
            <p>语言兴趣</p>
          </li>
        </ul>
      </div>
      <div class="block">
        <div class="course-list">
          <div w-250-180 aspectratio>
            <div aspectratio-content>
              <img src="https://ysm.onedisme.com/dayapi/public/uploads/fileimg/bae4b428c6d1843c9d61b540d27a66f5.jpg" alt="">
            </div>
          </div>
          <div class="right">
            <h2 class="title">测试课程2</h2>
            <div class="desc">范德萨范德萨发fgfdghy6thu高大哥大哥股份的三个人范德萨范德萨发fgfdghy6thu高大哥大哥股份的三个人</div>
            <div class="number">开班人数: 10</div>
            <div class="bottom">
              <div>
                <span>学前幼儿</span>
                <span>10课时</span>
              </div>
              <div class="price">￥100</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
    export default {}
</script>

<style>
  [w-750-400] {
    width: 750px;
  }
  [w-750-400] {
    aspect-ratio: '750:400'
  }
  .nav-wrap {
    position: relative;
    margin: -50px 15px 0;
    background-color: #fff;
    border-radius: 8px;
  }
  .nav-wrap ul {
    display: flex;
  }
  [w-180] {
    width: 180px;
    padding: 15px;
    text-align: center;
  }
  .nav-wrap p {
    margin: 10px 0;
    font-size: 30px;
  }
  .course-list {
    display: flex;
    margin: 10px 15px;
    padding: 20px;
    border-radius: 8px;
    background-color: #fff;
  }
  [w-250-180] {
    width: 250px;
  }
  [w-250-180] {
    aspect-ratio: '250:180';
  }
  .course-list .right {
    flex: 1;
    padding-left: 20px;
  }
  .course-list .right .title {
    font-size: 32px;
    margin: 0;
  }
  .course-list .right .desc {
    font-size: 28px;
    color: #999;
    overflow: hidden;
    text-overflow: ellipsis;
    word-break: break-all;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .course-list .right .number {
    font-size: 28px;
  }
  .bottom {
    display: flex;
    justify-content: space-between;
  }
  .bottom span {
    font-size: 24px;
    background-color: #e5f2ff;
    color: #1482f0;
  }
  .bottom .price {
    color: #ff6060;
    font-size: 32px;
  }
</style>
