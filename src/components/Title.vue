<!-- 
    creo 3 elementi:
template (HTML) => con all' interno un div
script (JAVASCRIPT) => creo un oggetto chimato export default con un nome in pascal case {nome_componente}
style(CSS) => inserico il css del componente creato, (<style scoped lang="scss">)
-->

<template>
    <div>
        <h1>Hello World</h1>
        <h2>“La mia prima app con Vue CLI!</h2>
    </div>
</template>

<script>
export default {
    name: 'TitlePage'
    
}
</script>

<style lang="scss">

</style>
