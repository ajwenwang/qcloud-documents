<style>
  table th:nth-of-type(1)
{width:145px;}
  table th:nth-of-type(2)
{width:200px;}
  table th:nth-of-type(3)
{width:200px;}
  table th:nth-of-type(4)
{width:200px;}
  table th:nth-of-type(5)
{width:145px;}
</style>

| 支持模式 | 详细内容    | 适用场景  |  调用方式   |
| -------| ----------- | -------- |  -------- |
| 自拍照+身份信息模式 | 1. 客户上送自拍照 、姓名、身份证号信息<br/>2. 腾讯云将依据此信息拉取权威比对源照片与上送自拍照比对，核实是否为本人 | 核实自拍照是否为本人的相关业务       | API 调用      |
| 自拍照+比对照模式   | 1. 客户上送自拍照、比对照两张照片<br/>2. 腾讯云将两张照片进行比对，核实是否为同一个人 | 核实两张照片是否为同一个人的相关业务 | API 调用      |
| 二要素验证          | 1. 客户上送姓名、身份证号信息<br/>2. 腾讯云将依据此信息查询权威数据源，核实二要素是否匹配 | 核实姓名与身份证是否匹配的相关业务   | API 调用      |
