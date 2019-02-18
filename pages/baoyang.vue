<template>
  <div class="baoyang">
    <!--保养管家-->
    <div class="wrap clearfix">
      <div class="m_baoyang_box m_baoyang_box2 fl">
        <h2 class="m_baoyang_tit m_baoyang_tit2"><em>保养管家</em>请正确输入行驶里程和购车日期</h2>

        <form id="orderFrom" action="http://www.chemayi.com/maintain/check.html" method="post">
          <input type="text" style="display:none;">
          <input class="pub-input" value="" type="hidden" name="autocare_carmodel">
          <input class="pub-input" value="" type="hidden" name="car_model">
          <ul class="m_baoyang_input">
            <li class="m_baoyang_input_li">
              <div class="m_baoyang_input_l">行驶里程：</div>
              <div class="m_baoyang_input_r pr">
                <input id="lichengNum" type="text" class="pub-input" name="miles" value="" placeholder-text="请输入行驶里程" style="color: rgb(141, 141, 141);">
                <div class="pub-input_tip">公里</div>
                <div class="err_tip pa" id="lichengTip">
                </div>
              </div>
            </li>
            <li class="m_baoyang_input_li">
              <div class="m_baoyang_input_l">购车时间：</div>
              <div class="m_baoyang_input_r">
                <div class="rule-single-select fl single-select"><div class="boxwrap"><a class="select-tit" href="javascript:;"><span>请选择年</span><i></i></a><div class="select-items" style="display: none;"><ul><li class="selected">请选择年</li><li>2015</li><li>2014</li><li>2013</li><li>2012</li><li>2011</li><li>2010</li><li>2009</li><li>2008</li><li>2007</li><li>2006</li><li>2005</li><li>2004</li><li>2003</li><li>2002</li><li>2001</li><li>2000</li></ul></div><i class="arrow" style="display: none;"></i></div><div class="boxwrap" style="display: none;"><a class="select-tit" href="javascript:;"><span>请选择年</span><i></i></a><div class="select-items" style="display: none;"><ul><li class="selected">请选择年</li><li>2015</li><li>2014</li><li>2013</li><li>2012</li><li>2011</li><li>2010</li><li>2009</li><li>2008</li><li>2007</li><li>2006</li><li>2005</li><li>2004</li><li>2003</li><li>2002</li><li>2001</li><li>2000</li></ul></div><i class="arrow" style="display: none;"></i></div>
                  <select name="byear" datatype="*" sucmsg=" " id="byear" style="display: none;">
                    <option value="">请选择年</option>
                    <option value="2015">2015</option>
                    <option value="2014">2014</option>
                    <option value="2013">2013</option>
                    <option value="2012">2012</option>
                    <option value="2011">2011</option>
                    <option value="2010">2010</option>
                    <option value="2009">2009</option>
                    <option value="2008">2008</option>
                    <option value="2007">2007</option>
                    <option value="2006">2006</option>
                    <option value="2005">2005</option>
                    <option value="2004">2004</option>
                    <option value="2003">2003</option>
                    <option value="2002">2002</option>
                    <option value="2001">2001</option>
                    <option value="2000">2000</option>
                  </select>
                </div>
                <div class="rule-single-select fr single-select"><div class="boxwrap"><a class="select-tit" href="javascript:;"><span>请选择月</span><i></i></a><div class="select-items" style="display: none;"><ul><li class="selected">请选择月</li><li>12</li><li>11</li><li>10</li><li>9</li><li>8</li><li>7</li><li>6</li><li>5</li><li>4</li><li>3</li><li>2</li><li>1</li></ul></div><i class="arrow" style="display: none;"></i></div><div class="boxwrap" style="display: none;"><a class="select-tit" href="javascript:;"><span>请选择月</span><i></i></a><div class="select-items" style="display: none;"><ul><li class="selected">请选择月</li><li>12</li><li>11</li><li>10</li><li>9</li><li>8</li><li>7</li><li>6</li><li>5</li><li>4</li><li>3</li><li>2</li><li>1</li></ul></div><i class="arrow" style="display: none;"></i></div>
                  <select name="bmonth" datatype="*" sucmsg=" " id="bmonth" style="display: none;">
                    <option value="">请选择月</option>
                    <option value="12">12</option>
                    <option value="11">11</option>
                    <option value="10">10</option>
                    <option value="9">9</option>
                    <option value="8">8</option>
                    <option value="7">7</option>
                    <option value="6">6</option>
                    <option value="5">5</option>
                    <option value="4">4</option>
                    <option value="3">3</option>
                    <option value="2">2</option>
                    <option value="1">1</option>
                  </select>
                </div>
                <div class="err_tip pa" id="buycarTime">请选择购车时间</div>
              </div>
            </li>
            <li class="m_baoyang_input_li">
              <div class="m_baoyang_input_l">&nbsp;</div>
              <div class="m_baoyang_input_r pr"> <a href="javascript:void(0)" class="lbt_btn a_org_mid tophysical">查看检测结果</a> </div>
            </li>
          </ul>
        </form>
      </div>
      <div class="by_topbox fr">
        <ul class="item_box item_box2">
          <li class="fl pr pop_dialog_icon_items">
            <a href="http://www.chemayi.com/carmaintainplan/project/pids-1.html" target="_blank">
              <div class="icon_com item_default pa"> 小保养<em>（机油 + 机油滤清器）</em> </div>
              <div class="item_hoverbg"> </div>
              <div class="item_hovertext"> 机油+机油滤清器 </div>
            </a>
          </li>

        </ul>
        <div class="by_tj">
          <h3> <span>通用保养推荐</span> <a href="http://mall.chemayi.com/category.php?id=81#category_tree"><i>+</i>更多推荐</a> </h3>
          <div class="main_service_con by_bj_con">
            <table>
              <tbody><tr>
                <td><div class="by_bj_item ">
                  <div class="by_bj_img fl"><a href="http://mall.chemayi.com/goods.php?id=623" target="_blank"> <img src="images/hx5.jpg"> </a></div>
                  <div class="by_bj_imgr fr">
                    <a href="http://mall.chemayi.com/goods.php?id=623" target="_blank">
                      <h3>汽车小保养服务经济方案A</h3>
                      <p>更换壳牌ＨＸ５机油＋更换品牌机滤</p>
                      <div class="bot"> <span><em>¥</em>264</span><i>¥300</i> </div>
                    </a>
                  </div>
                </div></td>
                <td><div class="by_bj_item ">
                  <div class="by_bj_img fl"><a href="http://mall.chemayi.com/goods.php?id=628" target="_blank"> <img src="images/jmf.jpg"> </a></div>
                  <div class="by_bj_imgr fr">
                    <a href="http://mall.chemayi.com/goods.php?id=628" target="_blank"> <h3>汽车小保养服务豪华方案A</h3>
                      <p>更换美孚金美孚１号机油＋更换品牌机滤</p>
                      <div class="bot"> <span><em>¥</em>557</span><i>¥700</i> </div>
                    </a>
                  </div>
                </div></td>
              </tr>
              </tbody></table>
          </div>
        </div>
      </div>
    </div>
    <!--专项保养开始-->
    <div class="wrap clearfix">
      <div class="main_service by_itembox fl mt20">
        <div class="main_service_tit"> <span>专项保养</span> </div>
        <div class="main_service_con main_service_cons pop_dialog_icon_items">
          <table>
            <tbody><tr>
              <td>
                <a href="http://www.chemayi.com/carmaintainplan/project/pids-5.html" target="_blank">
                  <div class="main_service_item icon_item">
                    <h5>
                      更换燃油滤清器
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://www.chemayi.com/carmaintainplan/project/pids-2.html" target="_blank">
                  <div class="main_service_item icon_item by_icon_item2">
                    <h5>
                      更换机油滤清器
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://www.chemayi.com/carmaintainplan/project/pids-6.html" target="_blank">
                  <div class="main_service_item icon_item by_icon_item3">
                    <h5>
                      更换空气滤清器
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://www.chemayi.com/carmaintainplan/project/pids-11.html" target="_blank">
                  <div class="main_service_item icon_item by_icon_item4">
                    <h5>
                      更换空调滤清器
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://www.chemayi.com/carmaintainplan/project.html" target="_blank">
                  <div class="main_service_item by_minwidth icon_item by_icon_item5">
                    <h5>
                      更换手动变速箱油
                    </h5>
                  </div>
                </a>
              </td>
            </tr>
            <tr>
              <td>
                <a href="http://www.chemayi.com/carmaintainplan/project.html" target="_blank">
                  <div class="main_service_item icon_item by_icon_item6">
                    <h5>
                      更换自动变速箱油
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://www.chemayi.com/carmaintainplan/project/pids-7.html" target="_blank">
                  <div class="main_service_item icon_item by_icon_item7">
                    <h5>
                      更换转向助力油
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://mall.chemayi.com/goods.php?id=2576" target="_blank">
                  <div class="main_service_item icon_item by_icon_item8">
                    <h5>
                      更换防冻液
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://mall.chemayi.com/goods.php?id=59" target="_blank">
                  <div class="main_service_item icon_item by_icon_item9">
                    <h5>
                      加注防冻液
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://mall.chemayi.com/goods.php?id=221" target="_blank">
                  <div class="main_service_item by_minwidth icon_item by_icon_item10">
                    <h5>
                      更换空调制冷剂
                    </h5>
                  </div>
                </a>
              </td>
            </tr>
            <tr>
              <td>
                <a href="http://mall.chemayi.com/goods.php?id=221" target="_blank">
                  <div class="main_service_item icon_item by_icon_item11">
                    <h5>
                      加注空调制冷剂
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://www.chemayi.com/carmaintainplan/project/pids-8.html" target="_blank">
                  <div class="main_service_item icon_item by_icon_item12">
                    <h5>
                      更换刹车油
                    </h5>
                  </div>
                </a>
              </td>
              <td>
                <a href="http://mall.chemayi.com/goods.php?id=55" target="_blank">
                  <div class="main_service_item icon_item by_icon_item17">
                    <h5>
                      底盘装甲
                    </h5>
                  </div>
                </a>
              </td>

            </tr>
            </tbody></table>
        </div>
      </div>
      <div class="by_qjyh fr mt20">
        <div class="main_service_tit "> <span>清洁养护</span> </div>
        <div class="main_service_con by_qjyh_con main_service_cons pop_dialog_icon_items">
          <table>
            <tbody><tr>
              <td>
                <a href="http://mall.chemayi.com/goods.php?id=56" target="_blank">
                  <div class="main_qjyh_item icon_item by_icon_item13">
                    <h5>
                      节气门清洗
                    </h5>
                  </div>
                </a>
              </td>

              <td>
                <a href="http://mall.chemayi.com/goods.php?id=57" target="_blank">
                  <div class="main_qjyh_item icon_item by_icon_item14">
                    <h5>
                      喷油嘴清洗
                    </h5>
                  </div>
                </a>
              </td>
            </tr>
            <tr>
              <td>
                <a href="http://mall.chemayi.com/goods.php?id=29" target="_blank">
                  <div class="main_qjyh_item icon_item by_icon_item15">
                    <h5>
                      发动机内部清洗
                    </h5>
                  </div>
                </a>
              </td>

              <td>
                <a href="http://mall.chemayi.com/goods.php?id=58" target="_blank">
                  <div class="main_qjyh_item icon_item by_icon_item16">
                    <h5>
                      发动机外部清洗
                    </h5>
                  </div>
                </a>
              </td>
            </tr>
            </tbody></table>
        </div>
      </div>
    </div>
    <!--专项套餐-->
    <div class="wrap clearfix ">
      <div class="main_service by_taocanbox fl mt20" id="hot_baoyang">
        <div class="main_service_tit"> <span>车蚂蚁专享车型保养套餐</span><a target="_blank" href="http://mall.chemayi.com/category.php?id=87" class="by_taocan_more"><i>+</i>更多套餐</a> </div>
        <div class="main_service_con main_hot_con">
          <table>
            <tbody><tr>
              <td><div class="main_hot_item min_tc_width"><a target="_blank" href="http://mall.chemayi.com/category.php?id=136"> <img class="lazy" src="images/1.jpg" data-original="http://img.chemayi.com/version63/index/hot_car/skd.jpg"> </a></div></td>
              <td><div class="main_hot_item"><a target="_blank" href="http://mall.chemayi.com/category.php?id=137"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/dzpl.jpg"> </a></div></td>
              <td><div class="main_hot_item"><a target="_blank" href="http://mall.chemayi.com/category.php?id=138"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/xflklz.jpg"> </a></div></td>
              <td><div class="main_hot_item"><a target="_blank" href="http://mall.chemayi.com/category.php?id=142"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/dzbl.jpg"> </a></div></td>
              <td><div class="main_hot_item"><a target="_blank" href="http://mall.chemayi.com/category.php?id=144"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/xdyd.jpg"> </a></div></td>
            </tr>
            <tr>
              <td><div class="main_hot_item min_tc_width"><a target="_blank" href="http://mall.chemayi.com/category.php?id=145"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/bkjw.jpg"> </a></div></td>
              <td><div class="main_hot_item"><a target="_blank" href="http://mall.chemayi.com/category.php?id=146"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/btgy.jpg"> </a></div></td>
              <td><div class="main_hot_item"><a target="_blank" href="http://mall.chemayi.com/category.php?id=149"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/dzst.jpg"> </a></div></td>
              <td><div class="main_hot_item"><a target="_blank" href="http://mall.chemayi.com/category.php?id=150"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/ftfks.jpg"> </a></div></td>
              <td><div class="main_hot_item"><a target="_blank" href="http://mall.chemayi.com/category.php?id=147"> <img class="lazy" src="images/t.gif" data-original="http://img.chemayi.com/version63/index/hot_car/mzd6.jpg"> </a></div></td>
            </tr>
            </tbody></table>
        </div>
      </div>
      <div class="main_bus fr mt20">
        <h3> <span>汽车保养小知识</span> <a target="_blank" href="http://www.chemayi.com/wiki/by/list_1_1.html"><i>+</i>更多知识</a> </h3>
        <ul class="main_by_list">
          <li> <a target="_blank" href="http://www.chemayi.com/wiki/by/486.html">城市里停车有技巧</a> </li>
          <li> <a target="_blank" href="http://www.chemayi.com/wiki/by/519.html">开车安全第一 怎样防止汽车追尾</a> </li>
          <li> <a target="_blank" href="http://www.chemayi.com/wiki/by/526.html">不同路况行车有区别 乡村土路上怎么开车</a> </li>
          <li> <a target="_blank" href="http://www.chemayi.com/wiki/by/510.html">汽车知识小科普 “五油三水”到底指啥</a> </li>
          <li> <a target="_blank" href="http://www.chemayi.com/wiki/by/518.html">您是女车主吗 车蚂蚁有话对您说</a> </li>
          <li> <a target="_blank" href="http://www.chemayi.com/wiki/by/512.html">车蚂蚁网：壳牌机油小保养只需198元</a> </li>
          <li> <a target="_blank" href="http://www.chemayi.com/wiki/by/488.html">这个夏天 你的爱车被车蚂蚁承包了</a> </li>
          <li> <a target="_blank" href="http://www.chemayi.com/wiki/by/469.html">应急修车技巧 教您遇事不用慌</a> </li>
        </ul>
      </div>
    </div>
    <!--子组件-->
    <lonIn></lonIn>
  </div>
</template>

<script>
  import lonIn from "@/components/logIn/logIn.vue"
  export default {
    components: {
      lonIn
    }
  }
</script>

<style>
  @import "@/assets/zhangqmcss/929fce5888dcb6d8980fc7174f81d92d.css";
  @import "@/assets/zhangqmcss/9a3fbe3acd45615db0b546121dd02187.css";
</style>
