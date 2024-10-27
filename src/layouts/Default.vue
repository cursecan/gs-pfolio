<template>
    <div class="">
        <div class="container mx-auto min-h-screen bg-white my-32 drop-shadow-2xl">
            <slot />
        </div>
    </div>
</template>

<static-query>
query {
    metadata {
        siteName
    }
}
</static-query>
