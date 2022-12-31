<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: {
        'my-navbar': Navbar
    }
}
</script>

<template>
    <div class="my-app">
        <section class="hero  is-link is-fullheight">
            <div class="hero-head">
                <my-navbar></my-navbar>
            </div>
       
                
                    <div class="hero-body columns">
                        <div class="column ">
                            First column
                        </div>
                        <div class="column">
                            Second column
                        </div>
                       
                    
             
            </div>
        </section>
    </div>



</template>
