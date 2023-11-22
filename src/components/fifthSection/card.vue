<template>
    <div class="card">
        <div>
            <img v-bind:src="picture" alt="">
        </div>
        <h3>{{headText}}</h3>
        <p>{{description}}</p>
        <button class="learn-more">Learn more</button>
    </div>
</template>
<script>
export default {
    name:"InfoCards",
    props:{
        headText: String,
        description: String,
        picture: Object
    }
}
</script>