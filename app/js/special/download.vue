<template>
    <Panel title="下载App" :class="$style.panel">
        <section :class="$style.content">
            <div>

            </div>
            <p>立即下载</p>
            <span>copyright</span>
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
html,
body {
    background: #fff;
}
.panel {
    @include panel;
    margin: 0 !important;
    > h4 {
        display: none;
    }
    .content {
        @include flex;
        justify-content: center;
        align-items: center;
        height: 1136px;
        width: 100%;
        > div {
            background: url(https://img12.360buyimg.com/jrpmobile/jfs/t8956/285/1249806938/50853/8cd3c8f0/59b65f36N05367075.png?)
                center center no-repeat;
            width: 600px;
            height: 800px;
            background-size: 100%;
            margin-top: -400px;
        }
        > p {
            @include btn(
                $size: 32px,
                $color: #fff,
                $bgcolor: #f1443e,
                $padding: 5px,
                $radius: 5px
            );
            height: 100px;
            line-height: 100px;
            width: 470px;
            position: fixed;
            bottom: 130px;
        }
        span {
            position: fixed;
            bottom: 16px;
            font-size: 24px;
            color: #eee;
        }
    }
}
</style>
