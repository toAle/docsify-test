### 首页<!-- {docsify-ignore-all} -->

在首页集成各模块业务当前状况，汇总各店铺数据QQQQQQQQQQQQQQ

##### 1. 销量分析& 即时销售情况

展示所有筛选条件的数据，取值来源：销量统计

1.  图形上的折线可以点击指标来控制显示和隐藏，图形的横轴是所选择的时间范围按日展开
2.  鼠标移入图形可以查看对应日期的数据
3.  鼠标移入环比数据可以查看环比的具体日期范围
4.  点击跳转销量分析模块
5.  即时销售情况也就是选择今日实时的销量分析，数据源与更新频率和销量分析都一样
6.  当选择的时间包含今日时，图形不包含今日的数据，今日的概念由所选择的国家/店铺决定，比如 4.6 上午 10 点，选择日本，那么今日是 4.6，图形将画到 4.5 的数据，选择美国，那么今日是 4.5，图形将画到 4.4 的数据，此逻辑只影响图形，不影响卡片

##### 2. 广告表现& 即时广告情况

筛选条件应用：国家、店铺、日期<br>
取值来源：广告报表，以广告活动为粒度汇总，包括 SP SB SD 数据<br>

1. 图形上的折线可以点击指标来控制显示和隐藏，图形的横轴是所选择的时间范围按日展开
2. 鼠标移入图形可以查看对应日期的数据
3. 点击跳转 SP 广告报表模块
4. 即时广告情况也就是选择今日时的广告表现，数据源与更新频率都一样

##### 3. 库存状况

取值来源：<br>
在库总数量 = FBA 可用库存 + 海外仓可用 + 本地可用<br>
上月仓储费取自月仓储费报表，取当前月份的上月的数据<br>
上月预计长期仓储费取自长期仓储费报表，取当前月份的上月的数据<br>
FBA 可用库存取【设置】模块【业务配置】仓库中设置的 FBA 可用库存计算公式，FBA 在途取 FBA 标发在途<br>
FBA 货值 = 采购成本 \* 数量<br>
海外仓和本地仓可用取库存明细可用，在途取调拨在途，对应货值取自库存明细。<br>

1. 点击右上角可以切换查看数量或货值
2. 鼠标移入条形图可以查看在途在库详细的数量/货值
3. 鼠标移入上月仓储费的感叹号可以查看上月预计长期仓储费
4. 点击标题跳转库存明细
