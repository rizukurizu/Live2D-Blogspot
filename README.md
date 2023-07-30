# live2d

Paste Jquery dan jQueryUI CDN di atas /head>
Apabila sudah ada Abaikan
```
<script crossorigin='anonymous' integrity='sha256-2Pmvv0kuTBOenSvLm6bvfBSSHrUJ+3A7x6P5Ebd07/g=' src='https://code.jquery.com/jquery-3.7.0.min.js'/>
<script crossorigin='anonymous' integrity='sha256-eTyxS0rkjpLEo16uXTS0uVCS4815lc40K2iVpWDvdSY=' src='https://code.jquery.com/ui/1.13.1/jquery-ui.min.js'/>
```
Paste HTML di atas /body
```
<div class='waifu'>
        <div class='waifu-tips'/>
        <canvas class='live2d' id='live2d'/>
        <div class='waifu-tool'>
            <span class='fui-home'/>
            <span class='fui-chat'/>
            <span class='fui-eye'/>
            <span class='fui-user'/>
            <span class='fui-photo'/>
            <span class='fui-info-circle'/>
            <span class='fui-cross'/>
        </div>
    </div>
```
Paste di atas /body>
Buat halaman github sendiri apabila ingin kostumisasi lebih lanjut.
```
<script src='https://cdn.statically.io/gh/wernayasa/live2d/main/assets/waifu-tips.min.js'/>
<script src='https://cdn.statically.io/gh/wernayasa/live2d/main/assets/live2d.min.js'/>
<script type='text/javascript'>
        /* 可直接修改部分参数 */
        live2d_settings[&#39;modelId&#39;] = 1;                  // 默认模型 ID
        live2d_settings[&#39;modelTexturesId&#39;] = 87;         // 默认材质 ID
        live2d_settings[&#39;modelStorage&#39;] = false;         // 不储存模型 ID
        live2d_settings[&#39;canCloseLive2d&#39;] = false;       // 隐藏 关闭看板娘 按钮
        live2d_settings[&#39;canTurnToHomePage&#39;] = false;    // 隐藏 返回首页 按钮
        live2d_settings[&#39;waifuSize&#39;] = &#39;600x535&#39;;        // 看板娘大小
        live2d_settings[&#39;waifuTipsSize&#39;] = &#39;570x150&#39;;    // 提示框大小
        live2d_settings[&#39;waifuFontSize&#39;] = &#39;30px&#39;;       // 提示框字体
        live2d_settings[&#39;waifuToolFont&#39;] = &#39;36px&#39;;       // 工具栏字体
        live2d_settings[&#39;waifuToolLine&#39;] = &#39;50px&#39;;       // 工具栏行高
        live2d_settings[&#39;waifuToolTop&#39;] = &#39;-60px&#39;;       // 工具栏顶部边距
        live2d_settings[&#39;waifuDraggable&#39;] = &#39;axis-x&#39;;    // 拖拽样式
        /* 在 initModel 前添加 */
        initModel(&quot;https://cdn.statically.io/gh/wernayasa/live2d/main/assets/waifu-tips.json&quot;)
    </script>
```
