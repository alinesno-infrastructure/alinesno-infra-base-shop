<template>
    <div>
        <el-row class="acp-dashboard-panel" :gutter="20">

            <el-col class="panel-col" :span="12">
                <div class="grid-content">
                    <div class="panel-header">
                        <div class="header-title"><i class="fa-solid fa-link"></i> 最新运行统计</div>
                    </div>
                    <div class="panel-body acp-height-auto">

                        <div class="count-box">
                            <ul>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">今日订单总数</div>
                                    <div class="count-box-item-number">280</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">今日销售总额</div>
                                    <div class="count-box-item-number">￥5000.00</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">昨日销售总额</div>
                                    <div class="count-box-item-number">￥5000.00</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">待处理退货订单</div>
                                    <div class="count-box-item-number">280</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">待确认收货订单</div>
                                    <div class="count-box-item-number">280</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">待处理退款申请</div>
                                    <div class="count-box-item-number">280</div>
                                </li>
                            </ul>
                        </div>

                    </div>
                </div>
            </el-col>
            <el-col class="panel-col" :span="12">
                <div class="grid-content">
                    <div class="panel-header">
                        <div class="header-title"><i class="fa-solid fa-link"></i> 商品运行总览</div>
                    </div>
                    <div class="panel-body acp-height-auto">

                        <div class="count-box">
                            <ul>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">全部商品</div>
                                    <div class="count-box-item-number">500</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">商品已上架</div>
                                    <div class="count-box-item-number">400</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">商品已下架</div>
                                    <div class="count-box-item-number">100</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">新增订单</div>
                                    <div class="count-box-item-number">500</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">总订单量</div>
                                    <div class="count-box-item-number">400</div>
                                </li>
                                <li class="count-box-item">
                                    <div class="count-box-item-title">退款订单</div>
                                    <div class="count-box-item-number">100</div>
                                </li>
                            </ul>
                        </div>

                    </div>
                </div>
            </el-col>


        </el-row>

    </div>
</template>