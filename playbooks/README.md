
| category  | command                | playbook                   | sample output file |
|-----------|------------------------|----------------------------|--------------------|
| Inventory | GetSystemInventory     | get_storage_inventory.yml  | [r740_SystemInventory_YYYYMMDD_hhmmss.json](../sample_output_files/r740_SystemInventory_YYYYMMDD_hhmmss.json) | |
|           | GetPSUInventory        | get_psu_inventory.yml      | [r740_PSUInventory_YYYYMMDD_hhmmss.json](../sample_output_files/r740_PSUInventory_YYYYMMDD_hhmmss.json) |
|           | GetCPUInventory        | get_cpu_inventory.yml      | [r740_CPUInventory_YYYYMMDD_hhmmss.json](../sample_output_files/r740_CPUInventory_YYYYMMDD_hhmmss.json) |
|           | GetNICInventory        | get_nic_inventory.yml      | [r740_NICInventory_YYYYMMDD_hhmmss.json](../sample_output_files/r740_NICInventory_YYYYMMDD_hhmmss.json) |
|           | GetFanInventory        | get_fan_inventory.yml      | [r740_FanInventory_YYYYMMDD_hhmmss.json](../sample_output_files/r740_FanInventory_YYYYMMDD_hhmmss.json) |
| Firmware  | GetInventory           | get_firmware_inventory.yml | [r740_FirmwareInventory_YYYYMMDD_hhmmss.json](../sample_output_files/r740_FirmwareInventory_YYYYMMDD_hhmmss.json) |
|           | UploadFirmware         | firmware_update.yml        |                    |
|           | FirmwareCompare        | firmware_update.yml        |                    |
|           | InstallFirmware        | firmware_update.yml        |                    |
| Bios      | GetAttributes          | manage_bios.yml            | [r740_BIOSAttributes_YYYYMMDD_hhmmss.json](../sample_output_files/r740_BIOSAttributes_YYYYMMDD_hhmmss.json) |
|           | GetBootOrder           | manage_bios.yml            | [r740_BIOSBootOrder_YYYYMMDD_hhmmss.json](../sample_output_files/r740_BIOSBootOrder_YYYYMMDD_hhmmss.json) |
|           | SetOneTimeBoot         | manage_bios.yml            |                    |
|           | SetDefaultSettings     | manage_bios.yml            |                    |
|           | SetAttributes          | manage_bios.yml            |                    |
|           | ConfigJob              | manage_bios.yml            |                    |
| Power     | PowerOn                | manage_system_power.yml    |                    |
|           | PowerOff               | manage_system_power.yml    |                    |
|           | GracefulRestart        | manage_system_power.yml    |                    |
|           | GracefulShutdown       | manage_system_power.yml    |                    |
| Storage   | GetControllerInventory | get_storage_inventory.yml  | [r740_StorageControllerInventory_YYYYMMDD_hhmmss.json](../sample_output_files/r740_StorageControllerInventory_YYYYMMDD_hhmmss.json) |
|           | GetDiskInventory       | get_storage_inventory.yml  | [r740_DiskInventory_YYYYMMDD_hhmmss.json](../sample_output_files/r740_DiskInventory_YYYYMMDD_hhmmss.json) |
| Users     | ListUsers              | manage_idrac_users.yml     | [r740_IDRACUsers_YYYYMMDD_hhmmss.json](../sample_output_files/r740_IDRACUsers_YYYYMMDD_hhmmss.json) |
|           | AddUser                | manage_idrac_users.yml     |                    |
|           | EnableUser             | manage_idrac_users.yml     |                    |
|           | UpdateUserRole         | manage_idrac_users.yml     |                    |
|           | UpdateUserPassword     | manage_idrac_users.yml     |                    |
|           | DisableUser            | manage_idrac_users.yml     |                    |
|           | DeleteUser             | manage_idrac_users.yml     |                    |
| SCP       | ExportSCP              | manage_scp.yml             | [SCP_r740_YYYYMMDD_hhmmss.xml](../sample_output_files/SCP_r740_YYYYMMDD_hhmmss.xml) |
|           | ImportSCP              | manage_scp.yml             |                    |
| Logs      | GetSELogs              | get_system_logs.yml        | [r740_SELogs_YYYYMMDD_hhmmss.json](../sample_output_files/r740_SELogs_YYYYMMDD_hhmmss.json) |
|           | GetLCLogs              | get_system_logs.yml        | [r740_LCLogs_YYYYMMDD_hhmmss.json](../sample_output_files/r740_LCLogs_YYYYMMDD_hhmmss.json) |
| Idrac     | SetDefaultSettings     | manage_idrac_power.yml     |                    |
|           | GracefulRestart        | manage_idrac_power.yml     |                    |
| Network   | (coming soon)          | (coming soon)              |                    |
