<script>
import HeaderComp from '@/components/HeaderComp.vue'

export default{
  components:{
    HeaderComp
  }
}
</script>

<template>
  <header>
    <HeaderComp />
  </header>
</template>

<style>
*,*::before,*::after{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
:root {
    --font: 'Poppins', sans-serif;
    --accent: #a26fcd;
    --menu-background: #2a2a2acc;
    --menu-title: #c3c3c3;
    --menu-border: #3a3a3a9f;
    --menu-hover: #e6e6e68a;
    --cards-bg: #3f3f3f3f;
    --cards-title: #e8e8e8;
    --cards-text: #c3c3c3;
    --cards-icon-bg: #aeaeae;
    --inset-color: rgba(235, 225, 255, 0.178);
  }
  body {
    height: 100svh;
    color: white;
    font-family: var(--font);
    background: radial-gradient(55.65% 220.76% at 21.91% 46.07%, rgba(115, 41, 161, 0.197) 0, rgba(194, 97, 254, .04) 100%), #1d1d1d;
  }

  header{
    background-color: var(--menu-background);
    color: white;
    border-style: solid;
    border: 1px;
    border-color: var(--menu-border);
  }

  @font-face{
    font-family: 'Poppins';
    src: url(/fonts/Poppins-Bold.ttf);
    font-weight: 700;
    font-style: normal;
  }
  @font-face {
    font-family: 'Popppins';
    src: url(/fonts/Poppins-Light.ttf);
    font-weight: 300;
  }
  @font-face {
    font-family: 'Poppins';
    src: url(/fonts/Poppins-Medium.ttf);
    font-weight: 500;
  }
  @font-face {
    font-family: 'Poppins';
    src: url(/fonts/Poppins-Regular.ttf);
    font-weight: 400;
  }
  @font-face {
    font-family: 'Poppins';
    src: url(/fonts/Poppins-SemiBold.ttf);
    font-weight: 600;
  }



</style>
