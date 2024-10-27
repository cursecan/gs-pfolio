<script>
export default {
    props: ['title']
}
</script>


<template>
    <div class="flex">
        <div class="relative text-5xl font-semibold">
            <div class="text-xl font-normal text-gray-600 text-right">
                {{ title }}
            </div>
            <div class="uppercase">
                <slot />
            </div>
            <div class="absolute bottom-0 left-0 right-0 h-4 bg-yellow-300 translate-x-2"></div>
            <div class="uppercase bottom-0 left-0 absolute">
                <slot />
            </div>
        </div>
    </div>
</template>