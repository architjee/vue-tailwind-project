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
        <section class="hero  is-fullheight">
            <div class="hero-head">
               <my-navbar></my-navbar>
            </div>
            <div class="hero-body">
                <div class="custom-wrapper">
                    <p class="title">
                        About View Page
                    </p>
                    <p class="subtitle">
                        About view page subtitle.
                    </p>
                </div>

            </div>
        </section>
    </div>



</template>
