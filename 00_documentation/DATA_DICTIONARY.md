# 数据字典

## 模型评价

- `model_summary_three_scales.csv`：三个空间尺度的主模型汇总。
- `model_1to1_summary.csv`：合并折外样本的拟合摘要。
- `*_model_summary.csv`：单一尺度八类模型完整汇总。
- `*_moran_summary.csv`：折外残差全局 Moran's I。

## SHAP

- `shap_importance_by_scale.csv`：九因子平均绝对 SHAP 与归因份额。
- `entropy_summary.csv`：三尺度平均归因熵、主导因子及覆盖比例。
- `shap_pdp_summary.csv`：PDP 曲线诊断。
- `shap_ring_sector_profiles.csv`：环带和扇区 SHAP 剖面。
- `*_shap_mk_summary.csv`：单尺度 SHAP 趋势检验摘要。
- `cross_scale_agreement.csv`：SHAP 空间贡献的跨尺度一致性。
- `feature_level_rank_agreement.csv`：因子层级跨尺度排序一致性。
- `spatial_dispersion.csv`：SHAP 空间分布与符号统计。
- `grid_layers_*.csv`：各尺度格网级汇总数据。

## 扩张、形态与方向

- `morphology_*.csv`：新增斑块形态、景观扩张指数和尺度效应结果。
- `direction_*.csv`：扩张方向、标准差椭圆、质心迁移和方向相关分析。
- `三尺度扩张指数*.csv`：全市与格网级扩张趋势检验。
- `三尺度四期扩张强度热点*.csv`：四期 hotspots 汇总与格网数据。

## 空间数据

- `boundaries/`：行政边界、城镇开发边界和图幅边界。
- `centroids/`：扩张重心点与轨迹。
- `expansion_patterns/`：扩张模式格网与形态分类栅格。
- `hotspots/`：三尺度四期热点格网。
- `intensity/`：三尺度扩张强度格网。
- `drivers/shap/`：三尺度 SHAP 空间贡献格网。
- `statistics/`：区县和全市统计汇总。

## 坐标与单位

- GeoJSON 展示几何为 EPSG:4326。
- GeoTIFF 保留文件内原始 CRS。
- 990 m 和 1500 m 面板使用比例口径；3000 m 面板为百分点，跨尺度比较应使用标准化字段。
