---
theme: default
background: hero.png
class: 'text-center'
info: |
  # WebContainer
  como o StackBlitz transformou o desenvolvimento web com Node.js no navegador

  Apresentação no TDC 2023 sobre Node, StackBlitz e WebContainer
drawings:
  persist: false
css: unocss
title: 
  "WebContainer: como o StackBlitz transformou o desenvolvimento web com Node.js no navegador"
titleTemplate: '%s - Gabriel Daltoso (@ggdaltoso)'
---

<br >
<br >
<br >
<br >
<br >
<br >
<br >
<br >
<br >
<br >
<br >

# WebContainer

como o StackBlitz transformou o desenvolvimento web com Node.js no navegador

---
layout: image-right
image: eu.jpg
title: "Gabriel Daltoso - @ggdaltoso"
---

<br >
<br >

# Gabriel Daltoso

Desenvolvedor UX/UI - StackBlitz

<a target="_blank" alt="Perfil no Twitter de Gabriel Daltoso" href="https://twitter.com/ggdaltoso">@ggdaltoso</a>

<a target="_blank" alt="Link para a apresentação" href="https://tdc-2023.ggdaltoso.dev" class="text-3xl mt-26 inline-block">tdc-2023.ggdaltoso.dev</a>

<div class="abs-bl my-10 mx-12 flex gap-2">
  <a href="https://github.com/ggdaltoso" target="_blank" alt="Perfil no Github de Gabriel Daltoso"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
  <a href="https://twitter.com/ggdaltoso" target="_blank" alt="Perfil no Twitter de Gabriel Daltoso"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-twitter />
  </a>
  <a href="https://linkedin.com/in/ggdaltoso" target="_blank" alt="Perfil no LinkedIn de Gabriel Daltoso"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-linkedin />
  </a>
</div>

---
class: bg-white color-blue flex justify-center items-center
---

<h1 class="flex-grow-1 text-center">
  Node + StackBlitz = WebContainer
</h1>

---
class: bg-white flex justify-center items-center
---

<h1 class="flex-grow-1 text-center">
  <span class="color-blue">Node</span> + StackBlitz = WebContainer
</h1>

---

<div class="w-full h-full flex justify-center items-center">

<v-click>

![](/5/internet.png)

</v-click>

<v-click>

      ❓  
  
</v-click>
<v-click>
  <img src="/5/old-chrome.png" width="54"/>
</v-click>

</div>

<v-click>
  <div class="abs-br mr-10">
    <div class="flex gap-4 flex-items-end">    
      <a class="mb-2" target="_blank" href="https://en.wikipedia.org/wiki/Ryan_Dahl">
        Ryan Dahl
      </a>
      <img src="/5/Ryan.png" />
    </div>
  </div>
</v-click>
<!-- 
 Tópico 1: O JavaScript além do navegador
 - Breve introdução sobre o JavaScript, sua origem e função principal no navegador.
- Mencionar o lançamento do Chrome em 2008 e o uso do motor V8 para compilar JavaScript em código de máquina.
 - Destacar Ryan Dahl, que pegou o V8 e criou o NodeJS, permitindo que o JavaScript fosse executado fora do navegador.
-->

---

<div class="w-full h-full flex justify-center items-center">

<v-click>
  <img src="/6/node-logo.png" width="48" />
</v-click>
 
<v-click>

      +  

</v-click>

<v-click>
  <img src="/6/old-chrome.png" width="56" />
</v-click>

<v-click>
  <div class="abs-br m-16 text-6xl">
    😢
  </div>
</v-click>

</div>

<!--
 Tópico 1 (continuação): O desafio de trazer o Node para o navegador
 - Destacar a ideia de trazer o Node para o navegador, tornando mais fácil para os desenvolvedores utilizarem as funcionalidades do Node no desenvolvimento web.
-->

---
class: bg-white color-blue flex justify-center items-center
---

<h1 class="flex-grow-1 text-center">
  Node + StackBlitz = WebContainer
</h1>

---
class: bg-white flex justify-center items-center
---

<h1 class="flex-grow-1 text-center">
  Node + <span class="color-blue">StackBlitz</span> = WebContainer
