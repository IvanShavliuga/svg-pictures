<template>
<div>
  <Bulb/>
  <Usb-Flash/>
  <Eye/>
</div>
</template>
<script>
import Bulb from "./pictures/Bulb.vue";
import Eye from "./pictures/Eye.vue";
import UsbFlash from "./pictures/UsbFlash.vue";
export default {
  components: {
    Bulb,
    UsbFlash,
    Eye 
  }
}
</script>
