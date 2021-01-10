<b> HACKINTOSH BIG SUR 11.1 ON DELL INSPIRON 5579 2 in 1 Laptop Opencore 0.6.4</b>

<ul>
  <strong><h1>SPESIFICATIONS</h1></strong>
  <li>Processor : Intel core i5 8250U (KabyLake Refresh)</li>
  <li>RAM       : 16GB (Upgraded 2x8GB) Kingston</li>
  <li>iGPU      : Intel UHD 620</li>
  <li>Opencore  : 0.6.4</li>
  <li>Audio     : ALC225 (Layout ID 28, 30, 33) I use 28 </li>
</ul>

<p>
  <strong> <h1>BIG SUR 11.1 </h1></strong><br>
  <b>WORKS:</b><br>
  <ul>
    <li>iGPU UHD 620 Works with HDMI output and audio from HDMI output</li>
    <li>Audio Built-in and Microphone</li>
    <li>ALL USB port</li>
    <li>Function key on Built-in Keyboard and External Keyboard USB</li>
    <li>Touchpad (without gestures)</li>
    <li>Bluetooth (without Airdrop)</li>
    <li>Sleep Mode</li>
    <li>Battery Indicator</li>
  </ul>
  </p>
  
<p>
   <b>NOT working:</b><br>
<ul>
  <li>WiFi (its use DW1820 Atheros which is doesnt support by Apple, you have to change to NGFF WiFi Model that supported by Apple)</li>
  <li>Gestures on Trackpad</li>
  <li>iCloud but can use Apple ID to install app in appstore</li>
  </ul>
</p>

<p>
   <b>ADDITIONAL</b><br>
<ul>
  <li>ISSUES    : Suddenly Shutdown when on Battery, but Running very well when plugged</li>
  <li>ISSUES    : Processor Detect i7 not i5 in About this Mac, there is no effect on performance</li>
  <li>NOT TESTED: Touchscreen, I dont want it so I never search of it </li>
</ul>
<br>
  1. for first time use, you have to add <b>-v</b> in <i>boot flag</i> to see error when boot (if it wont boot) go to NVRAM - boot-args <br>
  2. Default, I use dual-monitor, so I added <b>agdpmod=vit9696</b> you can delete this boot-args if you just using single monitor<br>
                                           
  
