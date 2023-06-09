## 期末報告
>
>組員學號：110111203、110111206、110111224
><br />
>組員姓名：吳冠德、陳彥錡、王先達

本份文件包含以下主題：
- [x] 簡易紀錄
- [x] 內容

## 簡易紀錄

顧客進來餐廳可選擇掃描qrcode選擇菜單，查看食物與飲料的選項，（瀏覽的菜單是由餐廳主管進行上架，並且主管可以對菜單進行新增、刪除、修改），選擇完想點的食物與飲料後，選擇所需數量，並記錄到購物車中，然後顧客進入購物車查看，確認所需的食物與飲料數量正確後（如有不正確可以新增、刪除、修改）選擇付款方式：（付現或者信用卡）並送出，送出後系統自動發放號碼牌，同時系統自動將顧客選擇的餐點傳送到廚房，廚師根據收到的點餐單進行烹飪且依照號碼牌順序完成出餐,則顧客在用完餐後依據號碼牌數字來進行結帳。

## 內容

利害人關係表

<table border="1 soild #fff">
    <tr>
        <td width="15%">利害關係人</td>
        <td>目標</td>
    </tr>
    <tr>
        <td width="15%">顧客</td>
        <td>進到餐廳掃描qrcode選擇菜單，查看食物與飲料的選項選擇食物與飲料的所需數量，並記錄到購物車查看購物車並確認所選的品項和數量是否正確，如有錯誤可以進行新增、刪除、修改選擇付款方式，並在用完餐後依據號碼牌數字來進行結帳</td>
    </tr>
    <tr>
        <td width="15%">餐廳主管</td>
        <td>可以從系統後台針對所有品項進行新增、刪除、修改</td>
    </tr>
    <tr>
        <td width="15%">廚師</td>
        <td>在顧客送出訂單並產生出後碼牌後，依據系統傳送到廚房的號碼牌順序來進行烹飪</td>
    </tr>
    <tr>
        <td width="15%">服務生</td>
        <td>在廚師烹飪完成後，依據訂單上的號碼牌順序進行出餐</td>
    </tr>
</table>

事件表

<table border="1 soild #fff">
    <tr>
        <td width="80%">事件</td>
        <td>使用案例</td>
    </tr>
    <tr>
        <td width="80%">進到餐廳掃描qrcode選擇菜單，查看食物與飲料的選項</td>
        <td>1.訂單案例</td>
    </tr>
    <tr>
        <td width="80%">可以從系統後台針對所有品項進行新增、刪除、修改</td>
        <td></td>
    </tr>
    <tr>
        <td width="80%">選擇食物與飲料的所需數量，並記錄到購物車</td>
        <td>2.購物車案例</td>
    </tr>
    <tr>
        <td width="80%">查看購物車並確認所選的品項和數量是否正確，如有錯誤可以進行新增、刪除、修改</td>
        <td></td>
    </tr>
    <tr>
        <td width="80%">選擇付款方式，並在用完餐後依據號碼牌數字來進行結帳</td>
        <td>3.付款案例</td>
    </tr>
    <tr>
        <td width="80%">在顧客送出訂單並產生出後碼牌後，依據系統傳送到廚房的號碼牌順序來進行烹飪</td>
        <td>4.號碼牌案例</td>
    </tr>
    <tr>
        <td width="80%">在廚師烹飪完成後，依據訂單上的號碼牌順序進行出餐</td>
        <td></td>
    </tr>
</table>

使用案例

