
<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para Mary ❤️</title>

<style>
* { box-sizing: border-box; }

body {
  margin: 0;
  font-family: Georgia, serif;
  color: #fff0f3;
  text-align: center;
  background: linear-gradient(160deg, #10070c, #350d1d, #10070c);
}

header { padding: 28px 15px; }

h1 {
  color: #ff7898;
  font-size: clamp(42px, 10vw, 65px);
  margin-bottom: 8px;
}

h2 { color: #ff9ab0; }

p {
  line-height: 1.8;
  font-size: 17px;
}

section {
  padding: 30px 20px;
  max-width: 760px;
  margin: auto;
}

.card {
  border: 1px solid #a83c5b;
  border-radius: 18px;
  padding: 24px;
  margin: 20px auto;
  background: rgba(255,255,255,0.04);
}

.heart {
  font-size: 42px;
  animation: pulse 1.5s infinite;
}

button {
  background: #e94c75;
  color: white;
  border: none;
  border-radius: 30px;
  padding: 15px 24px;
  font-size: 16px;
  cursor: pointer;
  margin: 12px 5px;
}

button:hover { background: #ff7898; }

#carta {
  display: none;
  text-align: left;
  white-space: pre-line;
  animation: aparecer 1s ease;
}

footer {
  padding: 30px 15px;
  color: #ff9ab0;
}

@keyframes pulse {
  50% { transform: scale(1.15); }
}

@keyframes aparecer {
  from { opacity: 0; transform: translateY(15px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>
</head>

<body>

<header>
  <div class="heart">❤️</div>
  <h1>Mary...</h1>
  <h2>Perdoa-me, por favor.</h2>
  <p>
    Há palavras que às vezes não conseguem explicar
    tudo aquilo que sentimos. Mas hoje quero tentar.
  </p>
</header>

<section>
  <div class="card">
    <h2>Uma coisa que quero que saibas 💗</h2>
    <p>
      Mary, eu amo-te e a tua presença é muito importante
      para mim. O teu jeito, o teu sorriso e as nossas
      conversas têm um lugar especial no meu coração.
    </p>
    <p>
      Se te magoei, se falhei contigo ou se fiz alguma
      coisa que te deixou triste, peço-te desculpa.
      Não quero fingir que sou perfeito. Quero aprender
      com os meus erros e demonstrar isso com atitudes.
    </p>
  </div>

  <div class="card">
    <h2>O teu valor na minha vida 🌹</h2>
    <p>
      A tua presença faz diferença. Gosto de ter-te na
      minha vida e valorizo muito a pessoa que és.
      Não quero que penses que és indiferente para mim,
      porque não és.
    </p>
    <p>
      Não te escrevo para te pressionar, mas para ser
      sincero contigo. O que sinto por ti é importante
      para mim, e quero tratar os teus sentimentos
      com carinho e respeito.
    </p>
  </div>

  <div class="card">
    <h2>Tenho uma surpresa para ti 💌</h2>
    <p>
      Preparei uma pequena carta. Carrega no botão
      abaixo para a abrires.
    </p>

    <button onclick="abrirCarta()">
      Abrir a minha carta ❤️
    </button>

    <div id="carta">
Mary, ❤️

Se eu pudesse transformar os meus sentimentos em
palavras perfeitas, talvez ainda assim não conseguisse
explicar tudo o que significas para mim.

Quero pedir-te desculpa de coração. Sei que amar
alguém também significa reconhecer os próprios erros,
saber ouvir e procurar fazer melhor.

A tua presença é importante para mim. Não és apenas
mais uma pessoa na minha vida. És alguém por quem
tenho um carinho profundo, alguém cuja presença
valorizo e cuja felicidade também me importa.

Eu amo-te, Mary. E não quero que estas palavras sejam
apenas bonitas: quero que as minhas atitudes mostrem
respeito, cuidado e sinceridade.

Não precisas de responder imediatamente nem de
perdoar-me por obrigação. Quero respeitar o teu tempo
e os teus sentimentos.

Obrigado por seres quem és e por fazeres parte da
minha vida.

Com carinho e todo o meu coração,

Felizandro ❤️
    </div>
  </div>

  <p style="font-style:italic; color:#ff9ab0;">
    "Acima de tudo, porém, revistam-se do amor,
    que é o elo perfeito."
  </p>
  <p>Colossenses 3:14 📖</p>

  <div class="heart">❤️</div>
  <h2>Com carinho, Felizandro</h2>
</section>

<footer>
  Feito com carinho, especialmente para Mary. 🌹
</footer>

<script>
function abrirCarta() {
  const carta = document.getElementById("carta");

  if (carta.style.display === "block") {
    carta.style.display = "none";
  } else {
    carta.style.display = "block";
    carta.scrollIntoView({
      behavior: "smooth",
      block: "center"
    });
  }
}
</script>

</body>
</html>
