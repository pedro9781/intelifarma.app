<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>IA Pedro</title>
<style>
    /* ... (mantém todo o CSS do seu arquivo original) ... */
</style>
</head>
<body>
<div class="face-container" id="faceBox" onclick="ativarIA()">
    <div id="textoResposta"></div>
    <img id="imagemResposta">
 <svg viewBox="0 0 200 200" id="face">
    <g transform="translate(100,100)">
        <circle cx="0" cy="0" r="78" fill="none" stroke="#FFFFFF" stroke-width="2"/>
        <g stroke="#E0E0E0" stroke-width="1" opacity="0.5"> 
            <ellipse rx="78" ry="20" fill="none"/>
            <ellipse rx="78" ry="35" fill="none"/>
            <ellipse rx="78" ry="50" fill="none"/>
            <ellipse rx="78" ry="65" fill="none"/>
            <line x1="-78" y1="0" x2="78" y2="0"/>
        </g>
        <ellipse id="eyeL" class="eye" cx="-28" cy="-20" rx="10" ry="8" fill="#FFFFFF"/>
        <ellipse id="eyeR" class="eye" cx="28" cy="-20" rx="10" ry="8" fill="#FFFFFF"/>
        <g id="mouth" transform="translate(0,35)">
            <rect x="-25" y="-5" width="50" height="12" rx="6" fill="#FFFFFF"/>
        </g>
    </g>
</svg>
</div>
<script>
    // ... (todo o JS igual ao seu arquivo original) ...
</script>
</body>
</html>
