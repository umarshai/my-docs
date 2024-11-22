---


---

<h1 id="vscode-extensions-best">vscode-extensions [Best]</h1>
<div>
    <img src="https://readme-typing-svg.demolab.com/?pause=1&amp;size=50&amp;color=f75c7e¢er=True&amp;width=1200&amp;height=120&amp;vCenter=True&amp;lines=Click+the+⭐+Star+please .;Any+questions+can+be+asked+in+Issue.">
</div>
<p><a href="README.md">En README</a> | <a href="README.zh-TW.md">中文版說明檔</a></p>
<hr>
<ul>
<li>
<p>Record and share vscode extensions, including improving development efficiency, key points, theme beautification, etc. . .</p>
</li>
<li>
<p>This project will provide detailed instructions for each extension, hoping to help coders all over the world code happily together: emoji_sunglasses:</p>
</li>
<li>
<p>This project provides <a href="./share/README.md">“<strong>extended sharing area</strong>”</a>, you can submit interested extensions here.</p>
</li>
<li>
<p>If you want <strong>Pull Request</strong>, just update <code>README.md</code></p>
<p>(<a href="https://github.com/Lin-jun-xiang/action-translate-markdown/tree/main"><code>README.zh-TW.md</code></a> will be automatically updated through CI)</p>
</li>
<li>
<p>Extended Summary:</p>
<ul>
<li><a href="#starquickly-download-multiple-extensions">Quickly download multiple extensions (read this first)</a></li>
<li><a href="#snowflaketransparent-editor">transparent editor</a></li>
<li><a href="#purple_hearttheme">theme</a></li>
<li><a href="#yellow_heart-beautifying-editor-and-editing-environment">editor and beautifying environment</a></li>
<li><a href="#green_heart-must-have-highly-recommended">must have and highly recommended</a></li>
<li><a href="#star2big-data-ai-engineer---jupyter-python">Big Data and AI Engineer-Jupyter(Python)</a></li>
<li><a href="#wavegitmarkdown-support">Git and Markdown helper</a></li>
<li><a href="#computer-remote-wsl--dev-container">Remote WSL and Dev Container</a></li>
<li><a href="#computer-remote-ssl">Remote-SSH: How to connect VSCode to Colab?</a></li>
<li><a href="#wrenchfixer-fix-vscode-corrupt">Fixer</a></li>
<li><a href="#codeium">Copilot Assist</a></li>
<li><a href="./share/README.md">Community Shares and Contributions</a></li>
</ul>
</li>
</ul>

Vscode Common Commands
<ul>
<li>
<p>Using the vscode command panel can increase the development speed .</p>
</li>
<li>
<p>Open command panel: <code>ctrl+shift+p</code></p>
</li>
<li>
<p>Common commands:</p>
<ul>
<li><code>File: Open Folder</code>: open folder as workspace .</li>
<li><code>Preferences: Color Theme</code>: select color theme for editor .</li>
<li><code>Preferences: File Icon Theme</code>: select icon theme for file .</li>
<li><code>Developer: Reload Window</code>: Reload VSCode window .</li>
</ul>
</li>
</ul>

<hr>
<h2 id="starquickly-download-multiple-extensions">⭐️Quickly download multiple extensions</h2>
<p>I will introduce a lot of vscode extensions later . There is a trick here, you can quickly download many extensions without looking for . one by one.</p>
<p>⚠️ If you have high version vscode, you can jump over the following method, just go to <a href="#star-quickly-download-multiple-extensions-for-new-version-vscode">here</a></p>
<p>If you want to transfer the extension of the old computer to the new computer in the future, you can also use this method 😗</p>
<ul>
<li>You can download the <code>.ps1</code> file that comes with this project, follow the third step below to exclude the unnecessary extension .</li>
<li>In the <code>extensions.ps1</code> file, each extension has a comment ., please delete the unnecessary . before executing the installation command</li>
</ul>
<blockquote>
<p>method:</p>
<ol>
<li>
<p>Access all the extensions of vscode on the current computer, the output is text . Enter the following command in the terminal (<code>powershell</code>):<br>
<code>code --list-extensions | ForEach-Object {"code --install-extension $_"} &gt; extensions.ps1</code></p>
</li>
<li>
<p>After the command is executed, the <code>extensions.ps1</code> file will be obtained in the current directory (the file name is defined when the command is executed) .</p>
</li>
<li>
<p>Enter the following command in the terminal (<code>powershell</code>) of the new computer:<br>
<code>./extensions.ps1</code></p>
</li>
<li>
<p>download complete<br>
<img src="https://user-images.githubusercontent.com/63782903/226086537-1dddd375-3206-44db-8208-17715d70c744.png" width="60%"></p>
</li>
</ol>
</blockquote>

