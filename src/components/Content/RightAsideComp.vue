<template>
    <div>
        <div class="flex items-center justify-center md:justify-start">
        <span class="font-bold text-4xl md:text-5xl pb-7 pl-3 mr-1 md:mr-4">{{title}} </span>
        <img :src="url" class="w-[3.5rem] md:w-[4rem] pb-10 ">
        </div>
        <div class="pl-3">
        <span class="pt-8 font-bold text-lg md:text-xl"> · {{subTitle}}</span>
        <br>
        <span class="pt-8 font-bold text-lg md:text-xl"> · {{subTitle2}}</span>
        </div>
        <p class="text-lg pt-6 mt-6 pb-14 font-sans pl-3 ">{{content}} <br>
        I like to work with the team, with the agile working method, with the division of labor.</p>
        <IconsContComp />
    </div>
</template>

<script>
import IconsContComp from './IconsContComp.vue'
export default {
    name: "RightAside",
    components: { IconsContComp },
    data() { 
        return {
            title: "Hello I'm Haşim",
            content: "I am developing myself in the field of Front End, which I continue to learn with love and enjoyment and I am working to specialize in this field. I also do designs in the web field.",
            subTitle:'Front-End Developer / Web Designer',
            subTitle2:'Management Information System Student',
            url:'https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif'
        };
    },
}
</script>
