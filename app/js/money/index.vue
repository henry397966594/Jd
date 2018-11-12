<template lang="html">
    <div>
        <Heador></Heador>
        <Slider></Slider>
        <Ada></Ada>
        <Money></Money>
        <Adb></Adb>
        <Finance></Finance>
        <Adc></Adc>
        <Footor cname="mfooter"></Footor>
        <Navbar></Navbar>
        
    </div>
</template>

<script>
import Heador from "../public/header";
import Slider from "./mslider";
import Ada from "./ada";
import Money from "./money";
import Adb from "./adb";
import Finance from "./finance";
import Adc from "./adc";
import Footor from "../public/footer";
import Navbar from "../public/navbar";
export default {
    components: {
        Heador,
        Slider,
        Footor,
        Navbar,
        Ada,
        Money,
        Adb,
        Finance,
        Adc
    }
};
</script>
<style lang="scss" moudle>
.mfooter {
    ul {
        li:first-child {
            display: none;
        }
    }
}
</style>


