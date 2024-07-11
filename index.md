<style>
  input {
    size="50"
  }
</style>

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

<script src="https://gist.github.com/githubwua/48cb99409f81fb5bd6e5a58e94338a1c.js"></script>


You can use the [editor on GitHub](https://github.com/githubwua/githubwua.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.
