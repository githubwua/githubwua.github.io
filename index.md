<style>
  input {
    size="50"
  }
</style>

You can use the [editor on GitHub](https://github.com/githubwua/githubwua.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

# Wua Portal


## Search Engines


<!-- https://support.google.com/programmable-search/thread/184677405/how-can-i-fix-problem-about-using-two-programmable-search-engines-in-one-page?hl=en -->
<!-- 
<script async src="https://cse.google.com/cse.js?cx=3acd834d7218e856f"></script>
<div class="gcse-search"></div> 
-->
<form method="get" action="https://cse.google.com/cse" accept-charset="UTF-8"  target="_blank"> 
  <label for="search-3ac">Tech Blog Search:</label>
  <input type="hidden" name="cx" value="3acd834d7218e856f" />
  <input type="text" name="q" id="search-3ac" size="50" placeholder="e.g. lsof" /> 
  <input type="submit" value="🔍" /> 
</form>


<!-- https://support.google.com/programmable-search/thread/184677405/how-can-i-fix-problem-about-using-two-programmable-search-engines-in-one-page?hl=en -->
<form method="get" action="https://cse.google.com/cse" accept-charset="UTF-8"  target="_blank">
  <label for="search-b611">英日辞典サイトサーチ:</label>
　<input type="hidden" name="cx" value="b611564fcb8a8f9f4" />
　<input type="text" name="q" id="search-b611" size="50" placeholder="e.g. これ or egg" /> 
　<input type="submit" value="🔍" /> 
</form>

<form action="https://chinese.yabla.com/chinese-english-pinyin-dictionary.php" id="form-yabla"  target="_blank">
  <label for="yabla">査拼音/聽發音（yabla）:</label>
  <input type="text" placeholder="e.g. 環保 or 环保" id="search-yabla" name="q" id="yabla" size="50">
  <input type="submit" value="🔍">
</form>

<form action="https://www.moedict.tw/" id="moe"  target="_blank">
  <label for="yabla">萌典(國語辭典):</label>
  <input type="text" placeholder="e.g. 漢 or 鄉" id="search-yabla" name="q" id="yabla" size="50">
  <input type="submit" value="🔍">
</form>


<form action="https://crptransfer.moe.gov.tw/index.jsp" id="moe"  target="_blank">
  <label for="SN">查詢漢字、注音或拼音:</label>
  <input type="text" placeholder="e.g. 漢 or han4 or ㄏㄢˋ" id="SN" name="SN" size="40">
  <input type="submit" value="🔍">
</form>

<!-- <form action="https://dictionary.writtenchinese.com/" id="chinese" target="_blank"> -->
<form action="https://dictionary.writtenchinese.com/ajaxsearch/simsearch.action" id="chinese" method="post" target="_blank">  
  <label for="SK">Find Pinyin: </label>
  <input type="text" placeholder="e.g. hao or 凤　or wind" id="SＫ" name="searchKey" size="50">
  <input type="submit" value="🔍">
</form>

<form accept-charset="big5" action="https://humanum.arts.cuhk.edu.hk/Lexis/lexi-can/search.php" id="form-yue" target="_blank">
  <label for="yue">粤語發音(cuhk):</label>
  <input type="text" placeholder="e.g. 漢" id="yue" name="q" size="60">
  <input type="submit" value="🔍">
</form>

<form action="https://docs.python.org/3/search.html" id="pythondocs" target="_blank">
  <label for="pythondocs">Python</label>
  <input type="text" placeholder="search python docs" id="pythondocs" name="q">
  <input type="submit" value="🔍">
</form>

<form action="https://eow.alc.co.jp/search" id="alc" target="_blank">
  <label for="alc">alc</label>
  <input type="text" placeholder="search alc" id="q" name="q">
  <input type="submit" value="🔍">
</form>

# Tools
- [Google Admin Toolbox (HAR/Encode/Decode/etc)](https://toolbox.googleapps.com/apps/encode_decode/)
- [cyberchef](https://gchq.github.io/CyberChef/)
- [XOR Calculator Online](http://xor.pw/)
- [HAR Analyzer](https://toolbox.googleapps.com/apps/har_analyzer/)
- [Crontab.guru - The cron schedule expression generator](https://crontab.guru/)
- [Epoch Converter - Unix Timestamp Converter](https://www.epochconverter.com/)
- [GitHub - fiatjaf/jiq: jid on jq - interactive JSON query tool using jq expressions](https://github.com/fiatjaf/jiq)
- [Every Time Zone: time zone converter, compare time zone difference and find best time for a meeting with one click](https://everytimezone.com/)
- [Cloud Shell](https://shell.cloud.google.com/)
- [粵語審音配詞字庫](http://humanum.arts.cuhk.edu.hk/Lexis/lexi-can/)
- [羊羊粤语](https://shyyp.net/)
- [DeepL Translate: The world's most accurate translator](https://www.deepl.com/translator#en/zh/criteria)
- [regex101: build, test, and debug regex](https://regex101.com/)
- [explainshell.com - match command-line arguments to their help text](https://explainshell.com/)
- [IP Address Tools - TehnoBlog.org](https://tehnoblog.org/ip-tools/)
- [Loading CSV data from Cloud Storage](https://cloud.google.com/bigquery/docs/loading-data-cloud-storage-csv)
- [QR Code Generator](https://ja.qr-code-generator.com/)
- [Decimal to Hex Converter](https://www.rapidtables.com/convert/number/decimal-to-hex.html)
- [Wifi Redirect](http://www.gstatic.com/generate_204)
- [Replit – Build apps and sites with AI](https://replit.com/)
- [p5.js Web Editor](https://editor.p5js.org/)
- [Network Tools: DNS,Blacklisted IP,Email](https://mxtoolbox.com/SuperTool.aspx?action=blacklist%3a8.8.8.8&run=toolpage)

# Javascripts
- [add link breaks]javascript:const style = document.createElement('style'); style.textContent = 'td.dataCell, td.dataCol, td.data2Col { word-break: break-all; }'; document.head.append(style);
- [redirect to new site](javascript:window.open(window.location.href.replace('localhost','www.example.com'), '__blank');)
- [view image links as images](javascript:document.querySelectorAll('a[href^="https://localhost/"]').forEach((a) => {    let newLine = document.createElement("br");    let img = new Image();    img.setAttribute("width", "100%");    img.src = `${a.href}.png`;    a.parentNode.insertBefore(img, a.nextSibling);    a.parentNode.insertBefore(newLine, a.nextSibling);}))
- [hightlight ids](javascript:document.querySelectorAll('[id]').forEach((el) => {  el.style.border = 'solid 2px red';});)
- [show last modified](javascript:alert('Last modified on ' + document.lastModified))

[edit journals](https://gist.github.com/githubwua/48cb99409f81fb5bd6e5a58e94338a1c/edit)
<script src="https://gist.github.com/githubwua/48cb99409f81fb5bd6e5a58e94338a1c.js"></script>
[edit journals](https://gist.github.com/githubwua/48cb99409f81fb5bd6e5a58e94338a1c/edit)

You can use the [editor on GitHub](https://github.com/githubwua/githubwua.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.
