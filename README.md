<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link rel="stylesheet" href="assets/style.css" />
</head>
<body>
  <h1>Flashcards de Português</h1>
  <div class="container">

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          O que é um verbo?
        </div>
        <div class="card-back">
          Palavra que indica ação, estado ou fenômeno da natureza.
        </div>
      </div>
    </div>

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          O que é um adjetivo?
        </div>
        <div class="card-back">
          É a palavra que caracteriza o substantivo.
        </div>
      </div>
    </div>

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          O que é sujeito?
        </div>
        <div class="card-back">
          É o termo da oração que indica quem pratica ou sofre a ação.
        </div>
      </div>
    </div>

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          O que é predicado?
        </div>
        <div class="card-back">
          É tudo que se declara sobre o sujeito.
        </div>
      </div>
    </div>

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          Quem foi Machado de Assis?
        </div>
        <div class="card-back">
          Um dos maiores escritores brasileiros, autor de "Dom Casmurro".
        </div>
      </div>
    </div>

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          O que é uma metáfora?
        </div>
        <div class="card-back">
          Figura de linguagem que compara dois elementos sem “como”.
        </div>
      </div>
    </div>

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          Qual a função do ponto final?
        </div>
        <div class="card-back">
          Indicar o fim de uma frase declarativa.
        </div>
      </div>
    </div>

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          O que é um pronome?
        </div>
        <div class="card-back">
          Palavra que substitui ou acompanha o substantivo.
        </div>
      </div>
    </div>

    <div class="flashcard">
      <div class="card-inner">
        <div class="card-front">
          <span class="tag-topo">Português</span>
          O que é coesão textual?
        </div>
        <div class="card-back">
          Ligação harmônica entre as partes de um texto.
        </div>
      </div>
    </div>

  </div>

  <script>
    document.querySelectorAll('.flashcard').forEach(card => {
      card.addEventListener('click', () => {
        card.classList.toggle('ativo');
      });
    });
  </script>
</body>
</html>
<!-- Rodapé com nomes -->
<footer>
  <div class="nomes-finais">
    Alana C. Queiroz, Emily K. Gomes, Kethlyn S. De Paiva – 2ºJ
  </div>
  <div class="creditos">
    Desenvolvido por Alura. Projeto fictício sem fins comerciais.
  </div>
</footer>
