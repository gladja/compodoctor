<template>
  <svg @mouseover="changeColor"
       @mouseout="returnColor"
       xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
       width="52"
       height="52"
       viewBox="0 0 52 52">
    <defs>
      <path id="3f06a"
            d="M898.93 5637.03a25.97 25.97 0 1 1-51.93 0 25.97 25.97 0 0 1 51.93
            0zm-18.68-5.37h-4.83v-2.69c0-1.4.1-2.15 2.11-2.15h2.69v-5.37h-4.3c-5.16
            0-6.34 2.66-6.34 7.05v3.16h-3.9v5.37h3.9v15.58h5.84v-15.58h4.26z"/>
    </defs>
    <g>
      <g transform="translate(-847 -5611)">
        <use :fill="color" xlink:href="#3f06a"/>
      </g>
    </g>
  </svg>
</template>

<script>
export default {
  name: "IconFacebook",
  data() {
    return {
      color: '#bd4848',
    }
  },
  methods: {
    changeColor() {
      this.color = '#ffffff';
    },
    returnColor() {
      this.color = '#bd4848';
    }
  }
}
</script>

<style>

</style>