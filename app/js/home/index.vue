<template lang="html">
    <div>
        <Heador></Heador>
        <Slider></Slider>
        <Novice></Novice>
        <Borrow></Borrow>
        <Money></Money>
        <Product></Product>
        <Life></Life>
        <Footor></Footor>
        <Navbar></Navbar>
        
    </div>
</template>

<script>
import Heador from '../public/header'
import Slider from './hslider'
import Novice from './novice'
import Borrow from './borrow'
import Money from './money'
import Product from './product'
import Life from './life'
import Footor from '../public/footer'
import Navbar from '../public/navbar'
export default {
  components: {
    Heador,Slider,Novice,Borrow,Money,Product,Life,Footor,Navbar
  }
}
</script>