Find Missing Extensions
<ul>
<li>
<p><a href="./extensions_compare/"><code>extensions-compare</code></a></p>
</li>
<li>
<p>Compare two <code>.ps</code> files to find <strong>differences</strong> between two extension records .</p>
</li>
<li>
<p>Usage (choose one of the following):</p>
<ul>
<li>
<p><code>compare.py</code><br>
run <code>Python</code> script .</p>
  <img src="img/2023-04-19-11-06-37.png">
</li>
<li>
<p><code>compare.sh</code><br>
runs <code>./extensions_compare/compare.sh</code> etc . on <code>git bash, wsl, or linux</code></p>
  <img src="img/2023-04-19-11-07-16.png">
</li>
</ul>
</li>
</ul>

<h3 id="star-quickly-download-multiple-extensions-for-new-version-vscode">⭐️ Quickly download multiple extensions (for new version vscode)</h3>
<p>Just click the <code>Profile</code>, then you can import or export the extensions.</p>
<img src="img/2023-07-07-21-22-20.png" width="60%">
<hr>
<h2 id="snowflaketransparent-editor">❄️Transparent editor</h2>
<p>The transparency effect is amazing.</p>
<p>It can be used as a lazy tool (code while watching the video~) .</p>
<p>You can use your own desktop background while coding and watching <strong>Gura</strong> .</p>
<h3 id="glassit-vsc">GlassIt-VSC</h3>
<blockquote>
<p>Usage:<br>
<code>ctrl+alt+z</code>: desaturation (transparency)<br>
<code>ctrl+alt+c</code>: increase saturation (opacity)</p>
</blockquote>
<img src="img/2023-03-20-20-35-03.png" width="60%">
<p><a href="#top">Back to top</a></p>
<hr>
<h2 id="purple_hearttheme">💜Theme</h2>
<p>The biggest reason to use vscode is to have <code>eye-catching</code>, <code>elegant</code>, <code>comfortable</code>, <code>pleasant editing interface</code>. Only a good-looking editing environment can make the coder willing to type on the keyboard~😎</p>
<p>Next, I will share my favorite topics with you one by one (the following examples are based on Python, and different languages may have slight differences)</p>
<p>oh! Wait a minute, here is a quick way to switch themes . After all, you may want to change themes every day~~</p>
<blockquote>
<p>Quick switch theme</p>
<p>“ctrl+shift+p”: Open vscode command input box</p>
<p>“Preferences:Color Theme”: Enter and choose the theme you want</p>
</blockquote>
<h3 id="arc-dark-for-visual-studio-code">Arc Dark for Visual Studio Code</h3>
<ul>
<li>The theme is a bit similar to the dark theme of Visual Studio Code, but the overall tone is softer, similar to the color of macarons.</li>
</ul>
<img src="img/2023-03-25-16-10-51.png" width="60%">
<h3 id="buttertheme">ButterTheme</h3>
<ul>
<li>As the name suggests, this is an eye-catching <em>milk yellow</em> theme</li>
<li>A very rare theme (to put it bluntly, not many people use it), but the author likes it very much</li>
<li>If you can’t find this theme, <a href="https://marketplace.visualstudio.com/items?itemName=Levampire.Buttur" target="_blank">link</a></li>
</ul>
<img src="img/2023-03-17-14-36-15.png" width="60%">
<h3 id="coder200">Coder200</h3>
<ul>
<li>This time I don’t know … just by looking at the name</li>
<li>Rare theme, full of <em>orange</em>, so sexy~😳</li>
</ul>
<img src="img/2023-03-17-14-44-30.png" width="60%">
<h3 id="doom-emacs-theme">doom-emacs-theme</h3>
<ul>
<li>Simple style</li>
</ul>
<img src="https://user-images.githubusercontent.com/63782903/232356902-fc57dbc3-f650-4c41-b5a6-f33497954cc7.png" width="60%">
<h3 id="dracula-official">Dracula Official</h3>
<p>*very famous, <em>pink</em> and <em>purple</em> vampire colors</p>
<img src="img/2023-03-17-14-51-36.png" width="60%">
<h3 id="github-theme">Github Theme</h3>
<ul>
<li>One of the classic themes that cannot be ignored</li>
</ul>
<img src="img/2023-06-06-15-03-29.png" width="60%">
<h3 id="hydra-theme-for-vs-code">Hydra Theme for VS-Code</h3>
<ul>
<li>Black and red theme, exuding a strong sense of high-tech aesthetics.</li>
</ul>
<img src="img/2023-08-16-15-20-03.png" width="60%">
<h3 id="laserwave">LaserWave</h3>
<ul>
<li>A <em>purple pink</em> theme with a sunset feel</li>
</ul>
<img src="img/2023-03-17-20-17-56.png" width="60%">
<h3 id="moegi-theme">Moegi Theme</h3>
<ul>
<li>Gentle and charming theme</li>
</ul>
<img src="img/2023-03-17-20-20-13.png" width="60%">
<h3 id="material-dark">Material Dark</h3>
<ul>
<li>One of the classic themes that cannot be ignored</li>
</ul>
<img src="img/2023-03-17-20-37-24.png" width="60%">
<h3 id="one-dark-pro">One Dark Pro</h3>
<ul>
<li>One of the classic themes that cannot be ignored</li>
</ul>
<img src="img/2023-03-17-20-36-31.png" width="60%">
<h3 id="panda-theme">Panda Theme</h3>
<ul>
<li><em>Lake Green</em> 🐼 Top notch themes:</li>
<li>This theme is really cool!</li>
</ul>
<img src="img/2023-03-17-20-21-23.png" width="60%">
<h3 id="simple-dark">Simple Dark</h3>
<ul>
<li>The background is very dark, the text color will not be too dazzling</li>
</ul>
<img src="img/2023-03-17-20-23-37.png" width="60%">
<h3 id="skyline">Skyline</h3>
<ul>
<li>Blue lovers must use it 💙</li>
</ul>
<img src="img/2023-03-17-20-25-15.png" width="60%">
<h3 id="synthwave-84">SynthWave '84</h3>
<ul>
<li>Super high-tech, dazzling fluorescent theme: emoji_sunglasses:</li>
<li>Remember to turn on the fluorescent effect after selecting the theme (you can also match it with other theme colors: emoji_emoji_fu :)</li>
</ul>
<blockquote>
<p>Enable fluorescence mode:</p>
<ol>
<li>
<p>“ctrl+shift+p”: Open the VS Code command input box</p>
</li>
<li>
<p>“Synthwave '84: Enable/Disable Neon Dreams”: Enable/Disable Neon Dreams (see picture)</p>
</li>
<li>
<p>“Restart”: Restart VS Code</p>
</li>
</ol>
</blockquote>
<img src="img/2023-03-17-20-28-44.png" width="60%">
<img src="img/2023-03-17-20-27-06.png" width="60%">
<h3 id="tearz">Tearz</h3>
<ul>
<li>A bit similar to the previously launched Moe Wood theme<br>
*But this <em>purple</em> really attracts the author~</li>
</ul>
<img src="img/2023-03-17-20-33-32.png" width="60%">
<h3 id="vuesion-theme">Vuesion Theme</h3>
<ul>
<li>Simple pink, looks very comfortable</li>
</ul>
<img src="img/2023-05-18-14-20-10.png" width="60%">
<h3 id="xcode-theme">Xcode Theme</h3>
<ul>
<li>One of the classic themes that cannot be ignored</li>
</ul>
<img src="img/2023-03-17-20-35-39.png" width="60%">
<p><a href="#top">Back to top</a></p>
<hr>
<h2 id="yellow_heart-beautifying-editor-and-editing-environment">💛 Beautifying editor and editing environment</h2>
<p>After finishing the decoration, our editor will introduce the plug-ins that can not only increase the aesthetic feeling, but also improve work efficiency~</p>
<h3 id="color-highlight">Color Highlight</h3>
<ul>
<li>If you are a <strong>front-end</strong> engineer or <strong>data analyst</strong>, and often need to do <strong>visual</strong> work, be sure to download this!</li>
<li>When editing, as long as there is <strong>hexadecimal</strong> color expression, you can see the color very clearly (you don’t need to run the code if the color looks good) .</li>
</ul>
<img src="img/2023-03-17-20-48-11.png" width="60%">
<h3 id="material-theme-icons">Material Theme Icons</h3>
<ul>
<li>Different file extensions have different icons</li>
<li>Not only looks good but can find files faster.</li>
</ul>
<img src="img/2023-03-17-20-51-07.png" width="60%">
<h3 id="vscode-icons">vscode-icons</h3>
<ul>
<li>Slightly different from Material theme icons</li>
<li>The author prefers to use this~</li>
</ul>
<img src="img/2023-03-17-20-53-26.png" width="60%">
<p><a href="#top">Back to top</a></p>
<hr>
<h2 id="green_heart-must-have-highly-recommended">💚 Must-have, highly recommended</h2>
<p>The plugins to be introduced below are really easy to use!</p>
<p>Most of them can improve development efficiency, don’t miss: emoji_heart_eyes:</p>
<h3 id="autodocstring---python-docstring-generator">autoDocstring - Python Docstring Generator</h3>
<ul>
<li>This plugin was introduced by . for Python developers</li>
<li>Use shortcut keys to quickly generate <strong>Docstring</strong> style comments .</li>
<li>Describe the purpose, parameters, return value and other information of the function.</li>
<li>Support different <strong>Docstring</strong> styles, such as google, sphinx, numpy, etc. . .</li>
</ul>
<blockquote>
<p>How to use: Press the key below where you want to generate comments<br>
Windows: <code>ctrl+shift+2</code><br>
Mac: <code>cmd+shift+2</code></p>
</blockquote>
<img src="img/2023-03-17-21-07-10.png" width="60%">
<h3 id="code-runner">Code Runner</h3>
<ul>
<li>I believe that friends who have used VSCode should be familiar with this plugin! ?</li>
<li>Allow VSCode to execute the program with one click .</li>
<li>Support multiple languages, such as C, C++, Java, JavaScript, PHP, Python, Perl…etc.</li>
</ul>
<img src="img/2023-03-17-20-59-33.png" width="60%">
<h3 id="comment-divider">Comment Divider</h3>
<ul>
<li>Use shortcut keys to generate beautiful <strong>comment styles</strong> .</li>
<li>As shown in the figure below, you can see two styles: <code>Shift+Alt+x</code> and <code>Alt+x</code>.</li>
</ul>
<img src="img/2023-03-17-21-03-04.png" width="60%">
<h3 id="draw.io-integration"><a href="http://Draw.io">Draw.io</a> Integration</h3>
<ul>
<li>Flow chart drawing tool</li>
<li>When designing a project, you can use this plugin to plan the feasibility .</li>
<li>Can be used as a note taking tool .</li>
<li>Support many common modes, such as Google cloud platform representative function symbol (as shown in the figure).</li>
</ul>
<img src="img/2023-03-17-21-14-00.png" width="60%">
<h3 id="isort">Isort</h3>
<ul>
<li>
<p>This is intended for use by Python developers.</p>
</li>
<li>
<p>Automatically formats imports.</p>
</li>
<li>
<p>After downloading, add the following code to <code>settings.json</code>:</p>
<pre><code>"isort.args":["--profile", "black"]
</code></pre>
</li>
<li>
<p>Next, open <code>Keyboard Shortcuts</code> and set a shortcut (the author has bound it to <code>F12</code>):</p>
<img src="img/2023-08-16-15-25-55.png" width="60%">
</li>
<li>
<p>Use the shortcut <code>F12</code> to automatically format Python imports.</p>
</li>
</ul>
<img src="img/2023-08-16-15-27-41.png" width="60%">
<h3 id="path-intellisense">Path Intellisense</h3>
<ul>
<li>It’s really cool to have this plugin when coding 😘</li>
<li>Coder suitable for frequently reading and writing files .</li>
<li>When writing the path, it will automatically list the files under the path you want to find .</li>
</ul>
<img src="img/2023-03-17-21-17-09.png" width="60%">
<p><a href="#top">Back to top</a></p>
<hr>
<h2 id="star2big-data-ai-engineer---jupyter-python">🌟Big data, AI engineer - Jupyter (Python)</h2>
<p>The plugins presented here are really powerful!</p>
<p>The author knows that many people who use Python are not used to using vscode for many reasons:</p>
<ul>
<li>Interactive mode</li>
<li>View variable data type and variable value (just like in Spyder, Pycharm)</li>
<li>Execute the code line by line, and execute part of the code (really very practical, better than Debug~😍)</li>
</ul>
<p>The plugin provides the following features:</p>
<ul>
<li>📌<strong>interactive mode</strong></li>
<li>📌** View variable data type and variable value** (such as Spyder, Pycharm)</li>
<li>📌 <strong>Execute code line by line</strong> and <strong>Execute part of code</strong> (really useful, better than debugging~:heart_eyes :)</li>
</ul>
<blockquote>
<p>If you can understand Chinese, it is recommended to spend 5 minutes to quickly learn how to use the Jupyter plug-in (see <a href="https://www.bilibili.com/video/BV1Bg411J78F/" target="_blank">link</a>)</p>
</blockquote>
<blockquote>
<p>Usage:</p>
<p>💡 Download the following plug-ins (some may not be used, forget it~)</p>
<p><code>Jupyter</code>, <code>Jupyter keymap</code>, <code>Jupyter slide show</code>, <code>Jupyter cell tag</code>, <code>Jupyter notebook renderes</code>, <code>vs code jupyter notebook previewer</code></p>
<img src="img/2023-03-17-21-50-07.png" width="40%">
</blockquote>
<blockquote>
<p>💡<strong>Execute code in interactive mode</strong></p>
<ol>
<li>right click . in script</li>
<li>select <code>Run Current File in Interactive Window</code><br>
(It is recommended to set a VS Code shortcut key, I set it to <code>F10</code>).<br>
3 . <code>Interactive</code> window will appear after execution of .</li>
</ol>
<img src="img/2023-03-17-21-54-03.png" width="40%">
<img src="img/2023-03-17-21-57-03.png" width="40%">
</blockquote>
<blockquote>
<p>💡<strong>View variable data type and variable value</strong> (need to be in interactive mode)</p>
<p>Click <em>Variables</em>. in the interactive window</p>
<img src="img/2023-03-20-13-17.PNG" width="60%">
</blockquote>
<blockquote>
<p>💡 <strong>Execute line by line or partly</strong></p>
<ol>
<li>Select the code to execute (can be one or more lines) .</li>
<li>right click on selected code .<br>
3 . SELECT * run select/row in interactive window * .</li>
</ol>
<img src="img/2023-03-17-22-04-33.png" width="60%">
</blockquote>
<p><a href="#top">Back to top</a></p>
<hr>
<h2 id="wavegit、markdown-support">👋Git、Markdown Support</h2>
<p>The plugins described below are essential for developers working on Github or Gitlab projects .</p>
<h3 id="gitlens">GitLens</h3>
<ul>
<li>After downloading, the script code will show <strong>which</strong> parts were <strong>modified</strong>, <strong>who</strong> made the changes, <strong>when</strong> the . was modified</li>
<li>Note that the .<code>170</code> line on the right side of the screen has a green line indicating that there is a new code record (red means deleting the code) .</li>
<li>Remember to track the project with <code>git</code> for this plugin to work .</li>
</ul>
<img src="img/2023-03-17-22-08-15.png" width="60%">

