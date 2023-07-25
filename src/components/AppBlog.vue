<template>
    <div class="main d-in-flex f-dir-col p-20 m-20 back-yellow radius-15 j-center t-align-center">
        <div class="mb-20">
            <h2>{{title}}</h2>
        </div>    
        <div class="mb-15">
            <p>{{description}}</p>
        </div>
        <div>
            <button @click="coming" class="back-green white border-n p-10 radius-15">Read More</button>
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            title : String,
            description: String
        },
        methods: {
            coming(){
                alert('add be Soon');
            }
        }
    }
</script>

<style>

.main {
    width: calc((100% / 4) - 80px);
}

</style>