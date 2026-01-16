# ipclock
ip-address-like clock
<p align="center"><a href="#"><img src="preview.png" alt="Image"></a></p>

<h3>how it works</h3>
<p>this clock visualizes the "progress" of each time unit in an ip-address-like format.</p>
<b>IPv4:</b>
<p><code>day.hour.min.sec</code>: linear completion of each unit from 0 to 255, imagine if you measured time as a percentage, but instead of the maximum being 100% it is 255%</p>
<b>IPv6:</b>
<p><code>century:year:month:day:hour:min:sec:tick</code>: basically the same thing as previous but progression goes up to 65535 in hexadecimal format</p>
