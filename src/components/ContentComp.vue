<template>
  <div class="container text-[#fff] md:overflow-y-hidden">
      <div class="h-screen lg:mx-auto md:container md:mx-auto md:my-auto md:h-screen md:pt-0 bg-[#293241] w-100 relative ">
        <div class="cont-sha bg-[#E0FBFC] overflow-y-scroll lg:mx-auto  xl:overflow-hidden  text-[#293241] h-[85%] w-[85%] absolute top-[7%] left-[8%] flex justify-center items-start rounded-tl-[2rem] md:rounded-tl-[2rem] rounded-br-[2rem] md:rounded-br-[2rem] rounded-tr-[6.375rem] md:rounded-tr-[9.375rem] rounded-bl-[6.375rem] md:rounded-bl-[9.375rem]">
          <div class=" flex flex-col items-start justify-center flex-auto pt-8 px-auto md:px-40 md:ml-15">
            <div class="h-full mx-auto w-[85%] md:w-[75%] lg:w-[75%] ml-2 pl-6">
              <RightAsideComp />
            </div>
            <div class=" md:text-md text-sm h-full mx-auto w-[80%] pt-7 md:pt-6 pl-6 pb-[0.5rem] font-mono text-[#293241] flex items-center justify-center">
              <span>© Copyright 2022 created by Haşim Kılıç</span>
            </div>
        </div>
        </div>
      </div>
  </div>
</template>

<script>
import RightAsideComp from "./Content/RightAsideComp.vue";
export default {
  name: 'ContentComp',
  components:{
    RightAsideComp
},
}
</script>

<style scoped>
.cont-sha{
-webkit-box-shadow: 3px 5px 18px -2px rgba(224,251,252,1);
-moz-box-shadow: 3px 5px 18px -2px rgba(224,251,252,1);
box-shadow: 3px 5px 18px -2px rgba(224,251,252,1);
}
</style>

