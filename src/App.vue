<script setup>
import TabsWrapper from './components/TabsWrapper.vue'
import TabItem from './components/TabItem.vue'
</script>

<template>
    <TabsWrapper>
        <TabItem title="Tab 1">Content from Tab 1</TabItem>
        <TabItem title="Tab 2">Content from Tab 2 Lorem ipsum dolor sit amet.</TabItem>
        <TabItem title="Tab 3">Content from Tab 3 Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates, ipsa.</TabItem>
        <TabItem title="Tab 4">Content from Tab 4 Lorem ipsum dolor sit amet.</TabItem>
        <TabItem title="Tab 5">Content from Tab 5 Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora maiores ab minima. Facere mollitia tempora soluta, commodi beatae sit. Distinctio.</TabItem>
        <TabItem title="Tab 6">Content from Tab 6</TabItem>
    </TabsWrapper>
</template>

<style>
* {
    box-sizing: border-box;
}
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
