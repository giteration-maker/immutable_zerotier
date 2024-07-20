# immutable_zerotier
This is a repo for  the Zerotier installation script for immmutable Fedora distros  such as Silverblue, Bazzite, Aurora etc.<br>
[original script](https://gist.github.com/hannut/fd029c62cbdae515bcb0fed990d5a780) 
<br> 
<h4>changes:</h4>
<code>fc/22</code> part was modified to: 
<code>fc/$releasever</code> to always get the latest release.
<br>
<h3>Install the script from terminal: </h3> 
<code>curl -sSL https://raw.githubusercontent.com/giteration-maker/immutable_zerotier/main/install.sh| bash</code>
<p>
<ul>
  <li>curl: Downloads the script</li>
  <li>sSL: Flags for curl (s: silent mode, S: show error if fails, L: follow redirects)</li>
  <li>|: Pipes the downloaded content to bash</li>
  <li>bash: Executes the script</li>
</ul>
</p>
<br>
<h4>Credits: </h4>

[@hannut](https://gist.github.com/hannut)  - creator of the script <br>
[@kaidelorenzo](https://gist.github.com/kaidelorenzo) - suggestion to change to latest release
