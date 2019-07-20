<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header" v-text="title"></div>

                    <div class="card-body">
                        <p v-text="body"></p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data(){
            return {
                title:'Hola, soy un componente!',
                body:'Aqui se coloca informacion o algo asi :v'
            }
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