More for GitLens
<ul>
<li>Compare two commits with detailed <strong>differences</strong>
<ul>
<li>
<p><code>COMMITS</code>: Select the commit to compare with HEAD (step1~2)</p>
</li>
<li>
<p><code>SEARCH &amp; COMPARE</code>: select changed files (step 3)</p>
</li>
<li>
<p><code>diff</code>: correct file is HEAD (step 4)</p>
  <img src="img/git_diff.PNG" width="60%">
</li>
</ul>
</li>
</ul>

<h3 id="markdown-all-in-one">Markdown All in One</h3>
<ul>
<li>Using Markdown syntax in the vscode editor.</li>
<li>It provides automatic generation of table of contents.</li>
<li>It offers special shortcuts for Markdown, such as using <code>Ctrl+B</code> for bold formatting.</li>
</ul>
<img src="img/2023-06-27-20-42-05.png" width="60%">
<h3 id="markdown-preview-enhanced">Markdown Preview Enhanced</h3>
<ul>
<li>When writing <code>.md</code> file, you can preview the result .</li>
<li>Press <code>ctrl+k</code>, then <code>v</code> to open preview window .</li>
<li>The middle of the figure below is the <code>.md</code> file, and the right is the preview window .</li>
</ul>
<img src="img/2023-03-17-22-15-20.png" width="60%">
<h3 id="paste-image">Paste Image</h3>
<ul>
<li>
<p>Paste images directly from the clipboard into markdown/asciidoc (or other files)!</p>
</li>
<li>
<p>Usage</p>
<ul>
<li>screenshot to clipboard</li>
<li>Use default keybindings: <code>Ctrl+Alt+V</code> (<code>Cmd+Alt+V</code> on Mac).</li>
<li>images will be saved in the folder containing the currently edited file</li>
<li>Relative paths will be pasted to the current edited file</li>
</ul>
</li>
<li>
<p>You can configure <code>imagePath</code> in settings.</p>
  <img src="img/2023-05-27-15-53-03.png" width="60%">
