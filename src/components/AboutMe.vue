<script>
import PostImage from './PostImage.vue';
import TitleHeader from './TitleHeader.vue';

export default {
    components: {
        TitleHeader,
        PostImage
    }
}
</script>


<template>
    <div class="bg-gray-100">
        <div class="max-w-6xl mx-auto py-32 flex items-top gap-16">
            <PostImage>
                <img src="https://images.pexels.com/photos/7143854/pexels-photo-7143854.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="h-full w-full" alt="">
            </PostImage>
            <div class="flex-1">
                <TitleHeader :title="`About Me`">
                    Hello
                </TitleHeader>
                <p class="text-xl mt-10">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur, ut.
                </p>
            </div>
        </div>
    </div>
</template>