<script>
    import HomepageComponent from '@/components/homepage.vue';
    import NotFound from '../components/notfound.vue'
    import { createRouter } from 'vue-router';

    const routes = [
        { path: '*', component:NotFound },
        { path: '/', component: HomepageComponent },
        
    ]
    export const router = createRouter({routes});

</script>
