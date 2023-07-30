# live2d

Paste Jquery dan jQueryUI CDN di atas /head>
Apabila sudah ada Abaikan
```
<link href='https://cdn.statically.io/gh/wernayasa/live2d/main/assets/waifu.min.css' rel='stylesheet' type='text/css'/>
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
<script src='https://cdn.statically.io/gh/wernayasa/live2d/main/assets/waifu-tips.min.js'/>
<script src='https://cdn.statically.io/gh/wernayasa/live2d/main/assets/live2d.min.js'/>
```
Paste di atas /body> <br/>
Posisi dan ukuran bisa di configurasi lebih lanjut.<br/>
Bagian waifu-tips.json wajib di ubah karena masih bahasa jepang. Untuk ini wajib pakai Github Sendiri.
Convert linknya menggunakan: https://statically.io/convert/
```
<script type='text/javascript'>
    /* Konfigurasi */
    live2d_settings[&#39;waifuSize&#39;]            = &#39;280x250&#39;;    // 看板娘大小&#65292;例如 &#39;280x250&#39;, &#39;600x535&#39;
    live2d_settings[&#39;waifuTipsSize&#39;]        = &#39;250x70&#39;;     // 提示框大小&#65292;例如 &#39;250x70&#39;, &#39;570x150&#39;
    live2d_settings[&#39;waifuFontSize&#39;]        = &#39;12px&#39;;       // 提示框字体&#65292;例如 &#39;12px&#39;, &#39;30px&#39;
    live2d_settings[&#39;waifuToolFont&#39;]        = &#39;14px&#39;;       // 工具栏字体&#65292;例如 &#39;14px&#39;, &#39;36px&#39;
    live2d_settings[&#39;waifuToolLine&#39;]        = &#39;20px&#39;;       // 工具栏行高&#65292;例如 &#39;20px&#39;, &#39;36px&#39;
    live2d_settings[&#39;waifuToolTop&#39;]         = &#39;0px&#39;         // 工具栏顶部边距&#65292;例如 &#39;0px&#39;, &#39;-60px&#39;
    live2d_settings[&#39;waifuMinWidth&#39;]        = &#39;768px&#39;;      // 面页小于 指定宽度 隐藏看板娘&#65292;例如 &#39;disable&#39;(禁用), &#39;768px&#39;
    live2d_settings[&#39;waifuEdgeSide&#39;]        = &#39;right:30&#39;;     // 看板娘贴边方向&#65292;例如 &#39;left:0&#39;(靠左 0px), &#39;right:30&#39;(靠右 30px)
    live2d_settings[&#39;waifuDraggable&#39;]       = &#39;true&#39;;    // 拖拽样式&#65292;例如 &#39;disable&#39;(禁用), &#39;axis-x&#39;(只能水平拖拽), &#39;unlimited&#39;(自由拖拽)
    live2d_settings[&#39;waifuDraggableRevert&#39;] = false;         // 松开鼠标还原拖拽位置&#65292;可选 true(真), false(假)
    /* 在 initModel 前添加 */
    initModel(&quot;https://cdn.statically.io/gh/wernayasa/live2d/main/assets/waifu-tips.json&quot;)
  </script>
```
