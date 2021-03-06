## CIRP各螢幕校核條件
#### 目前所有螢幕 ( 共37張 ) <span id="top"></span>
  - [共同校核條件](#same)
  - [01 表燈（ ）登記單](#01)
  - [02 電力、綜合用電（）登記單](#02)
  - [04 終止契約／復電登記單](#04)
  - [05 變更用電（）登記單](#05)
  - [07 廢止用電登記單](#07)
  - [08 電表（）登記單](#08)
  - [09 軍眷優待用電／退休俸贍養金登記單](#09)
  - [11 過期換表工程明細單（登記單）](#11)
  - [12 表制用電資料更正連絡單](#12)
  - [13 表制用電整批更正計算日連絡單](#13)
  - [14 新增資料更正連絡單](#14)
  - [15 包燈（ ）用電登記單](#15)
  - [16 包燈（ ）用電登記單](#16)
  - [17 包制用電整批更正計算日連絡單](#17)
  - [18 高壓（ ）登記單](#18)
  - [19 需量　終止契約／復電 登記單](#19)
  - [20 高壓需量用電資料更正連絡單](#20)
  - [21 高壓需量用電計收遲付費用連絡單](#21)
  - [22 限制用電資料聯絡單（一）](#22)
  - [23 停電資料連絡單](#23)
  - [24 需量用電整批資料更單](#24)
  - [26 特殊用電聯絡單](#26)
  - [27 用戶基本資料更正連絡單](#27)
  - [35 臨時用電保證戶數聯絡單](#35)
  - [36 中央空調用電登記單](#36)
  - [37 臨時用電登記單（附頁）](#37)
  - [38 公共設施電費分攤登記單](#38)
  - [40 表制零星更正電號填報單（聯絡單）](#40)
  - [41 表制收費資料聯絡單](#41)
  - [42 營利事業統一編號填報單(登記單)](#42)
  - [43 延遲繳付費用資料聯絡單](#43)
  - [45 備用電力登記單(附頁)](#45)
  - [80 人工隨時核算明細表](#80)
  - [90 需量用電資料更正聯絡單（５１／７０變動）](#90)
  - [92 表制用電資料更正聯絡單（５１／７０變動）](#92)
  - [97 需量競價聯合型登記單](#97)
  - [98 需量電力綜合用電()登記單](#98)
***
#### 共同校核條件 <span id="same"></span>
> *1.多個螢幕都共同擁有的校核條件。*  
> *2.手冊不包含單一欄位的校核條件，如不清楚欄位需填內容可翻閱核算手冊。*
  - 輸入民國年月日
  - 變動日不可為半年前
  - 輸入人員、電號需同區
  - 電號、縣市別需同區
  - 整理號碼: 1~6位數字、不可為空
  - 計算日: 2位數字、不可為空，可接受清單為**CYCLEL**
  - 電號: 11位數字、不可為空
  - 電表型別之檢定年月不可超過未來，也不可小於目前年月
  - 倍數 = 比流*比壓器值
  - 電表型別之倍數，必須一致
  - 電表形式限制相別輸入，**不能** 為以下規則，否則為錯
    - 電表型式有值，但不是兩個字元
    - 電表型式有值，倍數為空或缺填
    - 電表型式有值且相別有值且電表型式可接受，此情況若倍數<=1為錯
***
#### 特殊校核條件
  - 馬祖發行類別限制只能1或2、計算日限制11-16
    - 適用螢幕: 01、02、12、13、27、40
  - 特殊計費L 只能用於台東
    - 適用螢幕: 01、02、12
  - 行政區有饋線輸入限制，只能輸入同一區處的饋線
    - 適用螢幕: 01、02、12、15、16、18、20、80
  - 17日序，計算日必須07，變動必須00
    - 適用螢幕: 01、02
  - **只有**變動別**12**可以電表號碼有值，但指數無值
    - 適用螢幕: 01、02、04、05、08、98
  - 低壓三段式相關
    - 適用螢幕: 04、08、09、92
      - 9,10表有輸入,1,3,6,8,9,10,11,12表必填,2表不可填
    - 適用螢幕: 04、05、08、19，允許的輸入電表組合
      - [1]
      -	[1,4]
      -	[1,6]
      -	[1,4,6]
      -	[1,3,6,8,11,12]
      -	[1,3,4,6,8,11,12]
      -	[1,3,6,8,9,10,11,12]
      -	[1,3,4,6,8,9,10,11,12]
      -	[1,3,11]
      -	[1,3,4,11]
      -	[1,2,6]
      -	[1,2,4,6]
      -	[1,2,3,6,8,11,12]
      -	[1,2,3,4,6,8,11,12]
      -	[1,3]
      -	[1,3,4]
      -	[1,3,9]
      -	[1,3,4,9]
###### [回到最上面](#top)
***
#### 01 表燈（ ）登記單 <span id="01"></span>
  - 00、01變動，契約**不可**為2或3
  - 變動別00、01、02、03、04、21，限制以下輸入
    - 發行類別限制輸入：1、2、3、4、5、6
    - 收費帳戶限制輸入：B、C、D、E、F、G、H、K、L、S
    - 縣市別限制輸入：
      - 01、02、03、04、05、11、13、14、15、16、17、18、19、
      - 21、22、23、24、31、32、33、34、35、36、37、41、42、
      - 43、51、52、53、61、62
    - 用戶類別限制輸入：1~8
  - 契約別1、2、3，不可輸入三表
  - 契約別K
    - 用電種類需為0、2、3、5、6、7、8、9、A
  - 契約別非K
    - 變動別需為00、01、02、03、04、21
    - 用電種類需為0、2、3、5、6、7、8、9、A
  - 用電種類7、8  收費帳戶需為 B、C
  - 01、02、03表有輸入時，且電表型式不為空時，以下必填
    - 電表組別、相別、安培、位數
    - 電表號碼、檢定年、檢定月、指數
  - 02、03電表號碼及位數都要和01表相同
  - 如電表01、04表形式都有值 則兩邊相別、倍數需相同
  - 如1表為GTN開頭之電表則01、04表下列條件都需相同
    - 電表號碼、安培、形式、檢定年、檢定月
  - 04表相別不可為A、B、C、D、P、Q、R
  - 無效表個數不管有沒有輸入或者為0時，電表型式都必須有值
  - TC、TU、RU 倍數表，倍數需>1
  - GD、TL、TT、TV、TX、RV、RT、RW、FT、KT、WT非倍數表，倍數只能=1
  - 相別限制比壓器比值
    - 相別2：比壓必須8200、1400、808.2
    - 相別3、P、T：比壓必須30 
    - 相別4、7、Q：比壓必須60
    - 相別A、B、C、D、E、F、G、H、J、K、L：比壓必須1
    - 相別I：比壓必須4 
    - 相別R、W：比壓必須100
    - 相別X：比壓必須200、300、350
    - 相別Y：比壓必須200
  - 相別、契約別限制代用別
    - 相別F、L且契約6、9、8、A：代用別必須2
    - 相別F、L且契約4、7、C、D、F且比壓比值小於1：代用別必須8
    - 相別S、T、U、V、W、X、Y、Z、2、3、4、7、8：代用別必須6
  - 可接受的電表型式
    - 瓦時計：24、30、32、34、38、3F
    - 高壓：GB、GE、TB、TA、TI、WA、WB
    - 乏時計：C8、D3、D4、E1、E2
    - IPP電子式電表：I3、I4、I5、W5
    - 電子表：G1、G2、G5、T1、T2、W1、W2
    - 低壓AMI：TE、TK、GU、KU、WU
    - 其他
      - 3G、3H、40、41、43、46、48、49、4A、4D、4E、4G、4I、4J、4K、50、
      - 61、62、63、64、65、66、67、68、84、85、86、87、89、90、91、93、96、97
  - 收費帳戶限制收費戶區輸入規則
    - 收費帳戶為D，收費戶區：00A~00Z
    - 收費帳戶為E，收費戶區：[123489][0-9][0-9]
    - 收費帳戶為F，收費戶區：[B-Z][123489][A-Z]
    - 收費帳戶為J，收費戶區：Q[A-Z][0-9A-Z]
    - 收費帳戶I，收費戶區第一碼與電號前兩碼輸入 **不能** 為以下規則，否則為錯
      - 收費區第一碼為A 或 D 且 電號開頭為00、01、02、05、16
      - 收費區第一碼為B 且 電號開頭為01、18
      - 收費區第一碼為C 或 G 且 電號開頭為06
      - 收費區第一碼為H 且 電號開頭為07
      - 收費區第一碼為Y 且 電號開頭為19
  - 特殊計費別為2、3、4、7、9、M、N的情況下，**不能** 為以下規則，否則為錯
    - 契約別非7、9、A、D
    - 用電別非5
    - 特殊計費別為2但行業別非012、013
    - 特殊計費別為2但行業別非013、082、083、086
    - 特殊計費別為4、M但行業別非013、082、083、086
    - 特殊計費別為7但行業別非013、040
    - 特殊計費別為9但行業別非011、013、086
    - 特殊計費別為N但行業別非082、083、086
  - 發行類別1或2，計算日必須等同日別
    
###### [回到最上面](#top)
***
#### 02 電力、綜合用電（）登記單 <span id="02"></span>
  - 改成簡易時間未滿一年不可申請3L變動
  - 變動別00、01，契約別**不可**為4、7
  - 變動別00、01、03、04、21、02、80、81、82、83、84、85、86、87、88、89，契約需為4、7、C、D、F、K
  - 變動別00、01、02、03、04、21
    - 發行類別需為：1、2、3、4、5、6
    - 收費帳戶需為：B、C、D、E、F、G、H、K、L、S
    - 收費戶區必填
    - 縣市別限制輸入：
      - 01、02、03、04、05、11、13、14、15、16、17、18、19、
      - 21、22、23、24、31、32、33、34、35、36、37、41、42、
      - 43、51、52、53、61、62
      - 用戶類別限制輸入：1~8
  - 契約別1、2、3，3表不可填
  - 契約別C、D，06表需量計必填
  - 契約別C、D 相別F、L、T、Q、U、W、Y、2、3、4、6、7、8且契約容量總合(經常+離峰+非夏+周六半) >= 30KW, 4表無效表必填
  - 契約別F, 3、6、8、11、12表必填
  - 契約別F且相別F、L且契約容量總合(經常+離峰+非夏+周六半) >= 20KW， 4表無效表必填
  - 契約K
    - 經常契約容量不可填
    - 用電用途必填
    - 用電種類需是0、2、3、5、6、7、8、9、A
    - 電表1、3必須輸入型式；4、9不一定需輸入；2、6、8、10、11、12不可輸入型式
  - 契約非K
    - 變動別必須是00、01、02、03、04、21，用電種類必須是0、2、3、5、6、7、8、9、A
    - 契約容量須輸入
  - 用電種類7、8  收費帳戶需為 B、C
  - 電表型式之倍數需一致
  - 4表相別不可為A、B、C、D、P、Q、R
  - 離峰用電，03離峰表必填
  - TC、TU、RU 倍數表，倍數需>1
  - GD、TL、TT、TV、TX、RV、RT、RW、FT、KT、WT非倍數表，倍數只能=1
  - 無效表個數不管有沒有輸入或者為0時，電表型式都必須有值
  - 如電表01、04表形式都有值 則兩邊相別、倍數需相同
  - 如1表為GTN開頭之電表則01、04表下列條件都需相同
    - 電表號碼、安培、形式、檢定年、檢定月
  - 以下欄位如果後者有值，則後者與前者需一致
    - 1、2表：電表號碼
    - 1、2表：位數
    - 1、3表：電表號碼
    - 1、2表：位數
    - 1、4表：電表號碼
    - 1、4表：相別
    - 1、4表：位數
    - 1、4表：電表型式
    - 1、6表：電表號碼
    - 1、6表：位數
    - 1、8表：電表號碼
    - 1、8表：位數
    - 1、9表：電表號碼
    - 1、9表：位數
    - 1、10表：電表號碼
    - 1、10表：位數
    - 1、11表：電表號碼
    - 1、11表：位數
    - 1、12表：電表號碼
    - 1、12表：位數
  - 電表型式有輸入時，以下欄位必填
    - 電表組別、相別、安培、位數
    - 電表號碼、檢定年、檢定月、指數
  - 可接受的電表型式
    - 瓦時計：24、30、32、34、38、3F
    - 高壓：GB、GE、TB、TA、TI、WA、WB
    - 乏時計：C8、D3、D4、E1、E2
    - IPP電子式電表：I3、I4、I5、W5
    - 電子表：G1、G2、G5、T1、T2、W1、W2
    - 低壓AMI：TE、TK、GU、KU、WU
    - 其他
      - 3G、3H、40、41、43、46、48、49、4A、4D、4E、4G、4I、4J、4K、50、
      - 61、62、63、64、65、66、67、68、84、85、86、87、89、90、91、93、96、97
  - 相別限制比壓器比值
    - 相別2：比壓必須8200、1400、808.2
    - 相別3、P、T：比壓必須30 
    - 相別4、7、Q：比壓必須60
    - 相別A、B、C、D、E、F、G、H、J、K、L：比壓必須1
    - 相別I：比壓必須4 
    - 相別R、W：比壓必須100
    - 相別X：比壓必須200、300、350
    - 相別Y：比壓必須200
  - 相別、契約別限制代用別
    - 相別F、L且契約6、9、8、A：代用別必須2
    - 相別F、L且契約4、7、C、D、F且比壓比值小於1：代用別必須8
    - 相別S、T、U、V、W、X、Y、Z、2、3、4、7、8：代用別必須6
  - 時間電價相關
    -  輸入1、3、4、9表時，時間電價必須是3
    -  輸入1、3、9表時，時間電價必須是3
    -  輸入1、3、4表時，時間電價必須是2
    -  輸入1、3表時，時間電價必須是2
    - 契約別C、D、F,時間段數3,必填9,10表
    - 僅9表有填，時間段數3，契約別為K
  - 特殊計費別為2、3、4、7、9、M、N的情況下，**不能** 為以下規則，否則為錯
    - 契約別非7、9、A、D
    - 用電別非5
    - 特殊計費別為2但行業別非012、013
    - 特殊計費別為2但行業別非013、082、083、086
    - 特殊計費別為4、M但行業別非013、082、083、086
    - 特殊計費別為7但行業別非013、040
    - 特殊計費別為9但行業別非011、013、086
    - 特殊計費別為N但行業別非082、083、086
  - 發行類別1或2，計算日必須等同日別
###### [回到最上面](#top)
***
#### 04 終止契約／復電登記單 <span id="04"></span>
  - 變動別8開頭，以下必填
    - 組別
    - 1表
    - 終止契約日期：必須今天之前、停電日之後
  - 變動別非8開頭，下列欄位必填
    - 表別、電表型式、相別、安培
    - 電表位數、電表號碼、檢定年、檢定月
    - 1表倍數 = 比流x比壓
  - 09、10表有輸入，01、03、06、08、09、10、11、12必填
  - 電表型式有輸入時，以下欄位必填
    - 電表組別、相別、安培、位數
    - 電表號碼、檢定年、檢定月、指數
  - TC、TU、RU 倍數表，倍數需>1
  - GD、TL、TT、TV、TX、RV、RT、RW、FT、KT、WT非倍數表，倍數只能=1
  - 如電表01、04表形式都有值 則兩邊相別、倍數需相同
  - 如1表為GTN開頭之電表則01、04表下列條件都需相同
    - 電表號碼、安培、形式、檢定年、檢定月
  - 以下欄位如果後者有值，則後者與前者需一致
    - 1、2表：電表號碼
    - 1、2表：位數
    - 1、3表：電表號碼
    - 1、3表：位數
    - 1、6表：電表號碼
    - 1、6表：位數
    - 1、8表：電表號碼
    - 1、8表：位數
    - 1、9表：電表號碼
    - 1、9表：位數
    - 1、10表：電表號碼
    - 1、10表：位數
    - 1、11表：電表號碼
    - 1、11表：位數
    - 1、12表：電表號碼
    - 1、12表：位數
  - 4表相別不可為A、B、C、D、P、Q、R
  - 可接受的電表型式
    - 瓦時計：24、30、32、34、38、3F
    - 高壓：GB、GE、TB、TA、TI、WA、WB
    - 乏時計：C8、D3、D4、E1、E2
    - IPP電子式電表：I3、I4、I5、W5
    - 電子表：G1、G2、G5、T1、T2、W1、W2
    - 低壓AMI：TE、TK、GU、KU、WU
    - 其他
      - 3G、3H、40、41、43、46、48、49、4A、4D、4E、4G、4I、4J、4K、50、
      - 61、62、63、64、65、66、67、68、84、85、86、87、89、90、91、93、96、97
  - 相別限制比壓器比值
    - 相別2：比壓必須8200、1400、808.2
    - 相別3、P、T：比壓必須30 
    - 相別4、7、Q：比壓必須60
    - 相別A、B、C、D、E、F、G、H、J、K、L：比壓必須1
    - 相別I：比壓必須4 
    - 相別R、W：比壓必須100
    - 相別X：比壓必須200、300、350
    - 相別Y：比壓必須200
###### [回到最上面](#top)
***
#### 05 變更用電（）登記單 <span id="05"></span>
  - 變動別21不可輸入契約容量
  - 變動別33、37，契容相加需大於0
  - 變動別45，1表(61~65)不可填，除此之外必填
  - 變動別3K
    - 不可輸入2、6、8、10、11、12表
    - 必填1、3表
  - 如變動別非27，變更後契約、用電種類必填
  - 變動別限制變更前後契約別
    - 變動別30：舊契約別需為[1、2、3]，新契約別需為[1、2、3] 
    - 變動別31：舊契約別需為[F]，新契約別需為[1]
    - 變動別32：
      - 舊契約別需為[C、D、4、7]，新契約別需為[F]
      - 舊契約別需為[F]，新契約別需為[C、D]
    - 變動別33：舊契約別需為[1、2、3]，新契約別需為[C、D、5、8]
    - 變動別34：舊契約別需為[C、D、4、5、7、8]，新契約別需為[1、2、3]
    - 變動別35：舊契約別需為[C、D、4、5、7、8]，新契約別需為[C、D、5、8]
    - 變動別36：舊契約別需為[C、4、5]，新契約別需為[C、5]
    - 變動別37：舊契約別需為[1]，新契約別需為[F]
    - 變動別39：舊契約別需為[D、7、8]，新契約別需為[D、7、8]
    - 變動別3K：舊契約別需為[1、4、7、C、D、F]，新契約別需為[K]
    - 變動別3L：舊契約別需為[K]，新契約別需為[1、C、D、F]
    - 變動別不為空，舊契約和新契約相同：正確
  - 變動別有填、變更後契約為K，則經常契容不可填、用電用途必填
  - 變更後契約1或K，用途別必填
  - 契約、用電別有填，行業別必填
  - 契約別C、D 相別F、L、T、Q、U、W、Y、2、3、4、6、7、8且契約容量總合(經常+離峰+非夏+周六半) >= 30KW, 4表無效表必填
  - 契約別C、D、F,時間段數3,必填9、10表。反之亦然
  - 契約別F且相別F、L且契約容量總合(經常+離峰+非夏+周六半) >= 20KW， 4表無效表必填
  - 用電種類7、8 ，收費帳戶需為 B、C
  - 檢查01表代用別、倍數
    - 如電表組別沒輸入，不處理
    - 如變更後契約種類6、8、9、A且相別為F、L：**代用需等於2**
    - 如變更後契約種類4、7、C、D、F且相別為F、L且比壓值小於1：**代用別需等於8**
  - TC、TU、RU 倍數表，倍數需>1
  - GD、TL、TT、TV、TX、RV、RT、RW、FT、KT、WT非倍數表，倍數只能=1
  - 電表型式有輸入時，以下欄位必填
    - 電表組別、相別、安培、位數
    - 電表號碼、檢定年、檢定月、指數
  - 以下欄位如果後者有值，則後者與前者需一致
    - 01、02表：電表號碼
    - 01、03表：電表號碼
    - 01、06表：電表號碼
    - 01、08表：電表號碼
    - 01、09表：電表號碼
    - 01、10表：電表號碼
    - 01、11表：電表號碼
    - 01、12表：電表號碼
    - 01、02表：位數
    - 01、03表：位數
    - 01、08表：位數
    - 01、09表：位數
    - 01、10表：位數
    - 01、11表：位數
    - 01、12表：位數
  - 以下欄位如第一欄有值，二、三欄任一欄為空則錯(NecessaryRule)
    - 裝表電表型式、裝表電表組別、裝表變動
    - 拆表電表號碼、拆表電表組別、拆表變動
    - 拆表變動、拆表電表號碼、拆表變動(怪)
  - 電表變動別12，故障代碼必填
  - 拆、裝表變動別限制
    - (裝表變動0開頭或1開頭) 且 拆表變動為空 -> 正確
    - 裝表變動為空 且 拆表變動為16 -> 正確
    - 裝表變動 = 拆表變動 -> 正確
  - 可接受的電表型式
    - 瓦時計：24、30、32、34、38、3F
    - 高壓：GB、GE、TB、TA、TI、WA、WB
    - 乏時計：C8、D3、D4、E1、E2
    - IPP電子式電表：I3、I4、I5、W5
    - 電子表：G1、G2、G5、T1、T2、W1、W2
    - 低壓AMI：TE、TK、GU、KU、WU
    - 其他
      - 3G、3H、40、41、43、46、48、49、4A、4D、4E、4G、4I、4J、4K、50、
      - 61、62、63、64、65、66、67、68、84、85、86、87、89、90、91、93、96、97
  - 04表相別不可為A、B、C、D、P、Q、R
  - 如電表01、04表形式都有值 則兩邊相別、倍數需相同
  - 如1表為GTN開頭之電表則01、04表下列條件都需相同
    - 電表號碼、安培、形式、檢定年、檢定月
  - 相別限制比壓器比值
    - 相別2：比壓必為8200、1400、808.2
    - 相別3、P、T：比壓必為30 
    - 相別4、7、Q：比壓必為60
    - 相別A、B、C、D、E、F、G、H、J、K、L：比壓必為1
    - 相別I：比壓必為4  
    - 相別R、W：比壓必為100
    - 相別X：比壓必為200、300、350
    - 相別Y：比壓必為200
  - 收費帳戶限制收費戶區輸入規則
    - 收費帳戶為D，收費戶區：00A~00Z
    - 收費帳戶為E，收費戶區：[123489][0-9][0-9]
    - 收費帳戶為F，收費戶區：[B-Z][123489][A-Z]
    - 收費帳戶為J，收費戶區：Q[A-Z][0-9A-Z]
    - 收費帳戶I，收費戶區第一碼與電號前兩碼輸入 **不能** 為以下規則，否則為錯
      - 收費區第一碼為A 或 D 且 電號開頭為00、01、02、05、16
      - 收費區第一碼為B 且 電號開頭為01、18
      - 收費區第一碼為C 或 G 且 電號開頭為06
      - 收費區第一碼為H 且 電號開頭為07
      - 收費區第一碼為Y 且 電號開頭為19
  - 特殊計費6，變動別需5開頭
  - 特殊計費別為2、3、4、7、9、M、N的情況下，**不能** 為以下規則，否則為錯
    - 契約別非7、9、A、D
    - 用電別非5
    - 特殊計費別為2但行業別非012、013
    - 特殊計費別為2但行業別非013、082、083、086
    - 特殊計費別為4、M但行業別非013、082、083、086
    - 特殊計費別為7但行業別非013、040
    - 特殊計費別為9但行業別非011、013、086
    - 特殊計費別為N但行業別非082、083、086
  - 三段式時間電價相關
    - 輸入1、3、4、9表時，時間電價必須是3
    - 輸入1、3、9表時，時間電價必須是3
    - 輸入1、3、4表時，時間電價必須是2
    - 輸入1、3表時，時間電價必須是2
    - 段數2
      - 1、3表必填; 2、9、10表不可填
      - 6、8、11、12表任一有填,則都必填
    - 段數3
      - 1、3、9表必填，2表不可填
      - 6、8、11、12表任一有填，則都必填
  - 故障代碼有填，需任一變動別為12
###### [回到最上面](#top)
***
#### 07 廢止用電登記單 <span id="07"></span>
  - E卡計算日必須等於14
###### [回到最上面](#top)
***
#### 08 電表（）登記單 <span id="08"></span>
  - E卡計算日必須等於14
  - 變動別12，故障代碼必填
  - 故障代碼有填，需一變動別為12
  - 養殖漁業契容有值，一表必填，容量需介於1~499; 0表示取消
    - 0~99，相別須為D、F、L
    - 大於99，相別必填L
  - 以下欄位如果後者有值，則後者與前者需一致
    - 01、02表：電表號碼
    - 01、02表：位數
    - 01、03表：電表號碼
    - 01、03表：位數
    - 01、06表：電表號碼
    - 01、06表：位數
    - 01、08表：電表號碼
    - 01、08表：位數
    - 01、09表：電表號碼
    - 01、09表：位數
    - 01、10表：電表號碼
    - 01、10表：位數
    - 01、11表：電表號碼
    - 01、11表：位數
    - 01、12表：電表號碼
    - 01、12表：位數
  - 04表相別不可為A、B、C、D、P、Q、R
  - 如電表01、04表型式都有值 則兩邊相別、倍數需相同
  - 如1表為GTN開頭之電表則01、04表下列條件都需相同
    - 電表號碼、安培、形式、檢定年、檢定月
  - 可接受的電表型式
    - 瓦時計：24、30、32、34、38、3F
    - 高壓：GB、GE、TB、TA、TI、WA、WB
    - 乏時計：C8、D3、D4、E1、E2
    - IPP電子式電表：I3、I4、I5、W5
    - 電子表：G1、G2、G5、T1、T2、W1、W2
    - 低壓AMI：TE、TK、GU、KU、WU
    - 其他
      - 3G、3H、40、41、43、46、48、49、4A、4D、4E、4G、4I、4J、4K、50、
      - 61、62、63、64、65、66、67、68、84、85、86、87、89、90、91、93、96、97
  - TC、TU、RU 倍數表，倍數需>1
  - GD、TL、TT、TV、TX、RV、RT、RW、FT、KT、WT非倍數表，倍數只能=1
  - 拆01表如變動非16或裝01表有輸入變動，則必填[電表組別、檢定年、檢定月]
  - 拆、裝表 變動別限制
    - 裝表變動 = 拆表變動 -> 正確
    - 裝表變動為0X或1X 且拆表變動為空 -> 正確
    - 裝表變動為空且拆表變動為16 -> 正確
  - 以下欄位如第一欄有值，二、三欄任一欄為空則錯(NecessaryRule)
    - 裝表電表型式、裝表電表組別、裝表變動
    - 拆表變動、拆表電表號碼、拆表變動(怪)
###### [回到最上面](#top)
***
#### 09 軍眷優待用電／退休俸贍養金登記單 <span id="09"></span>
  - 以下欄位如果後者有值，則後者與前者需一致
    - 優待變更前(25)、變更後(27)
    - 取消變更前(25)、變更後(27)
  - 流動電費+表租必須等於合計
  - 合計欄位不得大於0
  - 各變動規則
    - 優待變動
      - 如變動不為空，變更前(25-26)跟變更後(27-28)任一格為空則錯
      - 現役及領緒變動**不可**都空
    - 現役變動
      - 如變動不為空，[優待變動、現役位置(25-27)、現役軍人國民身份證號碼或撫卹令字號(28-38)]任一為空則錯
    - 領恤變動
      - 如變動不為空，[現役位置(25-27)、現役軍人國民身份證號碼或撫卹令字號(28-38)]任一為空則錯
    - 申請或取消退休俸贍養金人員補助變動
      - 如變動不為空，[結算別(24)、1表(25-29)]任一為空則錯
    - 特殊計費變動
      - 如變動不為空，[位置、更正內容)]任一為空則錯
    - 退休俸資料
      - 如變動不為空，[位置、更正內容)]任一為空則錯
    - 加/減收金額
      - 如變動不為空，結算別為空則錯 
###### [回到最上面](#top)
***
#### 11 過期換表工程明細單（登記單） <span id="11"></span>
###### [回到最上面](#top)
***
#### 12 表制用電資料更正連絡單 <span id="12"></span>
  - 027收費帳號I、J、W
    - 479銀行代號必填；否則不可填
    - 480金資代號必填；否則不可填
  - 紓困級距有輸入1、2、9時，109年不可輸入1、2月，且只能01日序
  - 紓困按日比例取消如輸入0，變動月份不可輸入01、02
###### [回到最上面](#top)
***
#### 13 表制用電整批更正計算日連絡單<span id="13"></span>
  - 收費帳戶I，收費戶區第一碼與電號前兩碼輸入 **不能** 為以下規則，否則為錯
    - 收費區第一碼為A 或 D 且 電號開頭為00,01,02,05,16
    - 收費區第一碼為C 或 G 且電號開頭為06
    - 收費區第一碼為B 且電號開頭為01,18
    - 收費區第一碼為Y 且電號開頭為19
    - 收費區第一碼為H 且電號開頭為07
  - 收費帳戶限制收費戶區輸入規則
    - 收費帳戶為D，收費戶區：00A~00Z
    - 收費帳戶為E，收費戶區：[123489][0-9][0-9]
    - 收費帳戶為F，收費戶區：[B-Z][123489][A-Z]
    - 收費帳戶為J，收費戶區：Q[A-Z][0-9A-Z]
  - 日序、新計算日任一為空則錯
  - 最高用戶電號需>=最低用戶電號
  - 最低用戶電號和最高用戶電號需一致，日序必須17，新計算日需07
  - 輸入日，最高用戶電號和最低用戶電號不可重複輸入
###### [回到最上面](#top)
***
#### 14 新增資料更正連絡單 <span id="14"></span>
  - 以下欄位如果A欄有值，B欄沒值 則錯
    - 更正一般制用戶新增資料
      - 52變動、用戶卡號
      - 用戶電力、用戶52變動
      - 用戶電熱、用戶52變動
      - 用戶電燈、用戶52變動
      - 用戶部分送電、用戶52變動
      - 用戶總表分錶／共用電表、用戶52變動
      - 用戶用電用途、用戶52變動
    - 更正或取消高壓需量用戶新增資料
      - 52變動、用戶卡號
      - 用戶電力、用戶52變動
      - 用戶電熱、用戶52變動
      - 用戶電燈、用戶52變動
      - 用戶部分送電、用戶52變動
      - 用戶總表分錶／共用電表、用戶52變動
  - C卡必填一般制用戶52變動欄位
  - C卡必填高壓需量制用戶52變動欄位
###### [回到最上面](#top)
***
#### 15 包燈（ ）用電登記單 <span id="15"></span>
  - 至少需要輸入一個卡號，但02變動或70至90變動不在此限
  - 以下欄位內容任一有填則第二欄卡號必填2
    - 欄位(75-103)
    - 第二欄欄位(23-70)
    - 如欄位全部未填卻有第二欄卡號 -> 錯 
  - 以下欄位內容任一有填則第三欄卡號必填1
    - 第三欄(23-34)
    - 租桿費/市區點數	
    - 契約別
    - 用電別
  - 卡號有填且變動別非40、41、42、92
    - 契約別需0或B
    - 用電種類必須是0、2、5、7、8、A、F、C、B
    - 如變動別為00、01、03、04 且 契約別為0，夜/日夜供電須為1或2
    - 收費區必填
    - 縣市別卡控
      01|02|03|04|05|11|13|14|15|16|17|18|19|21|22|23|24|31|32|33|34|35|36|37|41|42|43|51|52|53|61|62
    - 停電別需等於1
    - 轉帳軍種卡控
      B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|R|S|T|Q|U
    - 用電種類7、8 轉帳單位必填
    - 如收費日不為空，值必須等於01
    - 其他小型器具.超基本容量計費單位有填值>1，則具數不可小於1
    - 鐵路警報器 超基本容量計費單位有填值>1，則具數不可小於1
  - 卡號有填且變動別非40、41、42、92
    - 契約用電別限制
      - 僅契約用電別0C才能輸入租桿費
      - 契約用電別00，第二欄23-74必填，以下欄位不可輸入
        - 其他小型器具-超基本容量計費單位
        - 其他小型器具-具數
        - 鐵路路簽信號器-超基本容量計費單位
        - 鐵路路簽信號器-具數
        - 鐵路警報器-超基本容量計費單位
        - 鐵路警報器-具數
        - 交通指揮燈(LED路燈)-最大入力數
        - (1)警報器-容量
        - (1)警報器-具數
        - (2)警報器-容量
        - (2)警報器-具數
        - (3)警報器-容量
        - (3)警報器-具數
      - 契約用電別0F，第二欄23-74必填，以下欄位不可輸入
        - 其他小型器具-超基本容量計費單位
        - 其他小型器具-具數
        - 鐵路路簽信號器-超基本容量計費單位
        - 鐵路路簽信號器-具數
        - 鐵路警報器-超基本容量計費單位
        - 鐵路警報器-具數
        - (1)警報器-容量
        - (1)警報器-具數
        - (2)警報器-容量
        - (2)警報器-具數
        - (3)警報器-容量
        - (3)警報器-具數
      - 契約用電別B5，以下欄位不可輸入
        - 其他小型器具-超基本容量計費單位
        - 其他小型器具-具數
        - 鐵路路簽信號器-超基本容量計費單位
        - 鐵路路簽信號器-具數
        - 鐵路警報器-超基本容量計費單位
        - 鐵路警報器-具數
        - 交通指揮燈(LED路燈)-最大入力數
        - (1)警報器-容量
        - (1)警報器-具數
        - (2)警報器-容量
        - (2)警報器-具數
        - (3)警報器-容量
        - (3)警報器-具數
        - 第二欄23-74欄位
      - 契約用電別0A，合計容量必填，第二欄23-74必填，以下欄位不可輸入
        - 其他小型器具-超基本容量計費單位
        - 其他小型器具-具數
        - 鐵路路簽信號器-超基本容量計費單位
        - 鐵路路簽信號器-具數
        - 鐵路警報器-超基本容量計費單位
        - 鐵路警報器-具數
        - 交通指揮燈(LED路燈)-最大入力數
        - (1)警報器-容量
        - (1)警報器-具數
        - (2)警報器-容量
        - (2)警報器-具數
        - (3)警報器-容量
        - (3)警報器-具數
      - 契約用電別0B，合計容量必填，以下欄位不可輸入
        - 其他小型器具-超基本容量計費單位
        - 其他小型器具-具數
        - 鐵路路簽信號器-超基本容量計費單位
        - 鐵路路簽信號器-具數
        - 鐵路警報器-超基本容量計費單位
        - 鐵路警報器-具數
        - (1)警報器-容量
        - (1)警報器-具數
        - (2)警報器-容量
        - (2)警報器-具數
        - (3)警報器-容量
        - (3)警報器-具數
        - 第二欄23-74欄位
      - 契約用電別0C，以下欄位不可輸入
        - 其他小型器具-超基本容量計費單位
        - 其他小型器具-具數
        - 鐵路路簽信號器-超基本容量計費單位
        - 鐵路路簽信號器-具數
        - 鐵路警報器-超基本容量計費單位
        - 鐵路警報器-具數
        - (1)警報器-容量
        - (1)警報器-具數
        - (2)警報器-容量
        - (2)警報器-具數
        - (3)警報器-容量
        - (3)警報器-具數 
        - 第二欄23-74欄位
      - 契約用電別08，以下欄位不可輸入
        - 鐵路警報器-具數
        - (1)警報器-容量
        - (1)警報器-具數
        - (2)警報器-容量
        - (2)警報器-具數
        - (3)警報器-容量
        - (3)警報器-具數
      - 除上述契約用電別外，以下欄位不可全部為空
        - 其他小型器具-超基本容量計費單位
        - 其他小型器具-具數
        - 鐵路路簽信號器-超基本容量計費單位
        - 鐵路路簽信號器-具數
        - 鐵路警報器-超基本容量計費單位
        - 鐵路警報器-具數
        - (1)警報器-容量
        - (1)警報器-具數
        - (2)警報器-容量
        - (2)警報器-具數
        - (3)警報器-容量
        - (3)警報器-具數
  - 變動別為00的情況下
    - 用電種類必為8
    - 收費帳戶必為C
    - 轉帳軍種必為C
    - 收費區必為數字
    - 轉帳單位必為數字
    - 以下欄位必填
      - 契約種類、用電種類、收費帳戶、收費區、縣市
      - 供電饋線、用戶類別、卡號、配電場所、轉帳單位、轉帳軍種
  - 契約別0、F且用電別F
    - 變動別40、41，交通指揮燈必填
    - 變動別00，必填之欄位
      - 欄位23到70
      - 合計容量
      - 交通指揮燈(LED路燈)(88-91)
  - 用電種類7、8  收費帳戶需為 B、C
###### [回到最上面](#top)
***
#### 16 包燈（ ）用電登記單 <span id="16"></span>
  - 紓困級距有輸入1、2、9時，不可輸入1、2月，且只能01日
  - 紓困按日比例取消如輸入0，變動月份**不可**輸入01、02
  - 如負號在前(23-29)欄位有值，應加/減收電費**不可**為空(19-20)
###### [回到最上面](#top)
***
#### 17 包制用電整批更正計算日連絡單 <span id="17"></span>
  - 輸入日，最高用戶電號和最低用戶電號不可重複輸入
  - 最高用戶電號需>=最低用戶電號
###### [回到最上面](#top)
***
#### 18 高壓（ ）登記單 <span id="18"></span>
  - 變動別00、01、02、03、04、21
    - 限制用戶類別為1~8
    - 限制縣市別 **必須** 為
      - 01,02,03,04,05,11,13,14,15,16,17,18,19,
      - 21,22,23,24,31,32,33,34,35,36,37,41,42,43,51,52,53,61,62
  - 變動別00、01、03、04、21、02、80、81、82、83、84、85、86、87、88、89，契約種類需為 A、6、8、9
  - 有輸入變動別且收費帳戶H，戶區不可5開頭
  - 有輸入變動別
    - 限制收費帳戶B、C、D、G、H、L、S
    - 限制折扣率輸入為空白、0、2、4
    - 用電種類**必須**為0、2、5、6、7、8、9、T
  - 第二列變動別有填，以下欄位必填
    - 契約種類、用電種類、收費帳戶、收費區、縣市別
    - 送(停)電日期(年)、送(停)電日期(月)、送(停)電日期(日)
    - 經常契容、抄表梯次、用戶類別、供電饋線
  - 契約、用電別有填，行業別必填
  - 用電種類7、8  收費帳戶需為 B、C
  - 以下欄位A欄有填，B欄未填則錯
    - 鐵損度數、變壓容量(KVA)
    - 最後一列 卡號、電表組別
    - 第二列 卡號、變動別
    - 第二列 用電種類、變動別
    - 第三列 卡號、變動別
    - 第三列 契約種類、變動別
    - 最後一列 卡號、變動別
    - 最後一列 電表組別、變動別
  - 轉帳軍種與收費帳戶規則
    - 轉帳軍種B，收費帳戶必為B
    - 轉帳軍種C，收費帳戶必為C
    - 轉帳軍種為[D、E、F、G、H、I、K、L、M、N、O、P、S、T、U、J、Q]， 收費帳戶必為D
  -特殊計費別為2、3、4、7、9、M、N的情況下，**不能** 為以下規則，否則為錯
    - 契約別非7、9、A、D
    - 用電別非5
    - 特殊計費別為2但行業別非012、013
    - 特殊計費別為2但行業別非013、082、083、086
    - 特殊計費別為4、M但行業別非013、082、083、086
    - 特殊計費別為7但行業別非013、040
    - 特殊計費別為9但行業別非011、013、086
    - 特殊計費別為N但行業別非082、083、086
###### [回到最上面](#top)
***
#### 19 需量　終止契約／復電 登記單 <span id="19"></span>
  - 如變動別為14，以下欄位必填
    - 電表型式、電表相別、安培、位數
    - 電表號碼、檢定年、檢定月
  - 1表和4表的電表型式、相別需相同
  - 如1、4表型式都有值 則兩邊相別、倍數需相同
  - 如1表為GTN開頭之電表則1、4表下列條件都需相同
    - 電表號碼、安培、形式、檢定年、檢定月
  - 電表如果檢定年或檢定月有值，電表型式必填
  - 各電表的電表號碼、位數都需與1表電表號碼、位數相同
###### [回到最上面](#top)
***
#### 20 高壓需量用電資料更正連絡單 <span id="20"></span>
  - 收費帳戶限制收費戶區輸入規則
    - 收費帳戶為D，收費戶區：00A~00Z
    - 收費帳戶為E，收費戶區：[123489][0-9][0-9]
    - 收費帳戶為F，收費戶區：[B-Z][123489][A-Z]
    - 收費帳戶為J，收費戶區：Q[A-Z][0-9A-Z]
  - 收費戶區I、J、W
    - 欄位911必填
    - 欄位480必填
    - 反之，如果，如果收戶非I、J、W，此2欄位不可填
  - 紓困級距有輸入1、2、9時，109年不可輸入1、2月，且只能01日
  - 紓困按日比例取消如輸入0，變動月份不可輸入01、02
  - 需量935規則
    - 需量935格，如果輸入E開頭，則第9格必須改成空白
    - 935欄位如果值為以下兩者，直接過
      - AA000000
      - A 000000 
    - 除去上述狀況，935欄位開頭必為B、D、E、F、G、H
      - 開頭為B(需量競價措施)
        - 抑低類型(第2格)必為1~3
        - 如為聯合型3：抑低契約容量不得小於0瓩
        - 其他：抑低契約容量不得小於20瓩
        - 106.01.23改動
          - 條件一：變動日 <= 系統日期
          - 條件二
            - 輸入約定抑低月份 > 系統日期月份
            - 變動日期 <= ((系統年) + (輸入約定抑低月份 )) - 2個月 ) + 系統日
          - 條件三
            - 輸入約定抑低月份 <= 系統日期月份
            - 變動日期 <= ((系統年 + 1) + (輸入約定抑低月份)) - 2個月 ) + 系統日
          - 只要符合 (條件一 + 條件二 ) 或 (條件一 + 條件三 ) 之69變動即可通過CIRP檢核
          - 輸入以下可直接過檢核
            - B 00000001
            - B 00000002
            - B 00000003
            - B 00000004
            - B 00000005
            - B 00000006
            - B 00000007
            - B 00000008
            - B 00000009
            - B 00000010
            - B 00000011
            - B 00000012
      - 開頭為H(緊急通知型)
        - 抑低類型(第2格)必為1~8
        - H 000000 -> 檢核直接過
      - 開頭為D(月減8日型)
        - 欄位長度需介於8~16之間
        - 抑低月份只能為V或空白
        - 抑低類型(第2格)必為空白
        - D 000000 -> 檢核直接過
      - 開頭為E(日減6時型)
        - 欄位長度需介於8~16之間
        - 抑低月份只能為V或空白
        - 抑低類型(第2格)必為空白
        - [E 000000] 或 [E 000000     ] -> 檢核直接過
      - 開頭為F(日減2時型)
        - 欄位長度需介於8~16之間
        - 抑低月份只能為V或空白
        - 抑低類型(第2格)必為空白
        - F 000000 -> 檢核直接過
      - 開頭為G(限電回饋型)
        - 欄位長度為13
        - 抑低類型(第2格)必為空白
        - G 000000 -> 檢核直接過
###### [回到最上面](#top)
***
#### 21 高壓需量用電計收遲付費用連絡單 <span id="21"></span>
###### [回到最上面](#top)
***
#### 22 限制用電資料聯絡單（一 ） <span id="22"></span>
  - E卡只能Cycle 14
  - 限電別B，日數須為0、限電率需為01或02
  - 非限電別B，限電率必為0
  - 只要電號有值，以下欄位必填
    - 卡別、卡號、計算日、變動年、月、日
    - 限電別、限電率、日數、每度報價
  - 如限電別為H、D、E、F
    - 以下必為0
      - 限電前半尖峰最高需量
      - 限電時半尖峰最高需量
      - 解除時段半尖峰最高需量
      - 實際用電最高需量
      - 解除時段離峰最高需量
      - 每度報價
    - 基準用電容量、實際抑低容量需為1~6位數字
  - 如限電別為B
    - 以下必為0
      - 限電前半尖峰最高需量
      - 限電時半尖峰最高需量
      - 解除時段半尖峰最高需量
      - 實際用電最高需量
      - 解除時段離峰最高需量
    - 基準用電容量、實際抑低容量、每度報價需為1~6位數字
  - 如限電別為G
    - 以下必為0
      - 限電前半尖峰最高需量
      - 限電時半尖峰最高需量
      - 解除時段半尖峰最高需量
      - 解除時段離峰最高需量
      - 每度報價
    - 基準用電容量、實際抑低容量、實際用電最高需量需為1~6位數字
###### [回到最上面](#top)
***
#### 23 停電資料連絡單 <span id="23"></span>
  - C卡計算日不能25、變動別54,55
  - F卡計算日只能25、變動別54,55
  - E卡計算日只能14、變動別53,54,55
  - E卡54變動僅能填時數
  - C、F卡54變動，時數、次數必填
  - 53、55變動僅能填次數
  - 停電次數、停電時數，須同為正數或負數
  - 用戶因素有填，停電暗號必填
  - 用戶電號有填，以下必填
    - 卡別、計算日、變動年、月、日、變動別
###### [回到最上面](#top)
***
#### 24 需量用電整批資料更正聯絡單 <span id="24"></span>
  - 輸入日，最高用戶電號和最低用戶電號不可重複輸入
  - 收費帳戶限制收費戶區輸入規則
    - 收費帳戶為D，收費戶區：00A~00Z
    - 收費帳戶為E，收費戶區：[123489][0-9][0-9]
    - 收費帳戶為F，收費戶區：[B-Z][123489][A-Z]
    - 收費帳戶為J，收費戶區：Q[A-Z][0-9A-Z]
  - 最高用戶電號需>=最低用戶電號
###### [回到最上面](#top)
***
#### 26 特殊用電聯絡單 <span id="26"></span>
  - F卡，特殊用電不可輸入E、F、I、J
  - C卡計算日不能25
  - E卡計算日只能14
  - F卡計算日只能25
###### [回到最上面](#top)
***
#### 27 用戶基本資料更正連絡單 <span id="27"></span>
  - C卡計算日不能25、行業別僅能低壓
  - E卡計算日只能14、行業別僅能高壓
  - F卡計算日只能25、行業別不可填
  - A5變動變動日(民國年月日)，不得為半年以前
###### [回到最上面](#top)
***
#### 35 臨時用電保證戶數聯絡單 <span id="35"></span>
  - E卡必須14計算日
###### [回到最上面](#top)
***
#### 36 中央空調用電登記單 <span id="36"></span>
###### [回到最上面](#top)
***
#### 37 臨時用電登記單（附頁）<span id="37"></span>
###### [回到最上面](#top)
***
#### 38 公共設施電費分攤登記單 <span id="38"></span>
  - 母戶、子戶電號有填
    - 子戶變動日期 = 母戶變動日期
    - 公共設施用戶電號如未填，則以母戶填入
    - 卡別、計算日、變動年、月、日、變動別、識別號 必填
  - 如母戶電號無輸入，第一子戶電號、變動日期、公共設施用戶電號必須輸入
###### [回到最上面](#top)
***
#### 40 表制零星更正電號填報單（聯絡單）<span id="40"></span>
  - C卡計算日不能25
  - E卡計算日只能14
  - F卡計算日只能25
###### [回到最上面](#top)
***
#### 41 表制收費資料聯絡單 <span id="41"></span>
  - 收費帳號I、J、W，則銀行代號必填；否則不可填
  - 收費帳號I、J、W，則金資代號必填；否則不可填
  - 卡別E,F，不得輸入轉區日序
  - C卡計算日不能25
  - E卡計算日只能14
  - F卡計算日只能25
  - 電號有輸入，以下欄位必填
    - 卡別
    - 計算日
    - 變動別
    - 變動日期民國年月日
  - 收費帳戶E開頭，收費戶區第一位數僅能填1、2、3、4、8、9
  - 收費帳戶F開頭
    - 收費戶區
      - 第一位數B~Z
      - 第二位數僅能填1、2、3、4、8、9
      - 第三位數A~Z
  - 收費帳戶J開頭且收費戶區第一位為Q
    - 收費戶區第二位須為A~Z
    - 第三位為0~9
    - 感覺還有其他規則...Form41TypeRule
###### [回到最上面](#top)
***
#### 42 營利事業統一編號填報單(登記單) <span id="42"></span>
  - E卡，計算日必須14
###### [回到最上面](#top)
***
#### 43 延遲繳付費用資料聯絡單 <span id="43"></span>
  - C卡計算日不能25
  - E卡計算日只能14
  - F卡計算日只能25
###### [回到最上面](#top)
***
#### 45 備用電力登記單(附頁) <span id="45"></span>
  - 開始時間、結束時間年月日有輸入，時、分都必填
  - 有輸入變動別，用電種類須為0、2、5、6、7、8、9、T
  - 使用備用電力別(36欄位)填寫1或2時，備用電力別(35欄位)**不可**為1、2
  - 使用備用電力別有填寫，[開始時間]"與[結束時間]都 **必填**
  - 備用電力別(35欄位)"為3，[汽電共生超約計算方式] **必填**
  - 三個機組容量只要有一個有填，[備用電力別(35欄位)]**必為**2或3
###### [回到最上面](#top)
***
#### 80 人工隨時核算明細表 <span id="80"></span>
###### [回到最上面](#top)
***
#### 90 需量用電資料更正聯絡單（５１／７０變動） <span id="90"></span>
  - 結算別7，變動必為70
  - 變動別有填，結算別、卡號必填
  - 變動別為51，電表組別須為A~Z或9
  - 所有費用加總須等於合計金額
  - 結算別7、9以下欄位不可填
    - 流動電費(2個流動電費都不行)
    - 功率因數加減收金額	
    - 超約附加費
    - 遲付費用
    - 政府補助金額或空調費
    - 電器租費
    - 自轉
  - 如[基本電費、第一流動電費、功率因數加減收金額、超約附加費、遲付費用、政府補助金額或空調費]其中一個有值
    - 第二變動、第二變動結算別、第二變動卡號不可為空
  - 如[電器租費、第二流動電費、合計金額]其中一個有值
    - 第三變動、第三變動結算別、第三變動卡號不可為空
###### [回到最上面](#top)
***
#### 92 表制用電資料更正聯絡單（５１／７０變動）<span id="92"></span>
  - 結算別7，變動必為70
  - 基本電費 + 流動電費 + 遲付費用 + 電費減免 須等於 合計欄位
  - 結算別7、9，不可填下列欄位
    - 自轉
    - 流動電費
    - 電費減免
    - 遲付費用
###### [回到最上面](#top)
***
#### 97 需量競價聯合型登記單 <span id="97"></span>
  - 如卡別或計算日或群組用戶電號其中一個有填，則三者都必填
###### [回到最上面](#top)
***
#### 98 需量電力綜合用電()登記單 <span id="98"></span>
  - 故障代碼有輸入，至少有一變動別為12
  - 變動別12，故障代碼必填
  - 16變動
    - 不會處理比流、比壓、倍數條件
    - 可不填1表裝表欄位
  - 變動別非16
    - 需量計種類須介於1-6
    - 1表拆表欄位必填
  - 裝表電表型式有填、裝表電表組別、裝表變動必填
  - 電表型別之倍數，需 > 1
  - 高壓新設00~03不得輸入故障代碼 
  - 1、4表 電錶型式、代用別、相別須相同
  - 1、3、4、6、8、9、10、11、12
    - 電表型式有填，則變動別必填
    - 電表號碼、位數需相同
  - 型式有填，以下必填
    - 相別、安培、位數、電表號碼、檢定年、月、指數
###### [回到最上面](#top)