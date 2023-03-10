title: Pitch table
description: table of different pitch patterns
---

<form id="bloatbox" style="display: block;">
	<input type="text" id="narrow" placeholder="Filter concepts">
	<span class="option_container"><input type="checkbox" checked id="verbs" value="0"> <span class="option_caption" >Verbs</span></span>
	<span class="option_container"><input type="checkbox" checked id="nouns" value="0"> <span class="option_caption" >Nouns</span></span>
	<span class="option_container"><input type="checkbox" checked id="adjectives" value="0"> <span class="option_caption" >adjectives</span></span>
</form>


<p>Data source: <a href="NotOrange">NotOrange Notes</a>. Colors show what category each Pattern belongs to.<br><span id="js_hint" style="display: inline;"> Hint: Type <code>"と"</code> in the search box below to find all と entries. Middle click to view the section in the document.</span></p>

#### Counters 
| **_Counter_** | **_Pitch Accent_** | **_`Exceptions`_** **_and Other Notes_** |
| --- | --- | --- |
| ◯千◯<br>◯万◯<br>◯億◯<br>◯兆◯<br>etc | ◯せん◯{0}<br>◯まん◯{0}<br>◯おく◯{0}<br>◯ちょう◯{0}<br>etc | The first ◯ stands for a single kanji number and the second ◯ stands for any counter, like 人 or 円<br><br>eg.<br>1.  一千人・いっせんにん{0}<br>2.  8000冊・はっせんさつ{0}<br>3.  1億10万円・いちおく{2}　じゅうまんえん{0}<br>4.   2兆363万3千円・にちょう{1}　さんびゃく{1}　ろくじゅう{0}　さんまん{3}　さんぜんえん{0} |
| 〇っ〇〇 | 〇っ〇〇{4} | **ignores の rule** <br>eg.<br>一発・いっぱつ{4}<br>一曲・いっきょく{4}<br>六百・ろっぴゃく{4}<br>百匹・ひゃっぴき{4}<br><br>the pattern does not apply if the fourth mora does not have a consonant or otherwise cannot take an accent<br>eg. ～本・ほん, ～体・たい, and ～杯・はい would not follow this pattern |
| ～3 mora+ counter | 〇〇〇～{1} | `◯◯パーセント{5}`<br><br>eg.<br>一休み・ひとやすみ{3}<br>一単語・ひとたんご{3} |
| 数～  | すう〇〇{0} |     |
| 毎～  | まい〇〇{0} | `毎日・まいにち{1}`<br>`　　　まいにち{0}`<br>`毎晩・まいばん{1}` |
| ～か  | no change | `何回か・なんかいか{3}`<br>`               なんかいか{1} `|
| ～年  | ⠀ねん{1} | `3年・さんねん{0}`<br>`4年・よねん{0}`<br>`5年・ごねん{0}`<br><br>3年 is free to change to さんねん{1} or remain flat if it follows another number<br><br>eg.<br>13年・じゅうさんねん{3}<br>23年・にじゅう{1}・さんねん{1}<br>53年・ごじゅう{0}・さんねん{1} |
| ～ヶ月 | かげつ{1} |     |
| ～月  | がつ{2}<br>⠀がつ{1} | **ignores の rule**<br>1月・いちがつ{4}<br>2月・にがつ{1}<br>           にがつ{3}<br>3月・さんがつ{2}<br>4月・しがつ{1}<br>           しがつ{3}<br>5月・ごがつ{1}<br>6月・ろくがつ{4}<br>7月・しちがつ{4}<br>8月・はちがつ{4}<br>9月・くがつ{1}<br>10月・じゅうがつ{4}<br>11月・じゅういちがつ{6}<br>12月・じゅうにがつ{5}<br>           じゅうにがつ{3}<br>何月・なんがつ{1} |
| ～日  | か⠀{0}<br>にち{2}<br>⠀にち{1} | **ignores の rule**<br>何日・なんにち{1}<br>1日・ついたち{4}・いちにち{4}<br>2日・ふつか{0}<br>3日・みっか{0}<br>4日・よっか{0}<br>5日・いつか{0}<br>6日・むいか{0}<br>7日・なのか{0}<br>8日・ようか{0}<br>9日・ここのか{4}<br>10日・とおか{0}<br>11日・じゅういちにち{6}<br>12日・じゅうににち{3}<br>           じゅうににち{5}<br>13日・じゅうさんにち{3}<br>           じゅう{1}・さんにち{0}<br>14日・じゅうよっか{0}<br>　　　じゅう{1}・よっか{0}<br>           じゅうよんにち{3}<br>15日・じゅうごにち{3}<br>           じゅうごにち{5}<br>           じゅう{1}・ごにち{3}<br>           じゅう{1}・ごにち{1}<br>16日・じゅうろくにち{6}<br>17日・じゅうしちにち{6}<br>18日・じゅうはちにち{6}<br>19日・じゅうくにち{3}<br>20日・はつか{0}<br>21日・にじゅう{1}・いちにち{4}<br>22日・にじゅう{1}・ににち{3}<br>           にじゅう{1}・ににち{1}<br>23日・にじゅう{1}・さんにち{1}<br>　　　にじゅう{1}・さんにち{4}<br>24日・にじゅう{1}・よっか{0}<br>25日・にじゅう{1}・ごにち{1}<br>26日・にじゅう{1}・ろくにち{4}<br>27日・にじゅう{1}・しちにち{4}<br>28日・にじゅう{1}・はちにち{4}<br>29日・にじゅう{1}・くにち{1}<br>30日・さんじゅうにち{3}<br>40日・よんじゅうにち{3}<br>100日・ひゃくにち{4}<br>1000日・せんにち{1} |
| ～分  | ⠀ふん{1} | _See also:_ [_～分_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.h4xxd7p8ctm)　_counter for fractions_ _See also:_ [_～分_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.8wudiml0qrzs)　_suffix_ |
| ～秒  | ⠀びょう{1} |     |
| ～期  | ⠀き{1}  | _See also:_ [_～期_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.8dixs97jpgsh)　_suffix_ |
| ～晩  | ⠀ばん{1} |     |
| ～円  | ⠀えん{1} | `一円・いちえん{0}`<br>`百円・ひゃくえん{0}` |
| ～厘  | ⠀りん{1} |     |
| ～分  | ⠀ぶ{1}  | _See also:_ [_～分_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.6jguy8u0rsr)　_counter for minutes_ _See also:_ [_～分_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.8wudiml0qrzs)　_suffix_ |
| ～割  | ⠀わり{1} |     |
| ～十  | ⠀じゅう{1} | 10・じゅう{1}<br>11・じゅういち{4}<br>　　じゅういち{1}<br>12・じゅうに{3}<br>　　じゅうに{1}<br>13・じゅうさん{0}<br>　　じゅうさん{1}<br>14・じゅうよん{3}<br>　　じゅうよん{1}<br>15・じゅうご{3}<br>　　じゅうご{1}<br>16・じゅうろく{4}<br>　　じゅうろく{1}<br>17・じゅうなな{3}<br>　　じゅうなな{1}<br>18・じゅうはち{4}<br>　　じゅうはち{1}<br>19・じゅうきゅう{3}<br>　　じゅうきゅう{1}<br>20・にじゅう{1}<br>30・さんじゅう{1}<br>40・よんじゅう{1}<br>50・ごじゅう{2} but ごじゅう{0} when followed by another number<br>60・ろくじゅう{3} but ろくじゅう{0} when followed by another number<br>70・ななじゅう{2}<br>80・はちじゅう{3} but はちじゅう{0} when followed by another number<br>90・きゅうじゅう{1} |
| ～百  | ⠀ひゃく{1}<br>ひゃく{2} | 百・ひゃく{2}<br>二百・にひゃく{3}<br>三百・さんびゃく{1}<br>四百・よんひゃく{1}<br>五百・ごひゃく{3}<br>六百・ろっぴゃく{4}<br>七百・ななひゃく{2}<br>八百・はっぴゃく{4}<br>九百・きゅうひゃく{1} |
| ～千  | せん{1} |     |
| ～万  | まん{1} |     |
| ～億  | ⠀おく{1} |     |
| ～兆  | ⠀ちょう{1} |     |
| ～京  | ⠀けい{1} |     |
| ～垓  | ⠀がい{1} |     |
| ～.  | ⠀てん{1} |     |
| ～番  | ⠀ばん{1} | 3番・さんばん{0}<br>　　      さんばん{1}<br> 5番・ごばん{0}<br>一番・いちばん{0} when adverb |
| ～ドル | ⠀どる{1} |     |
| ～センチ | ⠀せんち{1} |     |
| ～キロ | ⠀きろ{1} |     |
| ～パーセント | ぱーせんと{3} |     |
| ～パー | ぱー{1} |     |
| ～羽  | ⠀わ{1}  |     |
| ～匹  | ⠀ひき{1} | may also be written as ～疋 |
| ～頭  | ⠀とう{1} |     |
| ～兎  | ⠀と{1}  |     |
| ～体  | ⠀たい{1} | `一体・いったい{0}　when meaning 'the heck'` |
| ～人  | ⠀にん{1} | _See also:_ [_～人_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.ur8uu5siojml)　people<br>_See also:_ [_～人_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.bh4tts7fcxgu)　kind of person<br>`一人・ひとり{2}`<br>`二人・ふたり{3}`<br>`三人・さんにん{3} but さんにん{0} when it's an adverb`<br>`　　　eg. さんにん{0}　いる{0}`<br>`四人・よにん{2}　but　よにん{0} when it's an adverb`<br>`　　　eg. よにん{0}　いる{0}`<br>`五人・ごにん{2}　but　ごにん{0} when it's an adverb`<br>`　　　eg. ごにん{0}　いる{0}` |
| ～名  | ⠀めい{1} | honorific counter for people<br>_See also:_ [_～名_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.apuplchg019b)　_suffix_ |
| ～階  | かい{0} |     |
| ～棟  | ⠀とう{1} | counter for buildings<br>_See also:_ [_～棟_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=kix.jij6ss5096km)_　suffix_ |
| ～杯  | ⠀はい{1} | `いっぱい{0}　when meaning 'lots'`<br>`5杯・ごはい{0} `|
| ～つ  | つ{1}  | **ignores の rule**<br>`一つ・ひとつ{2}`<br>`七つ・ななつ{2}`<br>`九つ・ここのつ{2}` |
| ～回  | かい{0}<br>　かい{1} | かい{0} for when it’s an adverb<br>かい{1} for when it’s a noun<br>`何回・なんかい{1}`<br>`　　　なんかい{3}`<br>`　　　なんかい{0}` |
| ～度  | ⠀ど{1}  | `一度・いちど{3}　when meaning ''once''`<br>`二度・にど{2}　when meaning ''twice''` |
| ～発  | ⠀はつ{1} |     |
| ～個  | ⠀こ{1}  |     |
| ～歳～才 | ⠀さい{1} |     |
| ～点  | てん{1}<br>⠀てん{1} | てん{1} for counting test marks or points<br>⠀てん{1} for everything else |
| ～組  | ⠀くみ{1} | _See also:_ [_～組_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.sjkddka9mrx2)_　suffix_ |
| ～枚  | ⠀まい{1} | `5枚・ごまい{0}`<br>`  　・ごまい{1} `|
| ～手  | ⠀て{1}  | counter for moves in board games<br>_See also:_ [_～手_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=kix.oqqxpxjasakg)_　suffix_ |
| ～軒  | ⠀けん{1} |     |
| ～話  | ⠀わ{1}  |     |
| ～着  | ⠀ちゃく{1} |     |
| ～冊  | ⠀さつ{1} |     |
| ～本  | ⠀ほん{1} | _See also:_ [_～本_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.sv01vsteaw9)　_suffix_<br>`5本・ごほん{0}`<br>`　  ・ごほん{1} `|
| ～巻  | ⠀かん{1} |     |
| ～代  | ⠀だい{1} | counter for decades or ages<br>_See also:_ [_～代_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=kix.y0xkkei6xz0z)　_suffix_ |
| ～升  | ⠀ます{1} |     |
| ～言  | ⠀こと{1} | eg. 一言、二言 |
| ～丁  | ⠀ちょう{1} |     |
| ～文字 | ⠀もじ{1} |     |
| ～問  | ⠀もん{1} |     |
| ～級  | きゅう{0} |     |
| ～語  | ⠀ご{1}  | counter for words<br>_See also:_ [_～語_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.95ydpsmzmhbp)　_language_ |
| ～種  | ⠀しゅ{1} |     |
| ～箇所 | かしょ{1} |     |
| ～連  | れん{0} |     |
| ～両  | ⠀りょう{1} |     |
| ～曲  | ⠀きょく{1} |     |
| ～口  | ⠀くち{1} |     |
| ～週  | しゅう{0} |     |
| ～桁  | ⠀けた{1} |     |
| ～機  | ⠀き{1}  |     |
| ～色  | ⠀しょく{1} | _See also:_ [_～色_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.vvt7va8f9o6e)　_colour_ |
| ～条  | ⠀じょう{1} |     |
| ～勝  | しょう{0} |     |
| ～敗  | はい{0} |     |
| ～部屋 | ⠀へや{1} | _See also:_ [_～部屋_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.7ao2x5d24uab) _suffix_ |
| ～隻  | ⠀せき{1} |     |
| ～価  | ⠀か{1}  | _See also:_ [_～価_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.oa2ww6qgqj5k)_　suffix_ |
| ～流  | ⠀りゅう{0} | _See also:_ [_～流_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.8abzwawzkwly)_　suffix_ |
| ～品  | ⠀しな{1} | _See also:_ [_～品_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.yli8wo64nlxp)_　suffix_ |
| 〜戸  | ⠀こ{1}  |     |
| 〜貫  | ⠀かん{1} |     |


