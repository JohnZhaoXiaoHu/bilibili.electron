<!--
 * @公司名: 北京雨花石云计算
 * @Description: 我的消息
 * @Author: MArio
 * @Date: 2021-10-06 09:55:45
 * @LastEditTime: 2021-10-07 15:54:14
 * @LastEditors: MArio
-->
<template>
  <div id="myNews">
    <div class="Searchbox">
      <!-- 搜索条 -->
      <div class="zuijinSo loading">
        <div class="tubiaoS"></div>
        <div class="tubiaoK"></div>
      </div>
      <div
        class="shuaXin"
        :style="backColor"
        @mousemove="onmouseoverSha"
        @mouseout="onmouseoutSha"
      >
        SH
      </div>
    </div>
    <div class="titleFast">
      我的消息
    </div>
    <div class="tableFast">
      <table>
        <tr>
          <td>
            <div class="tableCard loading">
              <div class="tableTop">
                <div class="tableIcon"></div>
                <div class="tableText"></div>
              </div>
              <div class="tableBottom"></div>
            </div>
          </td>
          <td>
            <div class="tableCard loading">
              <div class="tableTop">
                <div class="tableIcon"></div>
                <div class="tableText"></div>
              </div>
              <div class="tableBottom"></div>
            </div>
          </td>
          <td>
            <div class="tableCard loading">
              <div class="tableTop">
                <div class="tableIcon"></div>
                <div class="tableText"></div>
              </div>
              <div class="tableBottom"></div>
            </div>
          </td>
        </tr>
      </table>
    </div>
    <div class="CardFast scro">
      <table>
        <tr>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
          <td>
            <div class="XiaoCard loading">
              <div class="XiaoT">
                <div class="XiaoIcon"></div>
                <div class="XiaoTitle"></div>
                <div class="XiaoDtime"></div>
              </div>
              <div class="XiaoPin"></div>
              <div class="XiaoH"></div>
              <div class="XiaoWen"></div>
            </div>
          </td>
        </tr>
      </table>
    </div>
  </div>
</template>


<script>
export default {
  name: "myNews",
  data() {
    return {
      backColor: "",
    };
  },
  methods: {
    onmouseoverSha() {
      this.backColor = " background-color: #fff;";
    },
    onmouseoutSha() {
      this.backColor = " background-color: #dee5eb;";
    },
  },
};
</script>

<style>
.XiaoCard {
  width: 290px;
  height: 180px;
  background-color: #fff;
  border-radius: 6px;
  overflow: hidden;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.12);
  margin: 5px;
}
.XiaoWen {
  width: 93%;
  height: 65px;
  margin-left: 10px;
  margin-top: 8px;
  border-radius: 6px;
}
.XiaoH {
  width: 100px;
  height: 20px;
  margin-left: 10px;
  border-radius: 6px;
  margin-top: 8px;
}
.XiaoPin {
  width: 170px;
  height: 20px;
  margin-left: 10px;
  border-radius: 6px;
}
.XiaoT {
  height: 50px;
  width: 100%;
}
.XiaoIcon {
  width: 35px;
  height: 35px;
  border-radius: 35px;
  float: left;
  margin-left: 10px;
  margin-top: 8px;
}
.XiaoTitle {
  width: 70px;
  height: 15px;
  float: left;
  margin-left: 8px;
  margin-top: 18px;
  border-radius: 6px;
}
.XiaoDtime {
  width: 40px;
  height: 15px;
  float: right;
  margin-right: 8px;
  margin-top: 18px;
  border-radius: 6px;
}

#myNews {
  height: 100%;
  width: 100%;
}
.Searchbox {
  height: 50px;
  /* background-color: aqua; */
}
.CardFast {
  margin-left: 45px;
  width: 90%;
  height: 75%;
  overflow-y: scroll;
}
.titleFast {
  margin-left: 45px;
  height: 50px;
  width: 88%;
  text-align: left;
  font-size: 35px;
  font-family: cursive;
}
.tableCard {
  width: 100px;
  height: 33px;
  background-color: #fff;
  border-radius: 6px;
  overflow: hidden;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.12);
  margin: 5px;
}
.tableBottom {
  margin-left: 10px;
  width: 80%;
  height: 4px;
  background-color: #ed5b8c;
}
.tableTop {
  height: 24px;
}
.tableIcon {
  width: 20px;
  height: 15px;
  background-color: #ed5b8c;
  margin-left: 10px;
  margin-top: 5px;
  float: left;
  border-radius: 6px;
}
.tableText {
  width: 50px;
  height: 15px;
  background-color: #ed5b8c;
  margin-left: 6px;
  margin-top: 5px;
  float: left;
}
.tableFast {
  margin-left: 45px;
  width: 88%;
  height: 50px;
}
@keyframes loading {
  to {
    background-position-x: -20%;
  }
}
.loading .tableIcon,
.loading .tableText,
.loading .XiaoIcon,
.loading .XiaoTitle,
.loading .XiaoDtime,
.loading .XiaoPin,
.loading .XiaoH,
.loading .XiaoWen,
.loading .tableBottom {
  background-color: var(--loading-grey);
  background: linear-gradient(
      100deg,
      rgba(255, 255, 255, 0) 40%,
      rgba(255, 255, 255, 0.5) 50%,
      rgba(255, 255, 255, 0) 60%
    )
    var(--loading-grey);
  background-size: 200% 100%;
  background-position-x: 180%;
  animation: 1s loading ease-in-out infinite;
}

.scro {
  /* height: 430px; */
  overflow-y: scroll;
}
.scro::-webkit-scrollbar {
  /*滚动条整体样式*/
  width: 7px;
  /*高宽分别对应横竖滚动条的尺寸*/
  height: 1px;
}

.scro::-webkit-scrollbar-thumb {
  /*滚动条里面小方块*/
  border-radius: 10px;
  -webkit-box-shadow: inset 0 0 5px rgba(235, 238, 240, 0.2);
  background: #ebeef0;
}

.scro::-webkit-scrollbar-track {
  /*滚动条里面轨道*/
  -webkit-box-shadow: inset 0 0 5px rgba(235, 238, 240, 0.2);
  border-radius: 10px;
  background: #f1f6fa;
}
.zuijinSo {
  float: left;
  margin-left: 45px;
  width: 345px;
  height: 40px;
  border-radius: 45px;
  background-color: #fff;
  overflow: hidden;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.12);
}
.shuaXin {
  float: right;
  margin-right: 45px;
  margin-top: 5px;
  background-color: #dee5eb;
  width: 45px;
  height: 45px;
  text-align: center;
  padding-top: 10px;
  border-radius: 45px;
  cursor: default;
}
.tubiaoS {
  height: 32px;
  width: 32px;
  background-color: rgba(245, 243, 243, 0.795);
  margin-top: 5px;
  margin-left: 5px;
  border-radius: 32px;
  float: left;
}
.tubiaoK {
  float: left;
  width: 250px;
  height: 32px;
  background-color: rgb(245, 243, 243);
  margin-top: 5px;
  margin-left: 5px;
}
</style>
