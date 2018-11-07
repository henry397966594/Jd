<template lang="html">
    <div>
        <Heador></Heador>
        <Slider></Slider>
        <Novice></Novice>
        <Borrow></Borrow>
        <Money></Money>
        <Product></Product>
        
    </div>
</template>

<script>
import Heador from '../public/header'
import Slider from './hslider'
import Novice from './novice'
import Borrow from './borrow'
import Money from './money'
import Product from './product'
export default {
  components: {
    Heador,Slider,Novice,Borrow,Money,Product
  }
}
</script>