#### Suffixes
| **_Suffix_** | **_Pitch Accent_** | **_`Exceptions`_** **_and Other Notes_** |
| --- | --- | --- |
| ～2 mora verb stem | 〇〇{0} |` 力持ち・ちからもち{3}`<br>`金持ち・かねもち{3}`<br>`　　　　かねもち{2}`<br><br>eg.<br>時間切れ・じかんぎれ{0}<br>一階建て・いっかいだて{0} |
| ～3 mora+ verb stem | ○○○～{1} |` 暇潰し・ひまつぶし{0}`<br><br>eg.<br>気配り・きくばり{2}<br>昔話・むかしばなし{4}<br>人助け・ひとだすけ{3}<br>桁違い・けたちがい{3} |
| ～後  | ご{1}  |` 放課後・ほうかご{0}`<br>`その後・そのご{0}`|
| ～前  | まえ{1} |     |
| ～時  | ⠀じ{1}  |     |
| ～時  | どき{0} |     |
| ～半  | はん{1} |     |
| ～間  | ⠀かん{1} |     |
| ～ぶり | ぶり{0} |     |
| ～期  | ⠀き{1}  | _See also:_ [_～期_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=kix.5w06x1kmahil)　_counter _ |
| ～弱  | じゃく{1} | eg. 一時間弱・いちじかんじゃく{6} |
| ～強  | きょう{1} | eg. 一時間強・いちじかんきょう{6} |
| ～目  | め{1}  | **_usually_ ignores の rule**<br>～ 目の{0}exists but is still less common than ～ 目の{1} |
| ～倍  | ばい{0} |     |
| ～数  | ⠀すう{1} |     |
| ～以上 | いじょう{1} |     |
| ～以下 | いか{1} |     |
| ～位  | ⠀い{1}  |     |
| ～さん | no effect |` 視聴者さん・しちょうしゃさん{2}`<br>`                      しちょうしゃさん{0}`<br>`彼氏さん・かれしさん{0}`<br>`　　　　　かれしさん{1}`<br>`彼女さん・かのじょさん{0}`<br>`　　　　　かのじょさん{1}`<br>`お客さん・おきゃくさん{0}`<br>`　　　　　おきゃくさん{4}`<br>`美人さん・びじんさん{0}`<br>`お医者さん・おいしゃさん{0}`<br>`　　　　　・おいしゃさん{4} `|
| ～くん | no effect |     |
| ～ちゃん | no effect |     |
| ～様  | no effect |` お客様・おきゃくさま{4}`<br>`旦那様・だんなさま{4}`<br>`仏様・ほとけさま{4}`<br>`お釈迦様・おしゃかさま{4} `|
| ～子  | ⠀こ{1}  |     |
| ～っ子 | ⠀っこ{1} |     |
| ～み  | み⠀{0}  | Only applies to 3 mora or more female given names. So names like 野上・のがみ{1} or 尚文・なおふみ{2} are not exceptions |
| ～野郎 | やろう{2} |     |
| ～名  | ⠀めい{1} | _See also:_ [_～名_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.n0yr6otzfe21)　_honorific counter for people_ |
| ～長  | ⠀ちょう{1} |     |
| ～付け | づけ{0} |     |
| ～人  | ⠀じん{1} | _See also:_ [_～人_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.23gff8i830gs)　_counter for people_<br>`日本人・にほんじん{4}`<br>`台湾人・たいわんじん{3}`<br>`　　　　たいわんじん{5}`<br>`朝鮮人・ちょうせんじん{3}`<br>`　　　　ちょうせんじん{5}`<br>`野蛮人・やばんじん{2}`<br>`　　　　やばんじん{4}`<br>`関西人・かんさいじん{3}`<br>`　　　　かんさいじん{5}`|
| ～人  | にん{0} | _See also:_ [_～人_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.23gff8i830gs)　_counter for people_ |
| ～員  | ⠀いん{1} |     |
| ～達  | ⠀たち{1} | only applies if the base word is flat, otherwise will attach low |
| ～等  | ⠀ら{1}  | only applies if the base word is flat, otherwise will attach low<br>`あんたら{1}`<br>`あんたら{3}` |
| ～者  | ⠀しゃ{1} | `視聴者・しちょうしゃ{2}`<br>`         　  しちょうしゃ{0}` |
| ～者  | もの{0} |     |
| ～手  | ⠀しゅ{1} | operator, driver<br>_See also:_ [_～手_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.1cgnet8mp7yd)　_counter for moves in board games_ |
| ～生  | ⠀せい{1} |     |
| ～家  | か⠀{0}  |     |
| ～家  | ⠀け{1}  |     |
| ～派  | は⠀{0}  |     |
| ～役  | やく{0} |     |
| ～県  | ⠀けん{1} |     |
| ～市  | ⠀し{1}  |     |
| ～シティ | してぃ{1} |     |
| ～道  | ⠀みち{1} |     |
| ～街  | ⠀がい{1} |     |
| ～駅  | ⠀えき{1} |     |
| ～区  | ⠀く{1}  |     |
| ～州  | ⠀しゅう{1} |     |
| ～場  | じょう{0} |     |
| ～先  | さき{0} |     |
| ～地  | ⠀ち{1}  |     |
| ～村  | むら{0} |     |
| ～島  | とう{0} |     |
| ～川  | ⠀がわ{1} | If the word comes out to be 4 mora, がわ{0} is more common |
| ～湾  | ⠀わん{1} |     |
| ～山  | やま{0} |     |
| ～府  | ⠀ふ{1}  |     |
| ～灯  | とう{0} |     |
| ～室  | ⠀しつ{1} |     |
| ～屋  | や⠀{0}<br>⠀や{1} | If the base word is 2 mora then ⠀や{1}, otherwise や⠀{0}<br>`桶屋・おけや{2}`<br>　　　`おけや{0}`<br>`床屋・とこや{0}`<br>`宿屋・やどや{2}`<br>`　　　やどや{0}`<br>`八百屋・やおや{0} `|
| ～館  | ⠀かん{1} |     |
| ～部屋 | べや{0} | _See also:_ [_～部屋_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.8fmqngu76xlk) _counter_ |
| ～店  | ⠀てん{1} | `喫茶店・きっさてん{0}`<br>`　　　　きっさてん{3}` |
| ～小屋 | ごや{0} |     |
| ～棟  | とう{0} | large building<br>_See also_ [_～棟_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=kix.d4z4x6o2f2jv)　_counter_ |
| ～城  | ⠀じょう{1} |     |
| ～字  | ⠀じ{1}  | `ローマ字・ろーまじ{0}`<br>`　　　　　ろーまじ{3}`<br>`当て字・あてじ{0}` |
| ～語  | ご⠀{0}  | language<br>_See also_ [_～語_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.3hpafg3dk439)　_counter_ |
| ～弁  | べん{0} |     |
| ～詞  | ⠀し{1}  |     |
| ～核  | ⠀かく{1} |     |
| ～音  | ⠀おん{1} |     |
 --- | --- | --- |
