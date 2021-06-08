<template>
  <v-container id="memes">
    <v-row>
      <v-col md = "6">
        <v-card max-width="500" >
          <v-carousel id="meme" >
            <v-carousel-item
                v-for="(item,i) in meme1"
                :key="i"
                :src="item.src"
                reverse-transition="fade-transition"
                transition="fade-transition"

            ></v-carousel-item>
          </v-carousel>
        </v-card>
      </v-col>

      <v-col md = "6">
        <v-card max-width="500">
          <v-carousel id="meme2" >
            <v-carousel-item
                v-for="(item,i) in meme2"
                :key="i"
                :src="item.src"
                reverse-transition="fade-transition"
                transition="fade-transition"

            ></v-carousel-item>
          </v-carousel>
        </v-card>
      </v-col>

      <!--    <v-container id="back">-->

      <!--    </v-container>-->
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "All memes",
  data() {
    return {
      meme1: [
        {
          src: 'https://sun9-18.userapi.com/impg/_n2S6GbsJUw-x936lAucRBjgiTdXVBD9x-euBQ/vPQCTDbvBd8.jpg?size=1280x1280&quality=96&sign=3196883ac2784e85e5edef088a2be772&type=album',
        },
        {
          src: 'https://sun9-41.userapi.com/impg/Gn3x8Rli12VIrsn9FU5Gk88lQUQviHZB-yMcDA/MXR8arcBFvY.jpg?size=1280x1280&quality=96&sign=2ac811abdd3bda18347aca589d4970e2&type=album',
        },
        {
          src: 'https://sun9-58.userapi.com/impg/2QUewGm2aYLWQq2DJs_SpRi2b2Nthk2gWSnppw/pfpAEMjVuSo.jpg?size=1280x1280&quality=96&sign=e36770518f6cceb6330a6fd0312352b8&type=album',
        },
        {
          src: 'https://sun9-28.userapi.com/impg/uP5v1QRO8lq1Zo0W7ILv0ljH0YFl7CTjfmDlpw/EkjB1C423Ag.jpg?size=1280x1280&quality=96&sign=94a35a921bd08502af82cd03a1c772e1&type=album',
        },
        {
          src: 'https://sun9-24.userapi.com/impg/uYDHNcXdrdXWaK7slIQhoxsIToKOK1cAvjQ5hw/zAqs7V17zfU.jpg?size=1280x1280&quality=96&sign=dff7a744de86246f3c971d43764628f7&type=album',
        },
        {
          src: 'https://sun9-27.userapi.com/impg/54k7d20_4x0P2JASeKetEOJNQBkdzvQPflx-Iw/jjRMIobPCMk.jpg?size=1280x1280&quality=96&sign=06bd2c3a89442c2163ec4b45699bd004&type=album',
        }
      ],
      meme2: [
        {
          src: 'https://sun9-60.userapi.com/impg/U7bpPoeAhbb4w4wNn4A0OV8W0hoIMeCOJmdfpQ/aHRADumTDMY.jpg?size=1280x1280&quality=96&sign=3c8cdce7a1bc5fab643a0d806866da6f&type=album',
        },
        {
          src: 'https://sun9-71.userapi.com/impg/imGpCGtkhZQWYD_k6MtE7tfQCxR5f9DraYeq1g/JtNl5UsaMfY.jpg?size=1280x1280&quality=96&sign=696b1133b17678c0ba244a326a967b55&type=album',
        },
        {
          src: 'https://sun9-51.userapi.com/impg/HveFSzsAXVIUWuy0NnImkIzZBia4pD4sS2QPag/_zkqgJ_wW-A.jpg?size=1280x1280&quality=96&sign=0f66df960a0d5519ed9b1beb71b245a0&type=album',
        },
        {
          src: 'https://sun9-36.userapi.com/impg/lGehNYx9hY_z-9CflNNY60tXa2aV2Ai8_19Lyg/ppTU0N6RMsY.jpg?size=1280x1280&quality=96&sign=6b5c0208f81f274f65cba0b98e7ee87d&type=album',
        },
        {
          src: 'https://sun9-8.userapi.com/impg/MUui7f6EO4ZmoRCwcQ9srnW0TCuCpViAwuFw3w/LCl_RdRp-10.jpg?size=1280x1280&quality=96&sign=7757a196f913408f91d356c7f0d39016&type=album',
        },
        {
          src: 'https://sun9-31.userapi.com/impg/RByhpNI0ASyDp5OjCSbOPWYBNrEFsZIaFi3X0w/rTN3zHsvVKc.jpg?size=1280x1280&quality=96&sign=6dd7d8c6501edc89bfb54a6636248293&type=album',
        },
        {
          src: 'https://sun9-24.userapi.com/impg/8qyZkjUBE6Ib6fCP4WhlZr_pECgzlVGtYzexOw/uZKXfj5RsrY.jpg?size=1280x1280&quality=96&sign=9563b32b535e3b8469576573786a6780&type=album',
        },
        {
          src: 'https://sun9-61.userapi.com/impg/E0fQ5nwqOSUh7BzPFYzRcUZ7SD8BPtHtDmmCxg/E7HsOkUZDbo.jpg?size=1280x1280&quality=96&sign=615fcbeedc21b65c103230935851977c&type=album',
        },
        {
          src: 'https://sun9-59.userapi.com/impg/KX6ij1WfShr6GhCUJ_IbN89uLn0Z5dTRBMbz5A/dD80XKGj8LY.jpg?size=1280x1280&quality=96&sign=232b13a1ae2d0b203672f63650c14c84&type=album',
        },
        {
          src: 'https://sun9-63.userapi.com/impg/OFlrEu0QiTTaPxoK7pLBhor9SAjb0OrC659bnw/kgk7h8wr0tk.jpg?size=1280x1280&quality=96&sign=86e576f965cbd85862d2ad665fa4e457&type=album',
        },
      ],
    }
  },
}
</script>

<style>
#meme
{

}
#memes
{
  background-image: url("../../Img/Bar.png");
}
</style>