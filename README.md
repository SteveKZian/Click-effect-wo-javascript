# Click-effect-wo-javascript
# How to click elements (in HTML) without javascript
<html><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8"> 
<title> Maskit.de </title> 
<style> 
details { 
    position:absolute; ;
    padding: 1px;
    width: 70px;
}
details > div { 
    position:absolute; 
    overflow:hidden;
    background-size: 100% 100%;
    }
</style>
</head>

<body> 
    <details id="d" style="left: 100px; top: 100px;" open="">
        <div id="q" style="width: 200px; height: 200px; 
        background-image: 
        url(&quot;http://logolinz.de/itask/galerie/g/g%20(1).jpg&quot;)">
        some Text</div>
    </details>
</body>
</html>