| ～上  | じょう{0} |     |
| ～内  | ⠀ない{1} |     |
| ～外  | ⠀がい{1} |     |
| ～側  | がわ{0} |     |
| ～ら辺 | らへん{0} |     |
| ～以外 | いがい{1} | for 'longer' words it does not control the pitch accent of the word it is attaching to. For 'shorter' words it often does. |
| ～以内 | いない{1} |     |
| ～部  | ⠀ぶ{1}  | department, club<br>_See also:_ [_～部_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.dbz5tasvcf23)　_counter_ |
| ～学  | ⠀がく{1} |     |
| ～科  | か⠀{0}  |     |
| ～校  | ⠀こう{1} | `予備校・よびこう{0}`<br>`女子校・じょしこう{0}`<br>`男子校・だんしこう{0}` |
| ～戦  | せん{0} | `決勝戦・けっしょうせん{3}`<br>`◯回戦・◯かいせん{2}`<br>` 　eg 一回戦・いっかいせん{3}` |
| ～隊  | たい{0} |     |
| ～軍  | ⠀ぐん{1} |     |
| ～力  | ⠀りょく{1} |     |
| ～罪  | ⠀ざい{1} |     |
| ～技  | わざ{0} |     |
| ～術  | ⠀じゅつ{1} |     |
| ～砲  | ほう{0} |     |
| ～船  | せん{0} |     |
| ～艦  | かん{0} |     |
| ～艇  | てい{0} |     |
| ～兵  | ⠀へい{1} |     |
| ～肉  | ⠀にく{1} | `焼き肉・やきにく{0}` |
| ～寿司 | ⠀ずし{1} |     |
| ～症  | しょう{0} |     |
| ～病  | びょう{0} |     |
| ～癌  | ⠀がん{1} | cancer |
| ～薬  | ⠀やく{1} |     |
| ～痛  | つう{0} |     |

