# 系統簡介
---
組&emsp;&emsp;別：第111208組 <br/>
專題名稱： MRTaipei｜台北先生 <br/>
指導教師： 許晉龍老師 <br/>
專題學生： 11036006 王佑強、11036025 柯玄娜、11036027 錢慧蓁、 <br/>
　　　　　 11036029 李崧毓、11036041 龔渝捷

---
## 一、前言
&emsp;&emsp;臺北市是臺灣的金融和經濟中心，擁有許多都會商圈，生活機能包羅萬象，也是許多國內外事業在台發展的首選。說到臺北，就不得不提到臺北頗具代表性的大眾運輸系統—臺北捷運。臺北捷運是臺北都會區非常重要的一項大眾運輸工具，每日約有200萬人次搭乘，是民眾日常通勤和出遊最依賴的交通工具之一，大大提升臺北市的都市機能，促進臺北都會區的繁榮與發展。


&emsp;&emsp;臺北捷運系統固然方便快速，但是當站內連接著其他路線，或是擁有好幾個出口，就很容易讓人迷失方向。為了初來乍到臺北這個大都會圈的北漂青年，又或者是平常甚少使用捷運系統的民眾，時常苦於看不懂站內外地圖，而造成繞遠路的情形，如何協助他們在搭乘捷運時能夠以更有效率的方式進行移動，會是值得深思的課題。


&emsp;&emsp;近年來，環保意識抬頭，除了捷運之外，使用腳踏車作為代步工具蔚為風潮，臺北市首先推出YouBike服務，不僅能讓民眾自由穿梭於大眾運輸工具未達之處，更能以漫遊的方式探索臺北，與捷運相輔相成，打造無縫交通網。YouBike服務固然便利，但民眾在前往騎乘前仍可能有所顧慮，例如該站點是否還有車輛可供租借，或是欲前往的站點是否有位置可以停放等，這些問題也會影響民眾使用YouBike的意願。


&emsp;&emsp;而在這科技發展迅速、智慧型手機當道的時期，手機應用程式層出不窮，但多數民眾可能認為，為了一種服務而去下載一個新的應用程式有不少麻煩之處，尤其大多數的應用程式在使用前都需要先進行註冊，更降低了使用意願。但若是從幾乎人人都有的應用程式──LINE起步，使用LINE提供的聊天機器人服務「LINE Bot」，採用LINE Bot不須額外下載應用程式和註冊會員就能提供服務，民眾接受度相對提升。


&emsp;&emsp;綜合以上討論，為了讓民眾能多一個簡便的選擇，我們將路線規劃服務及YouBike站點即時資訊與LINE Bot作結合，希望提供一個民眾能容易使用的方式來進行服務。


## 二、系統功能簡介
&emsp;&emsp;在免下載應用程式的前提下，以LINE作為平台，讓使用者透過圖文選單點擊，即可規劃路線、查詢回饋金及優惠資訊。

* 規劃路線：輸入起點及終點後，系統將會根據所輸入資訊規劃最適合的交通工具及路線、顯示預計花費金額與時間，並附有到下車提醒通知。且提供YouBike站點資訊及腳踏車可用數量。

* 回饋即時報：提供使用者查看目前搭乘次數、消費金額、回饋級距與金額。


## 三、系統使用對象
&emsp;&emsp;大臺北地區捷運網路的使用者（無論是來旅遊的旅客或每日的通勤的民眾）：透過LINE加入官方帳號，即可規劃站內最短路徑及站外最佳路線與轉乘之捷運、公車或YouBike等資訊。

## 四、系統特色
  1. 路線導覽：針對目的地規劃出站內外最佳路徑，像是鄰近車廂、手扶梯或最合適的交通工具轉乘等。<br/>
  2. 免下載應用程式：有些人願意接受資訊，卻不願額外下載應用程式，因此我們選擇結合臺灣普遍使用的通訊軟體—LINE作為平台，去滿足這個需求。<br/>
  3. YouBike站點：根據所規劃的路線去搜尋鄰近的YouBike站點。<br/>


## 五、系統開發工具
| 開發輔助工具      |  |
| -               | -|
| 手機規格         | Visual Studio Code   |
| 資料庫管理工具    | phpMyAdmin           |
| 版本控制工具      | Git                  |
| API測試工具      | Postman              |
| API文件         |  |
| 文件製作         | Microsoft Word       |
| 簡報製作         | Microsoft PowerPoint |
| UML工具         |  Draw.io             |
| 介面設計工具      | Figma               |
| 雛型設計         | Figma                |
| 製圖工具         | Adobe Ai, Ps         |
| 專案管理工具      | Figma                |
| 溝通工具         | LINE、Telegram        |
| 版本控管         | Git                  |
| 進度追蹤         | Trello               |
| 影片軟體         | FinalCutPro          |
| 剪輯軟體         | FinalCutPro          |

## 六、系統使用環境
伺服器端：Ubuntu 20.04 <br/>
手機端：Android 4.1或以上、iOS 8.0或以上

## 七、結論及未來發展
&emsp;&emsp;MRTaipei｜台北先生希望能夠以最簡單且最實用的功能，結合臺灣普遍使用的通訊軟體LINE，讓來臺北旅遊的旅客或是每日的通勤的民眾都可以透過加入官方帳號使用相關服務，以更高效率抵達目的地，且透過到站提醒，以此降低乘客搭乘時的不安感。未來希望可以結合簡單的遺失物影像辨識系統快速辨識出物品的特徵，使登記流程更簡潔，幫助民眾更易找回所遺失的物品。

