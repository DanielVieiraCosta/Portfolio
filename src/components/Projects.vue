<script></script>

<template>
  <main class="pb-4 border-bottom" id="projetos">
    <h1 class="laranja_degrade mt-3 mb-5"><b>Conheça alguns dos meus projetos</b></h1>
    
    <div class="row mb-5">
      <div class="order-2 order-xxl-1 col-xxl-5 gy-4">
        <p class="text-break laranja_degrade">
          Este projeto foi desenvolvido como <b>freelancer</b> para uma barbearia local, com o objetivo de automatizar e simplificar o processo de reservas.
          O sistema permite que os clientes escolham o serviço, barbeiro e horário desejados, tornando o <b>agendamento mais rápido e organizado.</b><br><br>

          O projeto contou com <b>integração ao Google Calendar API</b>, adicionando automaticamente as reservas à agenda do barbeiro responsável.
          Também trabalhei com validações de datas, horários e disponibilidade, <b>evitando conflitos entre agendamentos.</b>
        </p>
        <a href="https://loshermanosmarilia.com.br" target="_blank"><button class="btn-orange rounded-2">Acessar Projeto</button></a>
        <div class="mt-3 d-flex flex-wrap gap-2">
          <span class="tag_green rounded-4">Vue.js</span>
          <span class="tag_purple rounded-4">C#</span>
          <span class="tag_purple rounded-4">ASP.NET Core</span>
          <span class="tag_blue rounded-4">MySQL</span>
          <span class="tag_blue rounded-4">Google Calendar API</span>
          <span class="tag_purple rounded-4">Bootstrap</span>
          <span class="tag_yellow rounded-4">JavaScript</span>
        </div>
      </div>
      <div id="carouselLosHermanos" class="carousel slide order-1 col-xxl-7">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselLosHermanos" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselLosHermanos" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselLosHermanos" data-bs-slide-to="2" aria-label="Slide 3"></button>
          <button type="button" data-bs-target="#carouselLosHermanos" data-bs-slide-to="3" aria-label="Slide 4"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="/src/assets/LosHermanos_Projects/Home.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="/src/assets/LosHermanos_Projects/Reservation.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="/src/assets/LosHermanos_Projects/Unit.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="/src/assets/LosHermanos_Projects/MyReservation.png" class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselLosHermanos" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselLosHermanos" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
    <div class="row">
      <div class="order-2 order-xxl-1 col-xxl-5 gy-4">
        <p class="text-break laranja_degrade">
          <b>Site institucional</b> desenvolvido para a divulgação de uma barbearia, apresentando seus serviços, profissionais, informações sobre o
          estabelecimento, canais de contato e redes sociais.<br><br>

          O projeto teve como foco uma <b>interface moderna, organizada e responsiva</b>, facilitando o acesso às informações e proporcionando uma
          experiência <b>simples e agradável</b> aos usuários.
        </p>
        <a href="https://danielvieiracosta.github.io/Los_Hermanos_Barbearia" target="_blank"><button class="btn-orange rounded-2">Acessar Projeto</button></a>
        <div class="mt-3 d-flex gap-2">
          <span class="tag_green rounded-4">Vue.js</span>
          <span class="tag_purple rounded-4">Bootstrap</span>
        </div>
      </div>
      <div id="carouselBarbershop" class="carousel slide order-1 col-xxl-7">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselBarbershop" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselBarbershop" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselBarbershop" data-bs-slide-to="2" aria-label="Slide 3"></button>
          <button type="button" data-bs-target="#carouselBarbershop" data-bs-slide-to="3" aria-label="Slide 4"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="/src/assets/BarbeariaLosHermanos/Home.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="/src/assets/BarbeariaLosHermanos/AboutEndServices.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="/src/assets/BarbeariaLosHermanos/Barbers.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="/src/assets/BarbeariaLosHermanos/Reserve.png" class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselBarbershop" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselBarbershop" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </main>
</template>