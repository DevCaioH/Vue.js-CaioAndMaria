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
        data-bs-toggle="collapse"
        data-bs-target="#multiCollapseExample2"
        aria-expanded="false"
        aria-controls="multiCollapseExample2"
      >
        O Pedido
      </button>
      <button
        @click="showCard('button3')"
        class="btn btn-outline-dark selection boldAndColor selectionHover"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target=".multi-collapse"
        aria-expanded="false"
        aria-controls="multiCollapseExample1 multiCollapseExample2"
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
                src="../assets/IMG_3332.jpg"
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
      </div>

      <iframe 
        v-if="expand"
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
import AlertComponent from "./Alert.vue";
export default {
  name: "Info-Container",
  componets: { AlertComponent },
  data: function () {
    return {
      expand: false,
      activeButton: null,
     
    };
  },
  methods: {
    showCard(divId) {
      if (this.activeButton === divId) {
        this.expand = false;
        this.activeButton = null;
      } else {
        
        this.expand = true;
        this.activeButton = divId;
      }
    },
  },
};
</script>

