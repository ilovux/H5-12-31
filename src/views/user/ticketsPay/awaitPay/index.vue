<template>
  <div class="app">
    <van-nav-bar title="订单详情" fixed>
      <van-icon name="cross" slot="left" />
      <van-icon name="ellipsis" slot="right" />
    </van-nav-bar>
    <div class="kong"></div>
    <div class="big">
      <div class="big1">
        <div class="wulan">乌兰察布体育馆</div>
        <img src="../../../../assets/system-wait-L.png" alt />
        <div class="quxiao">待支付（08：28）</div>
      </div>
      <div class="big2">内蒙古自治区乌兰察布市集宁区格根西街近乌兰察布图书馆</div>
    </div>
    <div class="piao_name">
      <div class="piao_name_1">羽毛球-散客单人票</div>
      <div class="piao_name_2">
        <div class="piao_name_2_1">门票类型</div>
        <div class="piao_name_2_2">成人票</div>
      </div>
      <div class="piao_name_2">
        <div class="piao_name_2_1">订单价格</div>
        <div class="piao_name_2_2">￥15.00元</div>
      </div>
      <div class="piao_name_2">
        <div class="piao_name_2_1">可用时间</div>
        <div class="piao_name_2_2">周一至周日可用 07:30-23:00</div>
      </div>
      <div class="piao_name_2">
        <div class="piao_name_2_1">有效日期</div>
        <div class="piao_name_2_2">2020年10月30日-2029年10月30日</div>
      </div>
      <div class="piao_name_2">
        <div class="piao_name_2_1">购买数量</div>
        <div class="piao_name_2_2">X1</div>
      </div>
    </div>
    <div class="bom">
        <div class="left">合计金额</div>
        <div class="right">￥15.00</div>
    </div>
    <div class="an_niu">
      <div class="shi_fu">实付金额：</div>
      <div class="jin_e">352.00</div>
      <button>立即支付</button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.app {
  background-color: #f5f6f7;
  height: 667px;
  padding-bottom: 50px;
}
.kong {
  height: 54px;
  background-color: #f5f6f7;
}
.big {
  background-color: #fff;
  border-bottom: 1px solid #f5f6f7;
  .big1 {
    display: flex;
    justify-content: space-between;
    padding: 16px 12px 4px 10px;
    .wulan {
      flex: 7;
      height: 22px;
      font-size: 16px;
      font-family: PingFangSC-Medium, PingFang SC;
      font-weight: 500;
      color: rgba(46, 47, 51, 1);
      line-height: 22px;
    }
    img {
      width: 18px;
      height: 18px;
      margin-top: 3px;
      margin-right: 3px;
    }
    .quxiao {
      flex: 5;
      height: 22px;
      font-size: 16px;
      font-family: PingFangSC-Medium, PingFang SC;
      font-weight: 500;
      color: rgba(255, 77, 79, 1);
      line-height: 22px;
    }
  }
  .big2 {
    width: 338px;
    height: 18px;
    font-size: 13px;
    font-family: PingFangSC-Regular, PingFang SC;
    font-weight: 400;
    color: rgba(138, 140, 153, 1);
    line-height: 18px;
    padding-left: 10px;
    margin-bottom: 12px;
  }
}
.piao_name {
  display: flex;
  flex-direction: column;
  background-color: #fff;
  border-bottom: 1px solid #f5f6f7;
  padding: 15px 12px 0 12px;
  .piao_name_1 {
    width: 200px;
    height: 22px;
    font-size: 16px;
    font-family: PingFangSC-Medium, PingFang SC;
    font-weight: 500;
    color: rgba(46, 47, 51, 1);
    line-height: 22px;
    margin-bottom: 9px;
  }
  .piao_name_2 {
    display: flex;
    .piao_name_2_1 {
      width: 56px;
      height: 20px;
      font-size: 14px;
      font-family: PingFangSC-Regular, PingFang SC;
      font-weight: 400;
      color: rgba(138, 140, 153, 1);
      line-height: 20px;
      margin-bottom: 5px;
      margin-right: 4px;
    }
    .piao_name_2_2 {
      width: 250px;
      height: 20px;
      font-size: 14px;
      font-family: PingFangSC-Regular, PingFang SC;
      font-weight: 400;
      color: rgba(46, 47, 51, 1);
      line-height: 20px;
    }
  }
}
.bom {
    display: flex;
    height: 44px;
    align-items: center;
    background-color: #fff;
    padding: 0 12px;
    .left {
        height:22px;
        font-size:14px;
        font-family:PingFangSC-Regular,PingFang SC;
        font-weight:400;
        color:rgba(92,93,102,1);
        line-height:22px;
        flex: 5;
    }
    .right {
        width:71px;
        height:22px;
        font-size:16px;
        font-family:SFProText-Medium,SFProText;
        font-weight:500;
        color:rgba(250,100,0,1);
        line-height:19px;
        text-align: right;
        flex: 5;
    }
}
.an_niu {
    position: fixed;
    bottom: 0;
}
</style>
