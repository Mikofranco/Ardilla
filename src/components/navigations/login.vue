<template>
   <div class="login-section">
        <button class="sign-in" >Sign in</button>
        <button class="sign-up" >Create Account</button>
        <div class="contain">
            <div class="world">
                <img v-bind:src="world_image" alt="">
            </div>
        </div>
        <span><img v-bind:src="arrow" alt=""></span>
   </div>
</template>

<script>
import image from "../../assets/world.png"
import arrowDown from "../../assets/gridicons_dropdown.svg"
    export default {
    data() {
        return {
            world_image: image,
            arrow:arrowDown
        };
    },
};
</script>

<style scoped>
button{
    color: white;
}
.sign-in{
    background-color: transparent; 
    outline: none;
    border: none;
}
.sign-up{
    background-color: #8807F7;
    padding: 10px 20px;
    margin-left: 3rem;
    border-radius: 1rem;
}
.world{
    width: fit-content;
    padding: px;
    border-radius: 50%;
    width: 100%;
    height: 100%;
    background-color: #D6ABFC;
    justify-content: center;
}
.contain{
    width: 2rem;
    height: 2rem;
}
.login-section{
    display: flex;
    justify-content: center;
}

</style>