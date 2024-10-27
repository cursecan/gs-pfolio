<template>
    <Layout>
        <div class="flex h-screen overflow-hidden relative">
            <div class="bg-black max-w-xl w-full text-white text-2xl text-center">
                <div class="uppercase py-6 font-bold tracking-wider">Portofolio</div>
            </div>
            <div class="flex-1">
                <div class="bg-neutral-500 text-white h-20 flex items-center px-6 gap-10 uppercase font-semibold justify-center">
                    <div class="">Home</div>
                    <div class="">About</div>
                    <div class="">Work</div>
                    <div class="">Blog</div>
                    <div class="">Contact</div>
                </div>
                <div class="">
                    <img class="w-full h-full" src="https://images.pexels.com/photos/7143854/pexels-photo-7143854.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
                </div>
            </div>
            <div class="absolute text-white flex inset-0 items-end justify-center">
                <div class="max-w-6xl w-full uppercase text-6xl tracking-wider mb-40">
                    <div class="text-3xl mb-2">Hello, My name</div>
                    <div class="text-6xl font-semibold">Anderi Setiawan</div>
                    <div class="flex mt-10">
                        <div class="bg-yellow-300 font-semibold text-black text-3xl px-6 py-3">
                            i'm Web Developer
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- About -->
         <AboutMe />
    </Layout>
</template>

<script>
import AboutMe from '../components/AboutMe.vue';
export default {
    metaInfo: {
        title: 'Hello, world!'
    },
    components: {
        AboutMe
    }
}
</script>