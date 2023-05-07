<!DOCTYPE html>
<html>
<head>
  <title>Perfil Personalizado</title>
  <style>
    @keyframes fadeOut {
      0% { opacity: 1; }
      100% { opacity: 0; }
    }
    #text {
      animation: fadeOut 3s ease-in-out;
    }
  </style>
</head>
<body>
  <h1 id="text">Texto que desaparece en segundos</h1>

  <script>
    setTimeout(function() {
      document.getElementById("text").style.display = "none";
    }, 3000); // Desaparece después de 3 segundos (3000 ms)
  </script>
</body>
</html>




<!--
**RDO-MC/RDO-MC** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
