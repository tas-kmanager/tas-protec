You will need to make adjustment for these rules, such as changing the field names as per your mapping and whitelisting because every environment is different.

You can convert these sigma rules to other format using https://uncoder.io/

There are 20 rules here covering the 4 not powershell tools:

* invisishell_1_lhf_components_name.yml
* invisishell_2_lhf_dll_loaded.yml
* invisishell_3_unique_initialization_trace.yml
* invisishell_4_reg_exe_for_privilege_escalation.yml
* invisishell_5_reg_set_value.yml
* invisishell_6_powershell_loading_unknown_dll.yml
* invisishell_7_powershell_loading_unsigned_dll.yml
* nopowershell_1_lhf_basic_info.yml
* nopowershell_2_cobaltstrike_olaf_detection.yml
* nopowershell_3_net_version_downgrading.yml
* powerlessshell_1_lhf_exe_created_in_net_framework_folder.yml
* powerlessshell_2_certutil_decodehex.yml
* powerlessshell_3_msbuild_exe_execution.yml
* powerlessshell_4_renamed_msbuild.yml
* powerlessshell_5_renamed_msbuild_loading_ms_build_dll.yml
* powerlessshell_6_renamed_msbuild_exe_powershell_call_trace.yml
* powershdll_1_lhf_exe_basic_info.yml
* powershdll_2_loader_binary_loading_powershell_dll.yml
* powershdll_3_loader_binary_loading_unsigned_dll.yml
* powershdll_4_PowerShDLL_57_dlls_sample.yml