</li>
</ul>
<p><a href="#top">Back to top</a></p>
<hr>
<h2 id="computer-remote-wsl--dev-container">💻 Remote WSL &amp; Dev Container</h2>
<h3 id="remote-wsl">Remote WSL</h3>
<ul>
<li>vscode will open . in <code>Windows Subsystem Linux</code> environment</li>
<li>You can edit files in <code>WSL</code> environment in vscode editor without using <code>vim</code> or <code>nano</code>.</li>
</ul>
<blockquote>
<p>Usage:</p>
<ol>
<li><code>ctrl+shift+p</code>: open command panel .<br>
2 . <code>WSL: New WSL Window</code>: Open <code>WSL</code> environment in vscode .</li>
</ol>
</blockquote>
<img src="img/2023-03-20-11-47-42.png" width="60%">
<h3 id="dev-container">Dev-Container</h3>
<ul>
<li>
<p>Using <code>Docker</code>, the entire development environment inside vscode can run in the container, including editing, terminal, debugging, executing .</p>
</li>
<li>
<p><code>Node.js</code>, <code>Python</code>, <code>Java</code>, etc. and other development tasks, only need to install <code>Docker</code> and vscode, no need to install the corresponding runtime and compiling software .</p>
</li>
</ul>
<img src="img/2023-03-20-11-48-43.png" width="60%">
<p><a href="#top">Back to top</a></p>
<hr>
<h2 id="computer-remote-ssl">💻 Remote-SSL</h2>
<p>The Remote - SSH extension lets you use any remote machine with a SSH server as your development environment. This can greatly simplify development and troubleshooting in a wide variety of situations. You can:</p>
<ul>
<li>Develop on the same operating system you deploy to or use larger, faster, or more specialized hardware than your local machine.</li>
<li>Quickly swap between different, remote development environments and safely make updates without worrying about impacting your local machine.</li>
<li>Access an existing development environment from multiple machines or locations.<br>
Debug an application running somewhere else such as a customer site or in the cloud.</li>
</ul>
<img src="img/2023-06-27-20-45-53.png" width="60%">
<ul>
<li>
<p>Please note that if you are using the <strong>Windows</strong> operating system and experiencing issues with SSH, receiving the following error: <code>ssh: could not resolve hostname</code>, you need to add your <strong>Host</strong> and <strong>Hostname</strong> to the <code>C:/Windows/System32/drivers/etc/hosts</code> file:</p>
<pre><code>&lt;Host&gt; &lt;Hostname&gt;
</code></pre>
</li>
</ul>
<p>Next, let’s take an example of connecting VS Code to Colab:</p>
<h4 id="connect-vscode-to-colab">Connect VSCode to Colab</h4>
<p>Please refer to the official documentation for instructions:</p>
<p><a href="https://colab.research.google.com/github/JayThibs/jacques-blog/blob/master/_notebooks/2021-09-27-connect-to-colab-from-local-vscode.ipynb">https://colab.research.google.com/github/JayThibs/jacques-blog/blob/master/_notebooks/2021-09-27-connect-to-colab-from-local-vscode.ipynb</a></p>
<p>Remeber you only need to perform steps 6, 8, 9, and 10 once</p>
<ol>
<li>
<p>Open Colab.</p>
</li>
<li>
<p>Execute the following code to connect to Google Drive. You will see your Drive file manager appear next to Colab.</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> google<span class="token punctuation">.</span>colab <span class="token keyword">import</span> drive
drive<span class="token punctuation">.</span>mount<span class="token punctuation">(</span><span class="token string">"/content/drive"</span><span class="token punctuation">)</span>
</code></pre>
</li>
<li>
<p>Create a file named <code>config.env</code> in your Google Drive, for example:</p>
<pre><code># /content/drive/MyDrive/Colab/config.env
PASSWORD=1234567
</code></pre>
</li>
<li>
<p>Read the <code>config.env</code> file in Google Drive to obtain the password needed for SSH later.</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># !pip install python-dotenv --quiet</span>
 <span class="token keyword">import</span> dotenv
 <span class="token keyword">import</span> os

 dotenv<span class="token punctuation">.</span>load_dotenv<span class="token punctuation">(</span>
         os<span class="token punctuation">.</span>path<span class="token punctuation">.</span>join<span class="token punctuation">(</span><span class="token string">'/content/drive/MyDrive/Colab/'</span><span class="token punctuation">,</span> <span class="token string">'config.env'</span><span class="token punctuation">)</span>
 <span class="token punctuation">)</span>
 password <span class="token operator">=</span> os<span class="token punctuation">.</span>getenv<span class="token punctuation">(</span><span class="token string">'PASSWORD'</span><span class="token punctuation">)</span>