</h1>

---
class: bg-white flex flex-col justify-center items-center color-dark
---

<v-click>

  <div class="flex gap-6">

  ![Eric Simons](/9/eric.png)

  ![Albert Pai](/9/pai.png)

  </div>

</v-click>

<v-click>

  <div class="flex gap-6 justify-center items-center">
    <a target="_blank" href="https://twitter.com/ericsimons40">Eric Simons</a>
    <a target="_blank" class="ml-4" href="https://twitter.com/iamalbertpai">Albert Pai</a>
  </div>

</v-click>

<v-click>
  <span class="fixed top-46 left-110 text-2xl"> 💢 </span>
  <span class="fixed top-50 left-128 text-2xl"> 💢 </span>
</v-click>

<!-- 
 Tópico 2: Superando obstáculos e expandindo funcionalidades
 - Explicar a motivação de Eric e Albert ao desenvolverem uma plataforma de ensino de programação e os problemas enfrentados pelos alunos na configuração do ambiente.
 -->
---
class: bg-white grid grid-cols-3 p-20 place-items-center color-dark gap-6
---

<v-click>
  <div class="flex flex-col justify-center items-center">
    <img src="/10/file-system.png" />
    <span class="font-mono text-4">File system</span>
  </div>
  <div class="flex flex-col justify-center items-center">
    <img src="/10/event-loop.png" />
    <span class="font-mono text-4">Event Loop</span>
  </div>
  <div class="flex flex-col justify-center items-center">
    <img src="/10/serialization.png" />
    <span class="font-mono text-4">Serialization</span>
  </div>
  <div class="flex flex-col justify-center items-center">
    <img src="/10/package-manager.png" />
    <span class="font-mono text-4">Package manager</span>
  </div>
  <div class="flex flex-col justify-center items-center">
    <img src="/10/git.png" />
    <span class="font-mono text-4">git</span>
  </div>
  <div class="flex flex-col justify-center items-center">
    <img src="/10/terminal.png" />
    <span class="font-mono text-4">Terminal</span>
  </div>
</v-click>

<v-click>
  <span class="fixed top-43 left-66 text-2xl"> ✅ </span>
  <span class="fixed top-43 left-135 text-2xl"> ✅ </span>
  <span class="fixed top-43 left-209 text-2xl"> ✅ </span>
  <span class="fixed top-95 left-70 text-2xl"> ✅ </span>
  <span class="fixed top-95 left-126 text-2xl"> ✅ </span>
  <span class="fixed top-95 left-202 text-2xl"> ✅ </span>
  <a target="_blank" class="color-dark fixed bottom-12 left-105" href="https://blog.stackblitz.com/">blog.stackblitz.com</a>
</v-click>


<!-- 
 Tópico 2 (continuação): Os desafios encontrados
 Destacar as implementações necessárias para suportar o Node no navegador:
   - Sistema de arquivos
   - ES Modules
   - Event loop e serialização
   - Introdução do Turbo como gerenciador de pacotes
   - Possibilidade de executar comandos de terminal
 - Destacar a falta de suporte e limitações das ferramentas existentes, principalmente dos navegadores.
 - Mencionar a contribuição da equipe na identificação e resolução de bugs, como problemas de memória no V8 e WebAssembly, questões de threads no Firefox e no ARM M1.
-->

---
class: bg-white flex justify-center items-center
---

<h1 class="flex-grow-1 text-center">
  Node + StackBlitz = <span class="color-blue">WebContainer</span>
</h1>

