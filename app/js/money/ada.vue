<template>
    <Panel title="神劵" :class="$style.panel">
        <section :class="$style.content">
            <img src="//img12.360buyimg.com/jrpmobile/jfs/t27274/47/1656760071/48411/134ca9fa/5be8d67cN42ea4a37.jpg?width=750&height=220" alt="">

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
