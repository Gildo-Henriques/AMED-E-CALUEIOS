<script>
  import ServicosCards from "$lib/ServicosCards.svelte";

  import Depoimentos from "$lib/Depoimentos.svelte";
  import Galeria from "$lib/Galeria.svelte";
  import Semifooter from "$lib/Semifooter.svelte";
</script>
<!-- HERO -->
<section class="2xl:px-16 lg:px-10">
  <div class="w-full lg:h-[600px] h-[550px] relative">
    <img
      src="./hero.jpg"
      alt=""
      class="w-full h-full object-cover lg:rounded-2xl"
    />
    <div
      class="absolute top-0 space-y-8  left-0 bg-gradient-to-t text-white lg:px-20 md:px-10 px-5 flex flex-col justify-end lg:pb-20 py-10 from-black lg:rounded-2xl to-transparent w-full h-full"
    >
      <h1 class="lg:text-6xl montserrat md:text-5xl text-3xl font-bold">
        Projetos de Construção e <br class="lg:flex hidden"> Acabamento de Alta Qualidade
      </h1>
      <p class="lg:text-xl text-lg text-gray-300">
        Somos uma empresa especializada em construção civil, oferecendo serviços <br class="lg:flex hidden"> completos desde a elaboração de projetos até acabamentos e manutenção.
        <br> Aproveite e faça o seu orçamento
      </p>
      <div class="flex  gap-x-5 lg:flex-row md:flex-row flex-col gap-y-3  lg:items-center">
        <a href="" class="bg-white text-black font-semibold px-5 py-3  rounded-md">FAZER O ORÇAMENTO</a>
        <a href="" class="bg-black items-center flex  font-semibold  px-5 py-3 rounded-md">CONTACTE-NOS</a>
      </div>
    </div>

  </div>
</section>

<!-- SOBRE -->
<section class="bg-white ">
  

  <div class="container flex flex-col 2xl:px-20 lg:px-16 px-5 py-10 mx-auto space-y-6 lg:h-[32rem] lg:py-16 lg:flex-row lg:items-center">
      <div class="w-full flex flex-col lg:w-1/2 gap-y-5">
          <div class="lg:max-w-lg">
              <h1 class="text-3xl font-semibold tracking-wide outfit text-gray-800 lg:text-4xl">Tudo Que Precisa saber sobre a AMED-&-CALUEIOS</h1>
              <p class="mt-4 text-gray-600 text-lg">AMED-&-CALUEIOS é uma empresa de construção civil especializada em oferecer soluções completas para projetos residenciais e comerciais. Com anos de experiência no mercado, somos comprometidos com a qualidade, inovação e a satisfação dos nossos clientes.

                </p>
              
          </div>
          <a href="#" class=" px-5 py-2 text-sm font-medium tracking-wider basis-0  w-auto self-start text-center text-white transition-colors duration-300 bg-gray-900 rounded-md hover:bg-gray-700 lg:text-lg">Saber mais</a>
      </div>

      <div class="flex items-center relative justify-center w-full h-96 lg:w-1/2">
        <div class="absolute bg-gradient-to-t from-black/90 to-transparent w-full h-full"></div>
          <img class="object-cover w-full h-full  rounded-md" src="sobre-nos.jpg" alt="glasses photo">
      </div>
  </div>
</section>
<!-- SERVIÇOS -->
 <section class=" flex flex-col items-center justify-center space-y-10 mt-10">
  <h2 class="text-3xl font-semibold tracking-wide  text-gray-800 outfit lg:text-4xl">Nossos Serviços</h2>
  <ServicosCards />
 </section>
 <!-- TESTEMUNHAS -->
  <section class="mt-20 2xl:px-20 lg:px-1">
    <Depoimentos />
  </section>
  <!-- Portifolio -->
   <section class="flex justify-center">
    <Galeria />
   </section>
   <!-- SEMIFOOTER -->
    <section class="lg:px-20">
      <Semifooter />
    </section>
    <!-- Footer -->
     