<table border="1 soild #fff">
    <tr>
        <td width="20%">使用者案例名稱</td>
        <td>訂單案例</td>
    </tr>
    <tr>
        <td width="20%">使用者案例描述</td>
        <td>顧客進入餐廳後，掃描餐桌上的qrcode選擇菜單，查看由餐廳主管從系統後台上架的食物與飲料的選項，並且餐廳主管可從後台針對所有品項進行新增、刪除、修改</td>
    </tr>
    <tr>
        <td width="20%">主要參與者</td>
        <td>顧客、餐廳主管</td>
    </tr>
    <tr>
        <td width="20%">利害關係人與目標</td>
        <td>顧客：掃描餐桌上的qrcode選擇菜單，查看食物與飲料的選項<br>
            餐廳主管：可以從系統後台針對所有品項進行新增、刪除、修改
        </td>
    </tr>
    <tr>
        <td width="20%">前置條件</td>
        <td>1.系統管理者設定好系統並設定好餐廳主管帳號密碼，餐廳主管進行登入系統後<br>
            2.顧客用手機掃描餐桌上的qrcode後
        </td>
    </tr>
    <tr>
        <td width="20%">後置條件</td>
        <td>1.選擇食物與飲料選項<br>
            2.主管對所有品項進行新增、刪除、修改
        </td>
    </tr>
    <tr>
        <td width="20%">主要成功情節</td>
        <td>1.餐廳主管進行登入系統後，點選「品項」選項<br>
            2.點選「新增」，並上架品項<br>
            3.點選「完成」已完成新增<br>
            4.若輸入有錯誤要進行修改，於點選「編輯品項」後，將會於畫面產生所有目前已輸入的品項，請點選輸入錯誤的該筆資料，進入修改畫面<br>
            5.若要刪除單筆或多筆品項，則於該筆資料點選勾選框(可複選)，並再點選上方刪除鈕即可
        </td>
    </tr>
    <tr>
        <td width="20%">例外情節</td>
        <td>3a. 若新增失敗，將會有訊息視窗提示，並顯示失敗原因<br>
            5a. 若刪除失敗，將會有訊息視窗提示，並顯示失敗原因
        </td>
    </tr>
    <tr>
        <td width="20%">其他需求</td>
        <td>無</td>
    </tr>
</table>

