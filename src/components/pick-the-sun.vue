<template>
    <div>

        <div class="px-4 pt-0 pb-5 my-5 text-center" style="position: relative; ">
            <span class="no-waste">No more waste</span>
            <h4 class="display-6 fw-bold text-body-emphasis">Pick the Sun</h4>
            <div class="col-lg-8 mx-auto">
                <p class="lead mb-4">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit. </p>
            
            </div>
             
            <div class="container"> 
                <div class="col-10 col-sm-12 col-lg-10 mx-auto">
                
                <img src="/public/desktopImg.jpg" style="width: 100%; height: 100%; object-fit: cover; background-repeat: no-repeat; background-position: center; background-size: cover;"/>
                
                
                <!-- <div class="left-circle"></div>
                 -->
            
            </div>
            </div>
        </div>
    </div>
</template>
<script setup>
import Desktop from './desktop.vue'
</script>
<style scoped>
.no-waste{
    color:  #D97706;
text-align: center;


font-size: 20px;
font-style: normal;
font-weight: 500;
line-height: 110%; /* 22px */
}
.left-circle{
    width: 610px;
height: 611px;
flex-shrink: 0;
border-radius: 711px;
background: var(--Amber-500, #F59E0B);
position: absolute;
left: -20%;
z-index: -1;

top: -80px;
}
/* .right-circle{
    width: 510px;
height: 511px;
flex-shrink: 0;
border-radius: 597px;
background: var(--Purple-700, #7E22CE);
position: absolute;
right: -10%;
top: 100px;
} */
</style>
