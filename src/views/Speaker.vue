<template>
    <div>
        <div class="body-overlay"></div>

        <!-- Document Wrapper
        ============================================= -->
        <div id="wrapper" class="clearfix">

            <Header></Header>
            <ComingSoon></ComingSoon>
            <Footer></Footer>

        </div><!-- #wrapper end -->
    </div>
</template>

<script>
import Header from './Header.vue'
import Footer from './Footer.vue'
import ComingSoon from '../components/ComingSoon.vue'
export default {
    components: { Header, Footer, ComingSoon }
}
</script>