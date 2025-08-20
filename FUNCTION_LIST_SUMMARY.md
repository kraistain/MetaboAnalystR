# MetaboAnalystR项目R文件夹函数列表

根据请求，已提取MetaboAnalystR项目中R文件夹内所有.R文件中的函数名称。

## 总体统计

- **总R文件数**: 96个
- **总函数数**: 1858个
- **平均每文件函数数**: 约19个

## 各文件函数数量统计

| 文件名 | 函数数量 |
|--------|----------|
| batch_effect_utils.R | 127个函数 |
| biomarker_utils.R | 79个函数 |
| depends_refs.R | 13个函数 |
| dose_response_deanal.R | 16个函数 |
| dose_response_general.R | 21个函数 |
| dose_response_graphs.R | 10个函数 |
| dose_response_utils.R | 32个函数 |
| duplicates_estimates.R | 5个函数 |
| enrich_graphics.R | 16个函数 |
| enrich_integ.R | 30个函数 |
| enrich_kegg.R | 17个函数 |
| enrich_mset.R | 17个函数 |
| enrich_name_match.R | 16个函数 |
| enrich_path_graphics.R | 20个函数 |
| enrich_path_stats.R | 19个函数 |
| enrich_stats.R | 32个函数 |
| gene_fun_utils.R | 4个函数 |
| general_anot_utils.R | 19个函数 |
| general_data_utils.R | 61个函数 |
| general_lib_utils.R | 26个函数 |
| general_misc_utils.R | 85个函数 |
| general_norm_utils.R | 30个函数 |
| general_proc_utils.R | 35个函数 |
| generic_c_utils.R | 3个函数 |
| meta_data_utils.R | 17个函数 |
| meta_methods.R | 29个函数 |
| meta_pathway.R | 44个函数 |
| mgwas_data.R | 28个函数 |
| mgwas_misc.R | 9个函数 |
| mgwas_mr.R | 32个函数 |
| mgwas_tr.R | 20个函数 |
| multifac_asca_heatmap2.R | 37个函数 |
| multifac_covariate.R | 29个函数 |
| multifac_mb.R | 15个函数 |
| multifac_metadata.R | 20个函数 |
| multifac_pca_anova2.R | 22个函数 |
| networks_enrich.R | 8个函数 |
| networks_view.R | 39个函数 |
| others_lipomics.R | 4个函数 |
| peaks_ms2fun.R | 4个函数 |
| peaks_to_function.R | 79个函数 |
| plotly_utils.R | 10个函数 |
| power_utils.R | 6个函数 |
| rpackage_config.R | 0个函数 |
| spectra_processing.R | 76个函数 |
| stats_chemometrics.R | 93个函数 |
| stats_classification.R | 24个函数 |
| stats_clustering.R | 19个函数 |
| stats_correlations.R | 19个函数 |
| stats_opls.R | 4个函数 |
| stats_peaks.R | 2个函数 |
| stats_plot3d.R | 4个函数 |
| stats_sigfeatures.R | 23个函数 |
| stats_spls.R | 35个函数 |
| stats_univariates.R | 73个函数 |
| sweave_report_biomarker.R | 12个函数 |
| sweave_report_enrichment.R | 9个函数 |
| sweave_report_integmex.R | 7个函数 |
| sweave_report_meta_analysis.R | 9个函数 |
| sweave_report_metamummi.R | 13个函数 |
| sweave_report_mummichog.R | 8个函数 |
| sweave_report_network.R | 7个函数 |
| sweave_report_pathway.R | 6个函数 |
| sweave_report_power.R | 6个函数 |
| sweave_report_raw_spectra.R | 24个函数 |
| sweave_report_stats.R | 19个函数 |
| sweave_report_time.R | 13个函数 |
| sweave_reporter.R | 7个函数 |
| tandem_ms.R | 45个函数 |
| util_api.R | 8个函数 |
| util_approx.R | 1个函数 |
| util_batch.R | 1个函数 |
| util_compatibility.R | 3个函数 |
| util_fgsea.R | 2个函数 |
| util_heatmap.R | 1个函数 |
| util_lipid.R | 1个函数 |
| util_listheatmap.R | 1个函数 |
| util_lsd.R | 2个函数 |
| util_metabolon.R | 7个函数 |
| util_missing.R | 8个函数 |
| util_multifac_mb_1d.R | 1个函数 |
| util_multifac_mb_2d.R | 1个函数 |
| util_multifac_mb_manova.R | 2个函数 |
| util_mztab.R | 1个函数 |
| util_nmdr.R | 2个函数 |
| util_pcapair.R | 3个函数 |
| util_peaks.R | 4个函数 |
| util_plot3d.R | 9个函数 |
| util_psea.R | 6个函数 |
| util_savedata.R | 2个函数 |
| util_scatter3d.R | 8个函数 |
| util_sspa.R | 29个函数 |
| util_univreport.R | 1个函数 |
| util_venndiagram.R | 2个函数 |
| util_volcano.R | 1个函数 |
| utils_enrichnet.R | 9个函数 |

## 详细函数列表

完整的函数列表（包含每个文件中所有函数的详细名称）已保存在 `metaboanalyst_functions_complete.txt` 文件中。

## 方法说明

本报告通过R脚本自动扫描所有.R文件，使用正则表达式匹配以下函数定义模式：
- `function_name <- function(`
- `function_name = function(`
- `function_name<-function(`

该方法能够准确识别R语言中的标准函数定义，并排除注释行中的误匹配。