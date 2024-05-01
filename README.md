<h1>Installation Guide</h1>
<div>
<h2>NOTE: Make sure to use Miui 14 based on Android 13 Firmware, don't try to run this ROM with HyperOS Firmware</h2>
<div>
  <p>Follow this if you are on HyperOS(<a href="https://github.com/DragonEmperor9480/pipa_notes?tab=readme-ov-file#firmware-linksfor-those-who-are-on-hyperos">click here</a>)<br>You can skip this step if you are already on miui firmware and follow the below steps.</p>
</div>
  <ol>
    <li>Download the rom package along with boot,dtbo and vendor_boot(links mentioned in post)</li>
    <li>Put downloaded files in a folder(your platform tools folder preferred)</li>
    <li>reboot to bootloader(hold power + volume down button)</li>
    <li>In your pc,open terminal where you copied the above files and run the following commands:</li>
<br>
    
    fastboot flash boot boot.img
<br>

    fastboot flash dtbo dtbo.img
<br>
    
    fastboot flash vendor_boot vendor_boot.img
 <br>
 
    fastboot reboot recovery
<br>
    <li>Format data via recovery(optional if flashing on the same rom)</li>
     <li>select reboot to recovery(advanced -> reboot to recovery)</li>
    <li>select apply update in recovery</li>
    <li>In your pc terminal, run adb sideload rom.zip(replace rom.zip with the downloaded rom package name.zip)</li>
    <li>if you are flashing a vanilla build and want to flash gapps, select reboot to recovery(installation ends at 47% displayed on your pc terminal) and then sideload gapps by selecting apply update. Skip this step if you are already flashing a gapps build</li>
    <li>Reboot to system</li>
  </ol>
</div>
<div>
<h2>Firmware Links(For those who are on HyperOS)</h2>
<p>Follow Steps from 1 to 7, then Flash your regional firmware using the command adb sideload fw_package_name.zip(replace fw_package_name.zip with your downloaded firmware name.zip)<br>after flashing, reboot to recovery and follow the remaining steps above</p>
<ul>
  <li><a href="https://xdaforums.com/attachments/fw_pipa_miui_pipaeeaglobal_v14-0-7-0-tmzeuxm_69894218db_13-0-zip.6077268/">EU</a></li>
  <li><a href="https://xdaforums.com/attachments/fw_pipa_miui_pipainglobal_v14-0-7-0-tmzinxm_99edbc06b4_13-0-zip.6077269/">IN</a></li>
  <li><a href="https://xdaforums.com/attachments/fw_pipa_miui_pipaglobal_v14-0-11-0-tmzmixm_50200a003b_13-0-zip.6077270/">Global</a></li>
</ul>
</div>
<br>

<h1>If still having issues report here:  <a href="https://t.me/TheKamisatoClan">Support group</a></h1>
