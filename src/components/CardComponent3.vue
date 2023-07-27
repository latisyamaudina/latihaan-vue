<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
<center>
    <h1><b>DESSERT</b></h1>
</center><br>
<div class="flex flex-row">
  <div class="grid grid-cols-3 gap-9 m=8 mx-20">
<the-card variant="image" img-src="https://binus.ac.id/bandung/wp-content/uploads/2019/12/artikel-26.1.2.jpg" img-alt="Desk">
  <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">PANNACOTTA</h5>
  <p class="font-normal text-gray-700 dark:text-gray-400">
      <b>Rp.40.000</b><br>
      <b>
        Cocok untuk mengakhiri makan kamu
      </b>
    </p>
</the-card>

<the-card variant="image" img-src="https://img.okezone.com/content/2020/11/23/298/2314516/cara-bikin-dessert-puding-tiramisu-rasanya-manis-dan-lembut-IWL9ys0Tfo.jpg" img-alt="Desk">
  <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Puding Tiramisu</h5>
  <p class="font-normal text-gray-700 dark:text-gray-400">
      <b>Rp.35.000</b><br>
      <b>
        Sebagai makanan penutup
      </b>
    </p>
</the-card>

<the-card variant="image" img-src="https://img.taste.com.au/wuNwZZDt/w720-h480-cfill-q80/taste/2019/02/game-of-thrones-147508-3.jpg" img-alt="Desk">
  <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Lemon Ricotta cake</h5>
  <p class="font-normal text-gray-700 dark:text-gray-400">
      <b>Rp.60.000</b><br>
      <b>
        Cake dengan ciri khas lemonnya yang sangat enak dengan toping es krim
      </b>
    </p>
</the-card>
</div>
</div>

</template>