##### Conjugation


| **_Suffix_** | **_Pitch Accent_** | **_`Exceptions`_** **_and Other Notes_** |
| --- | --- | --- |
| i-adj～め | め⠀{0}  |     |
| i-adj～げ | げ⠀{0}  |     |
| masu stem～たて | たて{0} | may also be written as ～立て |
| masu stem～がち | がち{0} |     |
| adj～さ | ⠀さ{1}<br>さ⠀{0} | accented words will be ⠀さ{1}<br>heiban words will be さ⠀{0}<br>`綺麗さ・きれいさ{0}`<br>`暖かさ・あたたかさ{4}`<br>`　　　　あたたかさ{3}`<br>`大きさ・おおきさ{0}` |

##### Everything Else

| **_Suffix_** | **_Pitch Accent_** | **_`Exceptions`_** **_and Other Notes_** |
| --- | --- | --- |
| ～だけ | だけ{2} | **ignores の rule**<br>only affects the pitch accent of counters<br>`少しだけ・すこしだけ{5}`<br>`ちょっとだけ{5}`<br><br>Will affect the accent of a verb if だけ takes on the meaning of 'as much　as' rather than 'only'<br>eg. できるだけ{0}　そうしたい{4}<br>　　できる{2}　だけで{2}　すごい{2}<br>　　見るだけ見る・みるだけ{0}　みる{1}<br>　　見るだけでわかる・みる{1}　だけで{2}　わかる{2}<br>　　好きなだけ食っていいよ・すきなだけ{0}　くって{1}　いいよ{1}<br>       好きなだけではない・すきな{2}　だけでは{2}　ない{1} |
| ～ずつ | ずつ{1} |     |
| ～っぽい | っぽい{2} | is an i-adjective so pitch will change in same way as other adjectives when conjugated |
| ～会  | ⠀かい{1}<br>かい{0} | Four-mora words are flat<br>eg.<br>女子会・じょしかい{0}<br>飲み会・のみかい{0}<br>二次会・にじかい{0}<br>オフ会・おふかい{0}<br><br>⠀かい{1} is considered to be more correct, though most people, particularly younger people, will, to some extent, use かい{0} for some words. Four-mora words are apart from this continuum and are always pronounced that way by everyone. The words below are examples of words where かい{0} is often chosen.<br><br>生徒会・せいとかい{0}<br> 勉強会・べんきょうかい{0}<br>同好会・どうこうかい{0} |
| ～化  | か⠀{0}  |     |
| ～的  | てき{0} |     |
| ～くらい～ぐらい | くらい{1}<br>ぐらい{1} | `これ/この/それ/その/あれ/あの/どれ/どの + ぐらい/くらい will be heiban, though more traditionally どれ～ and どの～ will be atamadaka` |
| ～組  | ぐみ{0} | _See also:_ [_～組_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.ne3nstqd4b9l)　_counter_ |
| ～系  | けい{0} |     |
| ～色  | いろ{0} | _See also:_ [_～色_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.r8jybfyt0mp2)_　counter_ |
| ～中  | ちゅう{0}<br>じゅう{0} |     |
| ～性  | せい{0}<br>しょう{0} | `甲斐性・かいしょう{3}` |
| ～感  | ⠀かん{1} |     |
| ～法  | ほう{0} |     |
| ～物  | もの{0} |     |
| 2 mora accented verb stem＋もの | もの{1}<br>⠀もの{1} | 食べ物・たべもの{3}<br>　　　　たべもの{2}<br>飲み物・のみもの{3}<br>　　　　のみもの{2}<br>持ち物・もちもの{3}<br>  　　　　もちもの{2}<br>建物・たてもの{3}<br>           たてもの{2}<br>生き物・いきもの{3}<br>　　　　いきもの{2}<br>化け物・ばけもの{3}<br>編み物・あみもの{2}<br>　　　　あみもの{3}<br>食い物・くいもの{3}<br><br>借り物・かりもの{0} would not be an exception<br> because 借りる is not accented<br><br>in words where both ⠀もの{1} and もの{1} are acceptable,⠀もの{1} is more traditional, and もの{1} is newer |
| ～物  | ⠀ぶつ{1} |     |
| ～用  | よう{0} |     |
| ～声  | ごえ{1} | `鳴き声・泣き声・なきごえ{3}`<br>`              　　　　なきごえ{0}`<br>`鼻声・はなごえ{0}`<br>`歌声・うたごえ{0}`<br>`           うたごえ{3}`<br>`風邪声・かぜごえ{0}`<br>`萌え声・もえごえ{0}`<br>`喉声・のどごえ{0}` |
| ～好き | ずき{0} |     |
| ～型  | がた{0} |     |
| ～んち | んち{2} | **ignores の rule**<br>only odaka after something flat otherwise it attaches low |
| ～事  | ごと{0} |     |
| ～紙  | ⠀し{1}  |     |
| ～服  | ⠀ふく{1} |     |
| ～機  | ⠀き{1}  |     |
| ～器  | ⠀き{1}  |     |
| ～式  | ⠀しき{1} | ceremony |
| ～式  | しき{0} | style |
| ～箱  | ⠀ばこ{1} | `ゴミ箱・ごみばこ{3}`<br>`　　　　ごみばこ{0}`<br>`空き箱・あきばこ{0}`<br>`下駄箱・げたばこ{0}` |
| ～気味 | ぎみ{0} |     |
| ～分  | ぶん{0} | _See also:_ [_～分_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.6jguy8u0rsr)　_counter for minutes_<br> _See also:_ [_～分_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.h4xxd7p8ctm)　_counter for fractions_ |
| ～台  | だい{0} | bench, table, stand<br> _See also:_ [_～台_](https://docs.google.com/document/d/1ueKxTjL9YSu0aOlU9Fs4hWTGbFiBFBHmeA-GRJmxOlc/edit#bookmark=id.rwvy2a9fxi2n)　_counter_<br>`滑り台・すべりだい{3}` |
| ～顔  | がお{0} |     |
| ～主  | ⠀ぬし{1} | `買い主・かいぬし{0}` |
| ～像  | ⠀ぞう{1} |     |
| ～費  | ⠀ひ{1}  |     |
| ～具  | ⠀ぐ{1}  |     |
| ～品  | ひん{0} | _See also:_ [_～品_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.7orzs2lpkgjv)　counter_ |
| ～師  | ⠀し{1}  |     |
| ～説  | ⠀せつ{1} |     |
| ～姫  | ⠀ひめ{1} |     |
| ～状  | じょう{0} |     |
| ～表  | ひょう{0} |     |
| ～社  | ⠀しゃ{1} |     |
| ～ガン | ⠀がん{1} | gun |
| ～教  | きょう{0} |     |
| 〜キー | ⠀きー{1} |     |
| ～量  | ⠀りょう{1} |     |
| ～代  | だい{0} | charge, cost, price<br>_See also:_ [_～代_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=kix.88vcusx3k)　_counter _ |
| ～族  | ⠀ぞく{1} |     |
| ～車  | ⠀しゃ{1} |     |
| ～質  | ⠀しつ{1} |     |
| ～業  | ⠀ぎょう{1} |     |
| ～行  | ⠀ぎょう{1} |     |
| ～論  | ⠀ろん{1} |     |
| ～書  | しょ{1} | `教科書・きょうかしょ{3}`<br>`履歴書・りれきしょ{0}`<br>`　　　　りれきしょ{4}` |
| ～集  | ⠀しゅう{1} |     |
| ～版  | ばん{0} |     |
| ～ゲー | げー{0} | may also be written as ～ゲ |
| ～コン | こん{0} | complex |
| ～順  | じゅん{0} |     |
| ～帯  | たい{0} |     |
| ～誌  | ⠀し{1}  |     |
| ～座  | ざ⠀{0}  |     |
| ～客  | ⠀きゃく{1} |     |
| ～児  | ⠀じ{1}  |     |
| ～走  | ⠀そう{1} |     |
| ～玉  | だま{0} |     |
| ～編  | へん{0} |     |
| ～計  | けい{0} |     |
| ～柄  | がら{0} |     |
| ～なり | なり{0} |     |
| ～値  | ⠀ち{1}  |     |
| ～犯  | ⠀はん{1} |     |
| ～癖  | ぐせ{0} |     |
| ～宛  | あて{0} |     |
| ～本  | ぼん{0} | _See also:_ [_～本_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.xxtmob97wan3)　_counter_ |
| ～漁  | ⠀りょう{1} |     |
| ～愛  | ⠀あい{1} |     |
| ～界  | ⠀かい{1} |     |
| ～記  | ⠀き{1}  |     |
| ～炉  | ⠀ろ{1}  |     |
| ～産  | さん{0} |     |
| ～国  | ⠀こく{1} |     |
| ～率  | ⠀りつ{1} |     |
| ～策  | ⠀さく{1} |     |
| ～対  | たい{1} |     |
| ～史  | ⠀し{1}  | `日本史・にほんし{0}` |
| ～心地 | ごこち{0} |     |
| ～風  | ふう{0} |     |
| ～神  | ⠀がみ{1}<br>がみ{1} |     |
| ～団  | ⠀だん{1} |     |
| ～欄  | ⠀らん{1} |     |
| ～朝  | ちょう{0} |     |
| ～獣  | ⠀じゅう{1} |     |
| チック<br>ティック | ちっく{1}<br>てぃっく{1} |     |
| ～税  | ⠀ぜい{1} |     |
| ～省  | ⠀しょう{1} |     |
| ～証  | しょう{0} | `免許証・めんきょしょう{3}` |
| ～波  | ⠀は{1}  |     |
| ～死  | ⠀し{1}  |     |
| ～価  | ⠀か{1}  | _See also:_ [_～価_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.gzyp6plgi80e)　_counter_ |
| ～流  | りゅう{0} | _See also:_ [_～流_](https://docs.google.com/document/d/1e5DUuDLPKzYnyX9ZZPp2CXLoxk1ZPwH-Q0a0XCQA-Yc/edit#bookmark=id.vwbdbzlsny44)　_counter_ |
| ～寮  | ⠀りょう{1} |     |
| ～領  | ⠀りょう{1} |     |
| ～料  | ⠀りょう{1} |     |
| ～株  | ⠀かぶ{1} |     |
| ～丸  | ⠀まる{1} |     |
| 〜線  | せん{0} |     |
| 〜犬  | けん{0} |     |
| 〜便  | びん{0} |     |
