<template>
  <svg @mouseover="changeColor"
       @mouseout="returnColor"
       xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
       width="52"
       height="52"
       viewBox="0 0 52 52">
    <defs>
      <path id="9f9ka"
            d="M986 5637a26 26 0 1 1-52 0 26 26 0 0 1 52
            0zm-9.75-15.08c0-.64-.53-1.17-1.17-1.17h-30.16c-.64 0-1.17.53-1.17
            1.17v30.16c0 .64.53 1.17 1.17 1.17h30.16c.64 0 1.17-.53 1.17-1.17zM960
            5630.5a6.5 6.5 0 1 1 0 13 6.5 6.5 0 0 1 0-13zm6.5-6.5h6.5v6.5h-6.5zm2.95
            11.37H973V5650h-26v-14.63h3.55c-.14.66-.22.94-.22 1.63a9.68 9.68 0 0 0
            19.34 0c0-.7-.08-.97-.22-1.63z"/>
    </defs>
    <g>
      <g transform="translate(-934 -5611)">
        <use :fill="color" xlink:href="#9f9ka"/>
      </g>
    </g>
  </svg>
</template>

<script>
export default {
  name: "IconInstagram",
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