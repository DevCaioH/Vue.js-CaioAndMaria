<template>
  <div class="container-fluid p-3 mb-5">
    <h1 class="display-4">Lembranças que aquecem o coração!</h1>
    <hr />

    <div class="card-photos d-flex justify-content-around flex-wrap">
      <div class="card">
        <img
          class="card-img-top"
          src="../assets/CDF17380-6C39-48FD-97F5-BECBB41F5FD9.jpg"
          alt="Imagem de capa do card"
        />
      </div>
      <div class="card">
        <img
          class="card-img-top"
          src="../assets/IMG_6431.jpg"
          alt="Imagem de capa do card"
        />
      </div>
      <div class="card">
        <img
          class="card-img-top"
          src="../assets/IMG_6438.jpg"
          alt="Imagem de capa do card"
        />
      </div>
    </div>
    <hr />

    <p class="selection">
      <button
        @click="showCard('button1')"
        class="btn btn-outline-dark selection boldAndColor selectionHover"
        type="button"
        name="button1"
        data-bs-toggle="collapse"
        href="#multiCollapseExample1"
        role="button"
        aria-expanded="false"
        aria-controls="multiCollapseExample1"
      >
        Como tudo começou
      </button>
      <button
        @click="showCard('button2')"
        class="btn btn-outline-dark selection boldAndColor selectionHover"
        type="button"
        name="button2"
        data-bs-toggle="collapse"
        data-bs-target="#multiCollapseExample2"
        aria-expanded="false"
        aria-controls="multiCollapseExample2"
      >
        O Pedido
      </button>
      <button
        @click="showCard('button3')"
        class="btn btn-outline-dark selection boldAndColor selectionHover activate"
        type="button"
        name="button3"
        data-bs-toggle="collapse"
        data-bs-target="#multiCollapseExample3"
        aria-expanded="false"
        aria-controls="multiCollapseExample3"
      >
        O Noivado
      </button>
    </p>

    <div class="row">
      <div class="col">
        <div class="collapse multi-collapse" id="multiCollapseExample1">
          <div v-if="activeButton == 'button1'" class="card card-body beggin">
            <div class="media">
              <img
                src="../assets/IMG_3332.jpg"
                class="figure-img img-fluid rounded"
                alt="Imagem de um quadrado genérico com bordas arredondadas, em uma figure."
              />
              <div class="media-body">
                <h5 class="mt-6">Nosso começo</h5>
                <p class="mb-0">
                  Nos conhecemos de uma forma inesperada, virtualmente, onde
                  nossas conversas começaram despretensiosas, mas a cada
                  palavra, a cada troca de mensagens, eu sentia algo crescer
                  dentro de mim. Era uma conexão inexplicável, algo que
                  transcende o espaço e o tempo, como se nossos destinos já
                  estivessem entrelaçados muito antes de nos encontrarmos.
                </p>
                <br />
                <p class="mb-0">
                  Quando finalmente marcamos de nos ver, eu estava tomado por
                  uma mistura de excitação e nervosismo. Lembro claramente do
                  momento em que saí para te encontrar. Meu coração estava
                  acelerado, minhas mãos suavam, e meus pensamentos não paravam
                  de imaginar como seria te ver pela primeira vez. Eu sabia que
                  aquele dia mudaria minha vida para sempre.
                </p>
                <br />
                <p class="mb-0">
                  O instante em que te vi, ali, à minha frente, foi como se o
                  tempo tivesse parado. Tudo ao redor ficou em silêncio, e só
                  existia você. O sorriso que você me deu, a forma como me
                  olhou, fez o mundo inteiro desaparecer. Eu sentia cada batida
                  do meu coração ecoando no peito, e aquele nervosismo, que
                  antes era quase insuportável, se transformou em uma certeza
                  tranquila: eu estava onde deveria estar, com a pessoa que eu
                  sempre procurei.
                </p>
                <br />
                <p class="mb-0">
                  Eu ainda me lembro de cada detalhe daquele encontro. A
                  sensação de caminhar ao seu lado, de ouvir sua voz ao vivo
                  pela primeira vez, de ver o brilho dos seus olhos de perto.
                  Era como se todas as peças do quebra-cabeça da minha vida
                  tivessem finalmente se encaixado. Tudo fazia sentido.
                </p>
                <br />
                <p class="mb-0">
                  Você transformou o melhor dia da minha vida em um marco, o
                  ponto de partida de uma jornada incrível que estamos trilhando
                  juntos. A partir daquele momento, eu sabia que meu lugar era
                  ao seu lado. Cada dia desde então tem sido uma nova página de
                  uma história que eu mal posso esperar para continuar
                  escrevendo com você.
                </p>
                <br />
                <p class="mb-0">
                  Ainda hoje, quando penso naquele dia, sinto as mesmas emoções
                  invadirem meu coração. O frio na barriga, o nervosismo, mas,
                  acima de tudo, a felicidade de ter te encontrado. Você é a
                  pessoa que me completa, e tudo começou naquele primeiro
                  encontro que nunca vou esquecer. Te amo mais a cada dia, e
                  estou ansioso para viver muitos outros momentos inesquecíveis
                  ao seu lado.
                </p>
                <br />
              </div>
            </div>
          </div>
        </div>

        <div class="collapse multi-collapse" id="multiCollapseExample2">
          <div v-if="activeButton == 'button2'" class="card card-body beggin">
            <div class="media">
              <img
                src="../assets/IMG_3898.png"
                class="figure-img img-fluid rounded"
                alt="Imagem de um quadrado genérico com bordas arredondadas, em uma figure."
              />
              <div class="media-body">
                <h5 class="mt-6">O Pedido 💍</h5>
                <p class="mb-0">
                  Eu queria mostrar ao mundo tudo o que sinto por você, e para
                  isso, decidi te pedir em namoro. A ideia de dar esse passo me
                  deixava nervoso, especialmente porque eu sabia que teria que
                  conversar com seus pais. A expectativa misturada com a
                  ansiedade tornava tudo ainda mais intenso.
                </p>
                <br />

                <p class="mb-0">
                  A verdade é que eu já não sabia mais como viver sem você. A
                  cada dia que passava, sentia sua falta de uma maneira que ia
                  além do físico. A falta do seu sorriso iluminando meu dia e
                  dos seus abraços calorosos, que me faziam sentir completo,
                  tornava-se insuportável.
                </p>
                <br />

                <p class="mb-0">
                  Foi então que, naquele dia, fiz a melhor escolha da minha
                  vida! Com o coração acelerado e a mente cheia de pensamentos,
                  eu te pedi em namoro. Ali, naquele momento especial, demos o
                  pontapé inicial para o nosso relacionamento. A sensação de ter
                  tomado essa decisão foi como uma onda de alívio e felicidade,
                  pois sabia que havia encontrado alguém verdadeiramente
                  especial.
                </p>
                <br />

                <p class="mb-0">
                  A partir daquele instante, tudo mudou. Cada conversa, cada
                  olhar trocado, cada momento juntos se tornou ainda mais
                  significativo. Sabia que estávamos começando algo belo, e o
                  futuro parecia promissor. Ao te pedir em namoro, não apenas
                  declarei meu amor, mas também abri as portas para um mundo
                  novo, repleto de sonhos, risadas e aventuras que estávamos
                  prestes a viver juntos
                </p>
                <br />
              </div>
            </div>
          </div>
        </div>

        <div class="collapse multi-collapse" id="multiCollapseExample3">
          <div v-if="activeButton == 'button3'" class="card card-body beggin">
            <div class="media">
              <img
                src="../assets/IMG_6438.jpg"
                class="figure-img img-fluid rounded"
                alt="Imagem de um quadrado genérico com bordas arredondadas, em uma figure."
              />
              <div class="media-body">
                <h5 class="mt-6">O Noivado</h5>
                <p class="mb-0">
                  Sabe, conforme os dias foram se passando, eu fui me
                  apaixonando cada vez mais por você, como se cada risada, cada
                  olhar e cada conversa nossa fossem as peças de um
                  quebra-cabeça que, aos poucos, foram se encaixando. Cada
                  momento que passamos juntos foi como uma nova página no nosso
                  livro de amor, e a história que estamos escrevendo é
                  simplesmente incrível.
                </p>
                <br />
                <p class="mb-0">
                  A gente enfrentou altos e baixos, e mesmo nas brigas e
                  discussões que tivemos, nunca deixamos que nada nos separasse.
                  Na verdade, eu sinto que cada desafio que apareceu no nosso
                  caminho só serviu para nos unir ainda mais. Nós somos como
                  dois guerrilheiros lutando juntos, construindo um amor que é
                  mais forte a cada dia. Lembro de momentos em que pensei que
                  poderíamos desmoronar, mas aí você olhava nos meus olhos e
                  tudo voltava a fazer sentido. Você é a razão pela qual eu
                  sempre quero lutar e construir algo lindo.
                </p>
                <br />
                <p class="mb-0">
                  E aí, depois de dois anos vivendo essa aventura juntos, eu
                  decidi fazer algo que talvez você não esperasse, mas que no
                  fundo, eu sabia que era o próximo passo: pedi você em
                  casamento! Te ver surpresa naquele momento foi simplesmente
                  mágico. A sua reação foi como um sonho se tornando realidade,
                  e, sem dúvida, foi a segunda melhor escolha da minha vida. A
                  primeira? Ah, isso é fácil: foi ter te pedido em namoro. Cada
                  segundo ao seu lado é um tesouro que guardo com carinho, e eu
                  nunca quero perder isso.
                </p>
                <br />
                <p class="mb-0">
                  Que venham mais dias incríveis ao seu lado! Quero que a gente
                  continue a nos amar, a rir até doer a barriga e a enfrentar
                  tudo junto. Você é o meu porto seguro, e não importa o que
                  aconteça, eu sempre vou estar ao seu lado, segurando a sua mão
                  e te apoiando em cada passo dessa jornada.
                </p>
                <br />
                <p class="mb-0">
                  Prometo que estarei aqui, sempre pronto para te abraçar e
                  fazer você se sentir a pessoa mais especial do mundo, porque é
                  exatamente isso que você é para mim. Juntos, podemos criar uma
                  vida cheia de sonhos, aventuras e, acima de tudo, muito amor.
                  Você é a minha inspiração, e mal posso esperar para viver tudo
                  isso com você, eternamente. Te amo mais do que palavras podem
                  expressar, e estou animado para cada capítulo que ainda vamos
                  escrever juntos!
                </p>

                <br />
              </div>
            </div>
          </div>
        </div>
      </div>

      <iframe
        v-if="activeButton"
        class="spotify"
        style="border-radius: 12px"
        src="https://open.spotify.com/embed/playlist/5lmofNsZx7x0WhLdJe2w6j?utm_source=generator&theme=0"
        frameborder="0"
        allowfullscreen
        allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
        loading="lazy"
      ></iframe>
    </div>
  </div>
</template>

<script>
export default {
  name: "Info-Container",
  data: function () {
    return {
      activeButton: null,
    };
  },
  methods: {
    showCard(divId) {
      if (this.activeButton === divId) {
        const elements = document.getElementsByName(divId);
        for (let e of elements) {
          e.classList.remove("btn-color-change");
          e.classList.add("btn-outline-dark");
        }

        this.activeButton = null;
      } else {
        const elements = document.getElementsByName(divId);
        for (let e of elements) {
          e.classList.remove("btn-outline-dark");
          e.classList.add("btn-color-change");
        }
        this.activeButton = divId;
      }
    },
  },
};
</script>

<style>
</style>