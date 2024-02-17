<template>
  <header_component></header_component>
  <content>
    <div class="bg-form">
      <div class="flex justify-center items-center h-full">
        <div
          class="text-white flex justify-center items-center flex-col text-center space-y-[22px]"
        >
          <h2 class="text-3xl" data-aos="fade-up" data-aos-delay="100">
            Кадровое агенство «Анима»
          </h2>
          <h1 class="text-6xl" data-aos="fade-up" data-aos-delay="100">
            Услуги по работе с персоналом
          </h1>
          <h2 class="text-3xl" data-aos="fade-up" data-aos-delay="100">
            Подбор. Оценка. Развитие.
          </h2>
          <div>
            <Button class="mt-6"></Button>
          </div>
        </div>
      </div>
    </div>
    <div class="my-[100px]">
      <div class="w-[80%] mx-auto">
        <div
          class="flex flex-wrap items-center space-x-5 justify-center"
          data-aos="fade-up"
          data-aos-delay="100"
        >
          <div
            class="w-[260px] border border-black rounded-lg h-[170px] bg-white"
          >
            <div class="flex justify-center items-center h-full">
              <div class="flex flex-col justify-between h-[70%] mx-3">
                <img src="../assets/img/human.svg" class="w-[36px]" />
                <p>
                  Работа <b>экспертов</b>, действующих директоров по персоналу
                </p>
              </div>
            </div>
          </div>
          <div
            class="w-[260px] border border-black rounded-lg h-[170px] bg-[#DBF2FF]"
          >
            <div class="flex justify-center items-center h-full">
              <div class="flex flex-col justify-between h-[70%] mx-3">
                <img src="../assets/img/portf.svg" class="w-[36px]" />
                <p>
                  Внимание к проблематике, погружение в
                  <b>особенности</b> бизнеса
                </p>
              </div>
            </div>
          </div>
          <div
            class="w-[260px] border border-black rounded-lg h-[170px] bg-white"
          >
            <div class="flex justify-center items-center h-full">
              <div class="flex flex-col justify-between h-[70%] mx-3">
                <img src="../assets/img/corona.svg" class="w-[36px]" />
                <p>
                  <b>Честные</b> и <b>доверительные</b> отношения, каждый
                  заказчик - vip
                </p>
              </div>
            </div>
          </div>
          <div
            class="w-[260px] border border-black rounded-lg h-[170px] bg-[#DBF2FF]"
          >
            <div class="flex justify-center items-center h-full">
              <div class="flex flex-col justify-between h-[70%] mx-3">
                <img src="../assets/img/done.svg" class="w-[36px]" />
                <p>
                  <b>Качество</b> подбора, сложные вакансии, низкий процент
                  замены
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="my-[100px]">
      <div class="w-[80%] mx-auto">
        <h2 class="text-4xl text-center mb-[100px]">Мы предлагаем</h2>
        <div
          class="flex flex-wrap items-center space-x-5 justify-center"
          data-aos="fade-up"
          data-aos-delay="100"
        >
          <div class="w-[240px] rounded-lg h-[300px] bg-[#DBF2FF]">
            <div class="flex h-full">
              <div class="flex flex-col">
                <img
                  src="../assets/img/img1.png"
                  class="w-full rounded-t-lg h-[230px] object-cover"
                />
                <div
                  class="h-[70px] flex justify-center items-center w-[80%] mx-auto"
                >
                  <p class="text-center">Подбор персонала</p>
                </div>
              </div>
            </div>
          </div>
          <div class="w-[240px] rounded-lg h-[300px] bg-[#DBF2FF]">
            <div class="flex h-full">
              <div class="flex flex-col">
                <img
                  src="../assets/img/img2.png"
                  class="w-full rounded-t-lg h-[230px] object-cover"
                />
                <div
                  class="h-[70px] flex justify-center items-center w-[80%] mx-auto"
                >
                  <p class="text-center">Подбор внешних бизнес-эксперов</p>
                </div>
              </div>
            </div>
          </div>
          <div class="w-[240px] rounded-lg h-[300px] bg-[#DBF2FF]">
            <div class="flex h-full">
              <div class="flex flex-col">
                <img
                  src="../assets/img/img3.png"
                  class="w-full rounded-t-lg h-[230px] object-cover"
                />
                <div
                  class="h-[70px] flex justify-center items-center w-[80%] mx-auto"
                >
                  <p class="text-center">Психологическое тестирование</p>
                </div>
              </div>
            </div>
          </div>
          <div class="w-[240px] rounded-lg h-[300px] bg-[#DBF2FF]">
            <div class="flex h-full">
              <div class="flex flex-col">
                <img
                  src="../assets/img/img4.png"
                  class="w-full rounded-t-lg round h-[230px] object-cover"
                />
                <div
                  class="h-[70px] flex justify-center items-center w-[80%] mx-auto"
                >
                  <p class="text-center">Кадровый резерв и тренинги</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </content>
</template>

<script lang="ts" setup>
import AOS from "aos";
import "aos/dist/aos.css";

onMounted(() => {
  AOS.init({
    // Настройки AOS
    duration: 1200, // Продолжительность анимации в миллисекундах
  });
});
</script>

<style>
.bg-form {
  background-image: url(../assets/img/snapedit_17064806873251.png);
  background-size: 100%;
  height: 800px;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
