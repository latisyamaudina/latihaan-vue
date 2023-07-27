<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
<center>
      <h1><b>MAKANAN</b></h1>
  </center><br>
<div class="flex flex-row">
  <div class="grid grid-cols-3 gap-9 m=8 mx-20">
  <the-card variant="image" img-src="https://www.masakapahariini.com/wp-content/uploads/2021/03/shutterstock_1742054867-780x440.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Sate</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      <b>Rp.50.000</b><br>
      <b>
        Berbagai macam varian sate dengan bumbu yang khas
      </b>
    </p>
  </the-card>

  <the-card variant="image" img-src="https://akcdn.detik.net.id/community/media/visual/2022/06/10/ilustrasi-rendang-1_169.jpeg?w=620" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Rendang</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      <b>Rp.75.000</b><br>
      <b>
        Di masak dengan resep bumbu khas Sumatra yang sudah terjamin enaknya 
      </b>
    </p>
  </the-card>


  <the-card variant="image" img-src="https://awsimages.detik.net.id/community/media/visual/2021/04/22/5-makanan-enak-dari-indonesia-dan-malaysia-yang-terkenal-enak-5.jpeg?w=600&q=90" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Nasi Goreng</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      <b> <main>mulai dari Rp.40.000</main></b><br>
      <b>
        Berbagai macam varian nasi goreng,dari nasi goreng kampung sampai nasi goreng luar Negeri
      </b>
    </p>
  </the-card>
</div>
</div>
</template>
