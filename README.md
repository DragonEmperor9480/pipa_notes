<h1>Installation Guide</h1>
<div>
  <ol>
    <li>Download the rom package along with boot,dtbo and vendor_boot(links mentioned in post)</li>
    <li>Put downloaded files in a folder(your platform tools folder preferred)</li>
    <li>reboot to bootloader(hold power + volume down button)</li>
    <li>In your pc,open terminal where you copied the above files and run the following commands:</li>
    <ul>
      <li>fastboot flash boot boot.img</li>
    <li>fastboot flash dtbo dtbo.img</li>
    <li>fastboot flash vendor_boot vendor_boot.img</li>
    <li>fastboot reboot recovery</li>
    </ul>
    <li>Format data(optional if flashing on the same rom)</li>
     <li>select reboot to recovery(advanced -> reboot to recovery)</li>
    <li>select apply update in recovery</li>
    <li>In your pc terminal, run adb sideload rom.zip(replace rom.zip with the downloaded rom package name.zip)</li>
    <li>if you are flashing a vanilla build and want to flash gapps, select reboot to recovery(installation ends at 47% displayed on your pc terminal) and then sideload gapps by selecting apply update. Skip this step if you are already flashing a gapps build</li>
    <li>Reboot to system</li>
  </ol>
</div>
<br>
<h1>About Smartcover in custom roms</h1>
  <ol>
<li>Enable USB Debugging from developer options</li>
<li>Connect your tab to pc/laptop</li>
<li>Use the following command to enable it:</li>
  <ul>
<li>adb shell settings put global lid_behavior 1</li>
  </ul>
<li>Use the following command to Disable it:</li>
  <ul>
<li>adb shell settings put global lid_behavior 0</li>
  </ul>
<li>Note: It will be Enabled by default in my Builds</li>   
  </ol>
<br>
<h1>If still having issues report here:  <a href="https://t.me/TheKamisatoClan">Support group</a></h1>
