<template lang="html">
    <div>
        <Heador></Heador>
        <Slider></Slider>
        <Daily></Daily>
        <In></In>
        <Footor cname="mfooter"></Footor>
        <Navbar></Navbar>
        
    </div>
</template>

<script>
import Heador from "../public/header";
import Slider from "./rslider";
import Footor from "../public/footer";
import Navbar from "../public/navbar";
import Daily from "./daily"
import In from "./in"
export default {
    components: {
        Heador,
        Slider,
        Footor,
        Navbar,
        Daily,
        In
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