---
class: bg-white flex justify-center items-center
---

  <img src="/12/browser.png" width="600" />

  <v-click>
    <img src="/12/msdos.png" class="abs-br m-30 mr-64" /> 
  </v-click>

  <v-click>
    <div class="abs-tl mt-48 ml-66 text-2">
      <ol>
        <li>████████████████████████████</li>
        <li>████████████████</li>
        <li>████████████████████████████</li>
        <li>█████████████████████</li>
        <li>████████████████████████████████</li>
        <li>██████████████████</li>
        <li>███████████████████████</li>
        <li>█████████████</li>
        <li>████████████████████████████</li>
        <li>████████████</li>
        <li>█████████████████████████</li>
        <li>██████████████</li>
        <li>██████████</li>
        <li>███████</li>
      </ol>
    </div>  
  </v-click>

  <v-click>
    <Arrow class="color-red" x1="450" y1="400" x2="640" y2="416" />
  </v-click>

  <v-click>
    <Arrow class="color-red" x1="680" y1="380" x2="660" y2="336" />
    <span class="abs-tr mt-56 mr-72 text-8xl" >✨</span>
  </v-click>
  
  <v-click>
  <a target="_blank" class="color-dark fixed bottom-8 left-108" href="https://webcontainers.io/">webcontainers.io</a>
  </v-click>

<!--
 Tópico 3: StackBlitz - Facilitando o desenvolvimento web
 - Introduzir o StackBlitz como uma interface de desenvolvimento online capaz de rodar aplicações NodeJS no navegador.
 - Destacar a inspiração do NodeJS para a criação do StackBlitz, visando facilitar o processo de configuração do ambiente de desenvolvimento e permitir que os desenvolvedores se concentrem nas suas ideias.
-->
---
layout: two-cols
---

<Tweet id="1647708875834138625" scale="0.6" />

::right::

<iframe class="w-full h-118 m-auto" src="https://typescript-lzex4b.stackblitz.io/" />

<!-- 
 Tópico 4: WebContainer - Uma nova abordagem
 - Apresentar o WebContainer como uma tecnologia do StackBlitz que permite executar aplicações NodeJS diretamente no navegador.
 - Explicar que o WebContainer segue a API do NodeJS, permitindo que os desenvolvedores utilizem as ferramentas que já conhecem e se sintam em casa.
 - Destacar exemplos de sucesso que utilizam WebContainers:
   - Educação: "Professional TypeScript Training by Matt Pocock | Total TypeScript"
   - Simulador de fluído Euleriano: disponível em https://twitter.com/_paigesun/status/1647708875834138625
   - Documentação: no próprio site do NodeJS, em "Introduction to Node.js (nodejs.dev)"
   - Tutoriais: como no caso do SveltKit, disponível em "Introduction / What is SvelteKit? • Svelte Tutorial"
   - Inteligência Artificial: utilize inteligência artificial e WebContainers para gerar um projeto, disponível em "Chat UI Builder (chat-ui-builder.vercel.app)"
-->

---
preload: false
---

<iframe class="w-full h-118 m-auto" src="https://nodejs.dev/en/learn/" />

---
preload: false
layout: two-cols
class: flex justify-center items-center
---

<a target="_blank" href="https://learn.svelte.dev/tutorial/introducing-sveltekit">
  https://learn.svelte.dev
</a>

::right::

<a target="_blank" href="https://www.sveltelab.dev/">
  https://www.sveltelab.dev
</a>

---
preload: false
class: p-0
---

<iframe class="w-full h-full m-auto" src="https://chat-ui-builder.vercel.app/" />

---
class: flex justify-center items-center
---

<a target="_blank" class="b-none transition-300" href="https://www.gbstudio.dev/" >
  
  <img src="/17/gb-studio.png" alt="GB Studio logo" width="64"/> 

</a>

<style>
  a {
    border-bottom-width: 0 !important;
  }
  a:hover {
    transform: scale(1.2);
  }
</style>

<!-- 
 Mostrar um caso de uso meu com GBStudio
-->

---
class: flex justify-center items-center
---

  FIM

<!-- 
 Conclusão
 - Relembrar a evolução do JavaScript, do seu uso no navegador até a sua aplicação no desenvolvimento web com o NodeJS, o StackBlitz e o WebContainer.
 - Destacar a importância dessas ferramentas na facilitação e agilidade do desenvolvimento web.
 - Convidar a audiência a explorar essas tecnologias e aproveitar os exemplos de sucesso que utilizam WebContainers.

Agradecimentos e Encerramento
 - Agradecer a audiência pela atenção e participação.
 - Encerrar a apresentação de forma descontraída e agradável.
-->
---