</code></pre>
</li>
<li>
<p>Perform SSH using Cloudflared to obtain the remote host (URL that will be used later).</p>
<pre class=" language-python"><code class="prism  language-python"> <span class="token comment"># Install colab_ssh on google colab</span>
 <span class="token comment"># !pip install colab_ssh --upgrade --quiet</span>
 <span class="token keyword">from</span> colab_ssh <span class="token keyword">import</span> launch_ssh_cloudflared<span class="token punctuation">,</span> init_git_cloudflared
 launch_ssh_cloudflared<span class="token punctuation">(</span>password<span class="token punctuation">)</span>
</code></pre>
 <img src="img/2023-06-27-21-06-42.png" width="60%">
</li>
<li>
<p>Download Cloudflared to any location on your local machine. <a href="https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/install-and-setup/installation/">link</a></p>
</li>
<li>
<p>Install the <code>Remote-SSH</code> extension in VS Code.</p>
</li>
<li>
<p>Use the VS Code command <code>Ctrl+Shift+P</code> and enter <code>remote-ssh: connect to host</code>.</p>
</li>
<li>
<p>Select <code>configure ssh hosts</code> then <code>c:\users&lt;name&gt;.ssh\config</code>.</p>
</li>
<li>
<p>Paste the following code, making sure to fill in the path with the location where Cloudflared was downloaded!</p>
<pre><code>Host *.trycloudflare.com
    HostName %h
    User root
    Port 22
    ProxyCommand &lt;PUT_THE_ABSOLUTE_CLOUDFLARE_PATH_HERE&gt; access ssh --hostname %h
