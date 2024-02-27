<template>
  
    <div class="bg-gray-900 text-gray-100 py-3.5 px-6 shadow md:flex justify-between items-center">

        <div class="flex items-center">
            <span class="text-green-500 text-x1 mr-1">
                <i class="fi fi-sr-home"></i>
            </span>

            <h1 class="text-xl">Designer</h1>
        </div>

        <ul class="md:flex md:items-center">
            <li :v-for="link in links" class="md:mx-4">
                <a :href="link.link" class="text-xl hover:text-green-500">{{ link.name }}</a>
            </li>
        </ul>
    </div>

</template>

<script>

export default { 
    setup(){
        let links = [
            {name: "Home", link: "#"},
            {name: "Lanches", link: "#"},
            {name: "Bebidas", link: "#"},
            {name: "Combos", link: "#"},
            {name: "Doces", link: "#"},
        ]

        return(links)
    }
}
</script>

<style>

</style>