<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://www.masakapahariini.com/wp-content/uploads/2021/03/shutterstock_1742054867-780x440.jpg',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://img-cdn.medkomtek.com/AXY4I5NksTBSSIFzGUSxCb2n4TI=/0x0/smart/filters:quality(75):strip_icc():format(webp)/article/dX5CqkEEpcJR8FTJFp6xL/original/068756000_1603085635-Kenali-Mitos-dan-Fakta-Seputar-Minuman-Bersoda-shutterstock_361921463.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': 'hhttps://img.taste.com.au/wuNwZZDt/w720-h480-cfill-q80/taste/2019/02/game-of-thrones-147508-3.jpg',
    'alt': 'Picture 3',
  },
  {
    'src': 'https://balitribune.co.id/sites/default/files/styles/xtra_large/public/field/image/Orang%20Eropa%20Doyan%20Makanan%20Indonesia.jpg?itok=KhyFFbAs',
    'alt': 'Picture 4',
  },
  {
    'src': 'https://img.okezone.com/content/2020/11/23/298/2314516/cara-bikin-dessert-puding-tiramisu-rasanya-manis-dan-lembut-IWL9ys0Tfo.jpg',
    'alt': 'Picture 5',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>
