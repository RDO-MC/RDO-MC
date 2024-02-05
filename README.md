<!DOCTYPE html>
<html>
<head>
    <style>
        /* Estilo de letra tipo hacker */
        @font-face {
            font-family: hackerFont;
            src: url("ruta_de_tu_fuente.ttf"); /* Reemplaza 'ruta_de_tu_fuente.ttf' con la ruta real de tu fuente */
        }
        #myName {
            font-family: hackerFont, monospace; /* Utiliza la fuente hackerFont y respalda con una fuente monoespaciada */
        }
    </style>
</head>
<body>
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 510 40" style="background-color: #00000000;" width="510px" height="40px">
        <path id="path0">
            <!-- Single line -->
            <animate id="d0" attributeName="d" begin="0s;d0.end" dur="8000ms" fill="remove" values="m0,20 h0 ; m0,20 h510 ; m0,20 h510 ; m0,20 h0" keyTimes="0;0.7;0.825;1"/>
        </path>
        <text font-family="&quot;Iosevka&quot;, monospace" fill="#6791c9" font-size="21" dominant-baseline="auto" x="0%" text-anchor="start">
            <textPath xlink:href="#path0">
                Hi, I'm 
                <tspan fill="#ff0000" dy="-20" id="typedText">Rivaldo David (RDO-MC)</tspan>
                <animate attributeName="startOffset" from="0%" to="100%" dur="5s" repeatCount="indefinite" />
            </textPath>
        </text>
    </svg>

    <!-- Contenido de tu README -->
    <div class="github-readme">
        <p align="left"> <img src="https://komarev.com/ghpvc/?username=rdo-mc&label=Profile%20views&color=0e75b6&style=flat" alt="rdo-mc" /> </p>

        <p align="center"><img src="https://komarev.com/ghpvc/?username=rdo-mc&label=Profile%20views&color=0e75b6&style=flat" alt="rdo-mc" /></p>

        - 🌱 I’m currently learning **Node js**

        <p align="left"></p>
        <p align="center">
        </p>

        <h3 align="center">Languages and Tools:</h3>

        <p align="center">
          <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a>
          <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
          <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a>
          <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
        </p>

        <h3 align="left">Languages and Tools:</h3>
        <p align="left"> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>
        <p align="center"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=rdo-mc&show_icons=true&locale=en&layout=compact" alt="rdo-mc" /></p>

        <p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=rdo-mc&show_icons=true&locale=en&layout=compact" alt="rdo-mc" /></p>
        <p align="center">&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=rdo-mc&show_icons=true&locale=en" alt="rdo-mc" /></p>

        <p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=rdo-mc&show_icons=true&locale=en" alt="rdo-mc" /></p>
        <p align="center"><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=rdo-mc&" alt="rdo-mc" /></p>

        <p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=rdo-mc&" alt="rdo-mc" /></p>
    </div>

    <script>
        var txt = "Hi, I'm Rivaldo David (RDO-MC)"; /* El texto que quieres que se escriba */
        var speed = 100; /* La velocidad/duración de la efecto en milisegundos */
        var i = 0;
        var textNode = document.getElementById('typedText');
        
        function typeWriter() {
            if (i < txt.length) {
                textNode.textContent += txt.charAt(i);
                i++;
                setTimeout(typeWriter, speed);
            } else {
                // Si se completa la escritura, reinicia el efecto
                i = 0;
                textNode.textContent = "Rivaldo David (RDO-MC)";
                setTimeout(typeWriter, speed); // Vuelve a iniciar la escritura
            }
        }
        
        typeWriter();
    </script>
</body>
</html>