<br>

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" width="503px" viewBox="-0.5 -0.5 503 701" content="&lt;mxfile&gt;&lt;diagram id=&quot;qECihoOcTkfPVkBHCYOp&quot; name=&quot;第1頁&quot;&gt;&lt;mxGraphModel dx=&quot;1329&quot; dy=&quot;631&quot; grid=&quot;1&quot; gridSize=&quot;10&quot; guides=&quot;1&quot; tooltips=&quot;1&quot; connect=&quot;1&quot; arrows=&quot;1&quot; fold=&quot;1&quot; page=&quot;1&quot; pageScale=&quot;1&quot; pageWidth=&quot;827&quot; pageHeight=&quot;1169&quot; math=&quot;0&quot; shadow=&quot;0&quot;&gt;&lt;root&gt;&lt;mxCell id=&quot;0&quot;/&gt;&lt;mxCell id=&quot;1&quot; parent=&quot;0&quot;/&gt;&lt;mxCell id=&quot;4&quot; value=&quot;&amp;lt;span style=&amp;quot;&amp;quot;&amp;gt;後臺系統&amp;lt;/span&amp;gt;&quot; style=&quot;html=1;align=center;verticalAlign=top;rounded=1;absoluteArcSize=1;arcSize=10;dashed=0;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;230&quot; y=&quot;470&quot; width=&quot;140&quot; height=&quot;250&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;6&quot; value=&quot;pos系統&quot; style=&quot;html=1;align=center;verticalAlign=top;rounded=1;absoluteArcSize=1;arcSize=10;dashed=0;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;230&quot; y=&quot;20&quot; width=&quot;140&quot; height=&quot;430&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;3&quot; value=&quot;&amp;lt;div style=&amp;quot;color: rgb(212, 212, 212); background-color: rgb(30, 30, 30); font-family: Consolas, &amp;amp;quot;Courier New&amp;amp;quot;, monospace; font-size: 14px; line-height: 19px;&amp;quot;&amp;gt;購物車案例&amp;lt;/div&amp;gt;&quot; style=&quot;ellipse;whiteSpace=wrap;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;240&quot; y=&quot;60&quot; width=&quot;120&quot; height=&quot;80&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;5&quot; value=&quot;waiter&quot; style=&quot;shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;80&quot; y=&quot;70&quot; width=&quot;30&quot; height=&quot;60&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;18&quot; style=&quot;edgeStyle=none;html=1;exitX=1;exitY=0.3333333333333333;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0;entryY=0.588;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;&quot; edge=&quot;1&quot; parent=&quot;1&quot; source=&quot;7&quot; target=&quot;14&quot;&gt;&lt;mxGeometry relative=&quot;1&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;7&quot; value=&quot;restaurant supervisor&quot; style=&quot;shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;80&quot; y=&quot;430&quot; width=&quot;30&quot; height=&quot;60&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;21&quot; style=&quot;edgeStyle=none;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;endArrow=none;endFill=0;exitX=0;exitY=0.3333333333333333;exitDx=0;exitDy=0;exitPerimeter=0;&quot; edge=&quot;1&quot; parent=&quot;1&quot; source=&quot;8&quot; target=&quot;3&quot;&gt;&lt;mxGeometry relative=&quot;1&quot; as=&quot;geometry&quot;&gt;&lt;mxPoint x=&quot;430&quot; y=&quot;190&quot; as=&quot;sourcePoint&quot;/&gt;&lt;/mxGeometry&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;22&quot; style=&quot;edgeStyle=none;html=1;exitX=0;exitY=0.3333333333333333;exitDx=0;exitDy=0;exitPerimeter=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;endArrow=none;endFill=0;&quot; edge=&quot;1&quot; parent=&quot;1&quot; source=&quot;8&quot; target=&quot;13&quot;&gt;&lt;mxGeometry relative=&quot;1&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;23&quot; style=&quot;edgeStyle=none;html=1;exitX=0;exitY=0.3333333333333333;exitDx=0;exitDy=0;exitPerimeter=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;endArrow=none;endFill=0;&quot; edge=&quot;1&quot; parent=&quot;1&quot; source=&quot;8&quot; target=&quot;19&quot;&gt;&lt;mxGeometry relative=&quot;1&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;30&quot; style=&quot;edgeStyle=none;html=1;exitX=0;exitY=0.3333333333333333;exitDx=0;exitDy=0;exitPerimeter=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;endArrow=none;endFill=0;&quot; edge=&quot;1&quot; parent=&quot;1&quot; source=&quot;8&quot; target=&quot;29&quot;&gt;&lt;mxGeometry relative=&quot;1&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;8&quot; value=&quot;Actor&quot; style=&quot;shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;510&quot; y=&quot;150&quot; width=&quot;30&quot; height=&quot;60&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;9&quot; value=&quot;chef&quot; style=&quot;shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;80&quot; y=&quot;230&quot; width=&quot;30&quot; height=&quot;60&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;20&quot; style=&quot;edgeStyle=none;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.3333333333333333;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;&quot; edge=&quot;1&quot; parent=&quot;1&quot; source=&quot;13&quot; target=&quot;7&quot;&gt;&lt;mxGeometry relative=&quot;1&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;13&quot; value=&quot;&amp;lt;div style=&amp;quot;color: rgb(212, 212, 212); background-color: rgb(30, 30, 30); font-family: Consolas, &amp;amp;quot;Courier New&amp;amp;quot;, monospace; font-size: 14px; line-height: 19px;&amp;quot;&amp;gt;付款案例&amp;lt;/div&amp;gt;&quot; style=&quot;ellipse;whiteSpace=wrap;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;240&quot; y=&quot;150&quot; width=&quot;120&quot; height=&quot;80&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;14&quot; value=&quot;訂單案例&quot; style=&quot;ellipse;whiteSpace=wrap;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;240&quot; y=&quot;510&quot; width=&quot;120&quot; height=&quot;80&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;24&quot; style=&quot;edgeStyle=none;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.3333333333333333;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;&quot; edge=&quot;1&quot; parent=&quot;1&quot; source=&quot;19&quot; target=&quot;5&quot;&gt;&lt;mxGeometry relative=&quot;1&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;25&quot; style=&quot;edgeStyle=none;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.3333333333333333;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;&quot; edge=&quot;1&quot; parent=&quot;1&quot; source=&quot;19&quot; target=&quot;9&quot;&gt;&lt;mxGeometry relative=&quot;1&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;19&quot; value=&quot;&amp;lt;div style=&amp;quot;color: rgb(212, 212, 212); background-color: rgb(30, 30, 30); font-family: Consolas, &amp;amp;quot;Courier New&amp;amp;quot;, monospace; font-size: 14px; line-height: 19px;&amp;quot;&amp;gt;&amp;lt;div style=&amp;quot;line-height: 19px;&amp;quot;&amp;gt;號碼牌案例&amp;lt;/div&amp;gt;&amp;lt;/div&amp;gt;&quot; style=&quot;ellipse;whiteSpace=wrap;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;240&quot; y=&quot;260&quot; width=&quot;120&quot; height=&quot;80&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=&quot;29&quot; value=&quot;訂單案例&quot; style=&quot;ellipse;whiteSpace=wrap;html=1;&quot; vertex=&quot;1&quot; parent=&quot;1&quot;&gt;&lt;mxGeometry x=&quot;240&quot; y=&quot;350&quot; width=&quot;120&quot; height=&quot;80&quot; as=&quot;geometry&quot;/&gt;&lt;/mxCell&gt;&lt;/root&gt;&lt;/mxGraphModel&gt;&lt;/diagram&gt;&lt;diagram id=&quot;82PADr6x4MjmLu8p6FVv&quot; name=&quot;第2頁&quot;&gt;&lt;mxGraphModel dx=&quot;1130&quot; dy=&quot;536&quot; grid=&quot;1&quot; gridSize=&quot;10&quot; guides=&quot;1&quot; tooltips=&quot;1&quot; connect=&quot;1&quot; arrows=&quot;1&quot; fold=&quot;1&quot; page=&quot;1&quot; pageScale=&quot;1&quot; pageWidth=&quot;827&quot; pageHeight=&quot;1169&quot; math=&quot;0&quot; shadow=&quot;0&quot;&gt;&lt;root&gt;&lt;mxCell id=&quot;0&quot;/&gt;&lt;mxCell id=&quot;1&quot; parent=&quot;0&quot;/&gt;&lt;/root&gt;&lt;/mxGraphModel&gt;&lt;/diagram&gt;&lt;/mxfile&gt;" onclick="(function(svg){var src=window.event.target||window.event.srcElement;while (src!=null&amp;&amp;src.nodeName.toLowerCase()!='a'){src=src.parentNode;}if(src==null){if(svg.wnd!=null&amp;&amp;!svg.wnd.closed){svg.wnd.focus();}else{var r=function(evt){if(evt.data=='ready'&amp;&amp;evt.source==svg.wnd){svg.wnd.postMessage(decodeURIComponent(svg.getAttribute('content')),'*');window.removeEventListener('message',r);}};window.addEventListener('message',r);svg.wnd=window.open('https://viewer.diagrams.net/?client=1&amp;page=0&amp;edit=_blank');}}})(this);" style="cursor:pointer;max-width:100%;max-height:701px;"><defs/><g><rect x="191" y="450" width="140" height="250" rx="5" ry="5" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 457px; margin-left: 261px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;"><span style="">後臺系統</span></div></div></div></foreignObject><text x="261" y="469" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">後臺系統</text></switch></g><rect x="191" y="0" width="140" height="430" rx="5" ry="5" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 7px; margin-left: 261px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">pos系統</div></div></div></foreignObject><text x="261" y="19" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">pos系統</text></switch></g><ellipse cx="261" cy="80" rx="60" ry="40" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 80px; margin-left: 202px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;"><div style="color: rgb(212, 212, 212); background-color: rgb(30, 30, 30); font-family: Consolas, &quot;Courier New&quot;, monospace; font-size: 14px; line-height: 19px;">購物車案例</div></div></div></div></foreignObject><text x="261" y="84" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">購物車案例</text></switch></g><ellipse cx="56" cy="57.5" rx="7.5" ry="7.5" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><path d="M 56 65 L 56 90 M 56 70 L 41 70 M 56 70 L 71 70 M 56 90 L 41 110 M 56 90 L 71 110" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 117px; margin-left: 56px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">waiter</div></div></div></foreignObject><text x="56" y="129" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">waiter</text></switch></g><path d="M 71 430 L 201 537.04" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><ellipse cx="56" cy="417.5" rx="7.5" ry="7.5" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><path d="M 56 425 L 56 450 M 56 430 L 41 430 M 56 430 L 71 430 M 56 450 L 41 470 M 56 450 L 71 470" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 477px; margin-left: 56px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">restaurant supervisor</div></div></div></foreignObject><text x="56" y="489" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">resta...</text></switch></g><path d="M 471 150 L 321 80" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 471 150 L 321 170" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 471 150 L 321 280" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 471 150 L 321 370" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><ellipse cx="486" cy="137.5" rx="7.5" ry="7.5" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><path d="M 486 145 L 486 170 M 486 150 L 471 150 M 486 150 L 501 150 M 486 170 L 471 190 M 486 170 L 501 190" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 197px; margin-left: 486px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">Actor</div></div></div></foreignObject><text x="486" y="209" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Actor</text></switch></g><ellipse cx="56" cy="217.5" rx="7.5" ry="7.5" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><path d="M 56 225 L 56 250 M 56 230 L 41 230 M 56 230 L 71 230 M 56 250 L 41 270 M 56 250 L 71 270" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 277px; margin-left: 56px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">chef</div></div></div></foreignObject><text x="56" y="289" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">chef</text></switch></g><path d="M 201 170 L 71 430" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><ellipse cx="261" cy="170" rx="60" ry="40" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 170px; margin-left: 202px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;"><div style="color: rgb(212, 212, 212); background-color: rgb(30, 30, 30); font-family: Consolas, &quot;Courier New&quot;, monospace; font-size: 14px; line-height: 19px;">付款案例</div></div></div></div></foreignObject><text x="261" y="174" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">付款案例</text></switch></g><ellipse cx="261" cy="530" rx="60" ry="40" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 530px; margin-left: 202px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">訂單案例</div></div></div></foreignObject><text x="261" y="534" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">訂單案例</text></switch></g><path d="M 201 280 L 71 70" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 201 280 L 71 230" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><ellipse cx="261" cy="280" rx="60" ry="40" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 280px; margin-left: 202px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;"><div style="color: rgb(212, 212, 212); background-color: rgb(30, 30, 30); font-family: Consolas, &quot;Courier New&quot;, monospace; font-size: 14px; line-height: 19px;"><div style="line-height: 19px;">號碼牌案例</div></div></div></div></div></foreignObject><text x="261" y="284" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">號碼牌案例</text></switch></g><ellipse cx="261" cy="370" rx="60" ry="40" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 370px; margin-left: 202px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">訂單案例</div></div></div></foreignObject><text x="261" y="374" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">訂單案例</text></switch></g></g><switch><g requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"/><a transform="translate(0,-5)" xlink:href="https://www.diagrams.net/doc/faq/svg-export-text-problems" target="_blank"><text text-anchor="middle" font-size="10px" x="50%" y="100%">Text is not SVG - cannot display</text></a></switch></svg>