</code></pre>
</li>
<li>
<p>Use the VS Code command <code>Ctrl+Shift+P</code> and enter <code>remote-ssh: connect to host</code>.</p>
</li>
<li>
<p>Select <code>add new ssh host</code> and enter the URL from step 5.</p>
</li>
<li>
<p>Enter the password from <code>config.env</code>.</p>
</li>
<li>
<p>After creating new vscode window, choose the OS System.</p>
</li>
<li>
<p>Finished!</p>
</li>
</ol>
<p><a href="#top">Back to top</a></p>
<hr>
<h2 id="wrenchfixer-fix-vscode-corrupt">🔧Fixer (Fix Vscode Corrupt)</h2>
<p>Sometimes, when uninstalling the plugin, the following error message will appear in the lower right corner of the VS Code window:</p>
<img src="https://user-images.githubusercontent.com/63782903/231321298-916da9d3-0e90-4bd5-bfc6-859371545ec7.png" width="40%">
<p>You can solve this problem with:</p>
<blockquote>
<p>Usage:</p>
<ol>
<li>Download Fix VSCode Checksum Plugin .</li>
<li><code>ctrl+shift+p</code>: Open command palette .</li>
<li><code>Fix ChecksumS: Apply</code>: perform repair .</li>
<li><code>ctrl+shift+p</code>: Open command palette .</li>
<li><code>Developer: Reload Window</code>: restart VS Code.</li>
</ol>
</blockquote>
<img src="img/2023-03-17-21-36-48.png" width="60%">
<p><a href="#top">Back to top</a></p>
<h2 id="rocket-copilot">🚀 Copilot</h2>
<p>AI-assisted development tools similar to ChatGPT make everyone faster in the development process</p>
<h3 id="codeium">Codeium</h3>
<ul>
<li>
<p>Completely <strong>FREE</strong> to use!<br>
*Comparison of functions with ChatGPT and Copilot</p>
</li>
<li>
<p>With this tool, you can:</p>
<ul>
<li>Automatic code generation</li>
<li>automatically generates comments, <code>Docstring</code></li>
<li>automatically generates <code>Annotation hint</code></li>
<li>improve code quality</li>
</ul>
  <img src="img/2023-06-02-11-36-02.png" width="40%">
</li>
<li>
<p>Instructions</p>
<ul>
<li>
<p>Click <code>Refactor</code> of the code block</p>
  <img src="img/2023-06-02-11-35-37.png" width="60%">
</li>
<li>
<p>Select the processing you want, eg: <code>Add comments and docstrings to the code</code></p>
  <img src="img/2023-06-06-15-00-52.png" width="50%">
</li>
<li>
<p>generate <code>Codeium</code> chat blocks</p>
  <img src="img/2023-06-06-15-05-18.png" width="40%">
</li>
<li>
<p>code extraction is complete!</p>
</li>
</ul>
</li>
</ul>
<p><a href="#top">Back to top</a></p>

