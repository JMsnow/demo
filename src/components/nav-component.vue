<template>
    <ul class="menuOpen">
        <li :class="{current: current === 1}">
            <a href="./index.html"><i></i>这是首页</a>
        </li>
        <li :class="{current: current === 2}">
            <a href="./module2.html"><i></i>这是模块2</a>
        </li>
        <li :class="{current: current === 3}">
            <a href="./module3.html"><i></i>这是模块3</a>
        </li>
        <li :class="{current: current === 4}">
            <a href="./router.html"><i></i>这是带路由的模块</a>
        </li>
        <li :class="{current: current === 5}">
            <a href="./vuex.html"><i></i>这是带Vuex的模块</a>
        </li>
    </ul>
</template>
<script>
import '../assets/less/style.less'
export default {
    props: ['current']
}
</script>