<br>

<table border="1 soild #fff">
    <tr>
        <td width="20%">使用者案例名稱</td>
        <td>購物車案例</td>
    </tr>
    <tr>
        <td width="20%">使用者案例描述</td>
        <td>顧客選擇針對想要的食物與飲料進行點選，並選擇所需數量記錄到購物車中，選擇完畢後點選購物車，確認所選的品項與數量是否正確，如有錯誤可以進行新增、刪除、修
            改</td>
    </tr>
    <tr>
        <td width="20%">主要參與者</td>
        <td>顧客</td>
    </tr>
    <tr>
        <td width="20%">利害關係人與目標</td>
        <td>顧客：選擇食物與飲料的所需數量，並記錄到購物車，點選購物車並確認所選的品項和數量是否正確，如有錯誤可以進行新增、刪除、修
            改</td>
    </tr>
    <tr>
        <td width="20%">前置條件</td>
        <td>1.系統管理者設定好系統並設定好購物車<br>
            2.顧客用手機掃描餐桌上的qrcode後
        </td>
    </tr>
    <tr>
        <td width="20%">後置條件</td>
        <td>確認購物車中所選的品項和數量正確</td>
    </tr>
    <tr>
        <td width="20%">主要成功情節</td>
        <td>1.顧客用手機掃描餐桌上的qrcode後，點選「菜單」選項<br>
            2.點選「新增」，新增品項並選擇數量紀錄到購物車中<br>
            3.點選「購物車」，查看購物車並確認所選的品項和數量是否正確<br>
            4.點選「完成」已完成新增<br>
            5.若輸入有錯誤要進行修改，於點選「編輯菜單」後，將會於畫面產生所有目前已輸入的品項，請點選輸入錯誤的該筆資料，進入修改畫面<br>
            6.若要刪除單筆或多筆品項，則於該筆資料點選勾選框(可複選)，並再點選上方刪除鈕即可
        </td>
    </tr>
    <tr>
        <td width="20%">例外情節</td>
        <td>4a. 若新增失敗，將會有訊息視窗提示，並顯示失敗原因<br>
            6a. 若刪除失敗，將會有訊息視窗提示，並顯示失敗原因
        </td>
    </tr>
    <tr>
        <td width="20%">其他需求</td>
        <td>無</td>
    </tr>
