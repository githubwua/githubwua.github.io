<style>
  input {
    size="50"
  }
</style>

# Wua Portal


## Search Engines

### Syntax
<!-- https://support.google.com/programmable-search/thread/184677405/how-can-i-fix-problem-about-using-two-programmable-search-engines-in-one-page?hl=en -->
<!-- 
<script async src="https://cse.google.com/cse.js?cx=3acd834d7218e856f"></script>
<div class="gcse-search"></div> 
-->
<form method="get" action="https://cse.google.com/cse" accept-charset="UTF-8"> 
<input type="hidden" name="cx" value="3acd834d7218e856f" />
<input type="text" name="q" id="search-3acd834d7218e856f" size="50" value="" /> 
<input type="submit" value="Syntax Howto Search" /> 
</form>

### 英日辞典検索
<!-- https://support.google.com/programmable-search/thread/184677405/how-can-i-fix-problem-about-using-two-programmable-search-engines-in-one-page?hl=en -->
<form method="get" action="https://cse.google.com/cse" accept-charset="UTF-8"> 
<input type="hidden" name="cx" value="b611564fcb8a8f9f4" />
<input type="text" name="q" id="search-b611564fcb8a8f9f4" size="50" value="" /> 
<input type="submit" value="英日辞典検索" /> 
</form>

<form action="https://chinese.yabla.com/chinese-english-pinyin-dictionary.php" id="form1">
  <label for="chinese">中文:</label>
  <input type="text" placeholder="輸入中文字詞査拼音聽發音" id="search-yabla" name="yabla">
  <input type="submit" value="🔍">
</form>

<form action="https://crptransfer.moe.gov.tw/index.jsp" id="tai">
  <label for="chinese">拼音查詢:</label>
  <input type="text" placeholder="輸入一個中文字，查詢所有的標音​" id="SN" name="SN">
  <input type="submit" value="🔍">
</form>

<form action="https://dictionary.writtenchinese.com/" id="chinese">
  <label for="chinese">Search by Pinyin, ，簡體字，　or English: </label>
  <input type="text" placeholder="Enter Pinyin, ，簡體字，　or English" id="SＫ" name="SＫ">
  <input type="submit" value="🔍">
</form>

<form accept-charset="big5" action="https://humanum.arts.cuhk.edu.hk/Lexis/lexi-can/search.php" id="form2">
  <label for="yue">粤語:</label>
  <input type="text" placeholder="Search by 正體單 to get 粤語發音" id="yue" name="yue">
  <input type="submit" value="🔍">
</form>

<form action="https://docs.python.org/3/search.html" id="pythondocs">
  <label for="pythondocs">Python</label>
  <input type="text" placeholder="search python docs" id="q" name="q">
  <input type="submit" value="🔍">
</form>

<form action="https://eow.alc.co.jp/search" id="alc">
  <label for="alc">alc</label>
  <input type="text" placeholder="search alc" id="q" name="q">
  <input type="submit" value="🔍">
</form>

<script src="https://gist.github.com/githubwua/48cb99409f81fb5bd6e5a58e94338a1c.js"></script>


You can use the [editor on GitHub](https://github.com/githubwua/githubwua.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.
