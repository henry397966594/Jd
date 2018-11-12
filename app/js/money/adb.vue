<template>
    <Panel title="抢" :class="$style.panel">
        <section :class="$style.content">
            <img src="//img12.360buyimg.com/jrpmobile/jfs/t27532/62/1642715267/52820/b6b9e9ba/5be92aa2Nb3ec2fa5.gif?width=750&height=280" alt="">

        </section>

    </Panel>
</template>

<script>
import Panel from "../core/panel";
export default {
    data() {
        return {};
    },
    components: {
        Panel
    }
};
</script>

<style lang="scss" module>
@import "../../css/element.scss";
.panel {
    @include panel;
    > h4 {
        display: none;
    }
    .content {
        img {
            width: 100%;
            height: 230px;
            display: block;
        }
    }
}
</style>