</table>

<br>

<table border="1 soild #fff">
    <tr>
        <td width="20%">使用者案例名稱</td>
        <td>付款案例</td>
    </tr>
    <tr>
        <td width="20%">使用者案例描述</td>
        <td>顧客確認完購物車中品項及數量正確後按下送出，並可以選擇相應的付款方式(現金或信用卡)，並在用完餐後依據送出時產生的號碼牌數字到櫃檯跟餐廳主管進行結帳</td>
    </tr>
    <tr>
        <td width="20%">主要參與者</td>
        <td>顧客、餐廳主管</td>
    </tr>
    <tr>
        <td width="20%">利害關係人與目標</td>
        <td>顧客：選擇付款方式(現金或信用卡)<br>
            餐廳主管:依據送出時產生的號碼牌數字進行結帳</td>
    </tr>
    <tr>
        <td width="20%">前置條件</td>
        <td>1.系統管理者設定好系統並設定好付款(現金及信用卡)系統<br>
            2.系統管理者設定好系統並設定好號碼牌系統<br>
            3.顧客用手機掃描餐桌上的qrcode後<br>
            4.產生出號碼牌
        </td>
    </tr>
    <tr>
        <td width="20%">後置條件</td>
        <td>依據送出時產生的號碼牌數字來進行結帳</td>
    </tr>
    <tr>
        <td width="20%">主要成功情節</td>
        <td>1.點選「付款方式」，將會於畫面產生所有目前能使用的付款方式(現金或信用卡)<br>
            2.點選「現金」或「信用卡」已確認付款方式<br>
            3.點選「送出」將顧客填寫完的訂單送出<br>
            4.點選「產出號碼牌」已產出號碼牌數字<br>
            5.到櫃台出示號碼牌數字完成付款
        </td>
    </tr>
    <tr>
        <td width="20%">例外情節</td>
        <td>3a. 若送出失敗，將會有訊息視窗提示，並顯示失敗原因</td>
    </tr>
    <tr>
        <td width="20%">其他需求</td>
        <td>無</td>
    </tr>
