<template>
    <div class=" flex items-center justify-between md:ml-3 ">
        <div class="flex">
            <div class="mr-2">
                <!--Github Button-->
                <button id="github" class=" border-2 hover:border-0 text-white border-black border-solid text-2xl  min-w-wull hover:text-black hover:border-black-500 bg-black hover:border-solid hover:bg-white hover:border-black w-12 h-12  transform hover:-translate-y-3 rounded-full duration-500 ">
                    <a href="https://github.com/hasimkilic" target="_blank"><i class="fab fa-github"></i></a>
                </button>
            </div>
            <div class="mr-2">
                <!--Linkedin Button-->
                <button id="linkedin" type="button" class="bg-white transform hover:-translate-y-3  border-2 w-12 h-12 rounded-full duration-500 text-blue-500 border-blue-500  hover:bg-blue-500 hover:text-white text-2xl">
                    <a href="https://www.linkedin.com/in/hasimkilic/" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                </button>
            </div>
            <div class="mr-2">
                <!--İnstagram Button-->
                <button id="instagram" class=" border-2 hover:border-0 border-pink-500 bg-gradient-to-b text-2xl hover:from-indigo-600 hover:via-pink-600 hover:to-yellow-500 min-w-wull hover:text-white bg-white text-pink-600 w-12 h-12  transform hover:-translate-y-3 rounded-full duration-500 ">
                    <a href="https://www.instagram.com/hhasimkk/" target="_blank"><i class="fab fa-instagram"></i></a>
                </button> 
            </div>
            <div class="mr-2">
                <!--Twitter Button -->
                <button id="twitter" class="bg-white  transform hover:-translate-y-3  border-2 w-12 h-12 rounded-full duration-500 text-blue-400 border-blue-400 hover:bg-blue-400 hover:text-white text-2xl">
                    <a href="https://twitter.com/HasimK18" target="_blank"><i class="fab fa-twitter"></i></a>
                </button>
            </div>
            <div class="mr-2">
                <!--Google Plus Button -->
                <button id="googleplus" class="bg-white transform hover:-translate-y-3  py-[0.6rem] border-2 w-12 h-12 rounded-full duration-500 text-red-500 border-red-500 hover:bg-red-500 hover:text-white text-2xl">
                    <a href="mailto:hasimkilic.dev@gmail.com" target="_blank"><span class="material-symbols-rounded">mail</span></a>
                </button>                
            </div>         
        </div>
    </div>
</template>

<script>
export default {
    name:'IconsComp',
    data() {
        return {
            downLoad:'Download CV',
            url:'./assets/HasimKilicCv.pdf',
        }
    },

}
</script>