</table>

<br>

<table border="1 soild #fff">
    <tr>
        <td width="20%">使用者案例名稱</td>
        <td>號碼牌案例</td>
    </tr>
    <tr>
        <td width="20%">使用者案例描述</td>
        <td>在顧客送出訂單並產生出號碼牌後，系統會自動把顧客送出的訂單傳送到廚房，廚師則依照號碼牌順序來進行烹飪</td>
    </tr>
    <tr>
        <td width="20%">主要參與者</td>
        <td>顧客、廚師</td>
    </tr>
    <tr>
        <td width="20%">利害關係人與目標</td>
        <td>顧客：送出訂單<br>
            廚師：依系統自動送出的訂單號碼順序來進行烹飪
        </td>
    </tr>
    <tr>
        <td width="20%">前置條件</td>
        <td>1.系統管理者設定好系統並設定好號碼牌系統<br>
            2.顧客用手機掃描餐桌上的qrcode後<br>
            3.顧客送出訂單並產生出號碼牌後
        </td>
    </tr>
    <tr>
        <td width="20%">後置條件</td>
        <td>系統自動把送出的訂單傳送到廚房</td>
    </tr>
    <tr>
        <td width="20%">主要成功情節</td>
        <td>1.點選「送出」將顧客填寫完的訂單送出<br>
            2.系統自動把顧客送出的訂單傳送到廚房<br>
            3.廚師點選「訂單」將會於畫面產生所有目前已送出的訂單<br>
            4.依訂單號碼順序來進行烹飪
        </td>
    </tr>
    <tr>
        <td width="20%">例外情節</td>
        <td>無</td>
    </tr>
    <tr>
        <td width="20%">其他需求</td>
        <td>無</td>
    </tr>
</table>

<br>

<table border="1 soild #fff">
    <tr>
        <td width="20%">使用者案例名稱</td>
        <td>出餐案例</td>
    </tr>
    <tr>
        <td width="20%">使用者案例描述</td>
        <td>在廚師烹飪完成後，服務生依據訂單上的號碼牌順序進行出餐 </td>
    </tr>
    <tr>
        <td width="20%">主要參與者</td>
        <td>廚師、服務生</td>
    </tr>
    <tr>
        <td width="20%">利害關係人與目標</td>
        <td>廚師：烹飪完成通知服務生送餐<br>
            服務生：收到通知後依據訂單上的號碼牌順序進行出餐
        </td>
    </tr>
    <tr>
        <td width="20%">前置條件</td>
        <td>1.系統管理者設定好系統並設定好出餐系統<br>
            2.廚師烹飪完成<br>
            3.服務生收到通知
        </td>
    </tr>
    <tr>
        <td width="20%">後置條件</td>
        <td>完成出餐</td>
    </tr>
    <tr>
        <td width="20%">主要成功情節</td>
        <td>1.廚師點選「送餐通知」將顧客填寫完的訂單送出<br>
            2.服務生收到通知，前往送餐檯<br>
            3.服務生點選「出餐」確認訂單的號碼牌順序<br>
            4.完成出餐
        </td>
    </tr>
    <tr>
        <td width="20%">例外情節</td>
        <td>無</td>
    </tr>
    <tr>
        <td width="20%">其他需求</td>
        <td>無</td>
    </tr>
</table>

