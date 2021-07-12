<template>
   <div></div>
</template>

<script>
export default {
    data() {
        return {
            title: 'Jonaflix',
            count: 1
        }
    },
    head() {
        return {
            title: this.title,
            link: [
                {rel: 'stylesheet', href: 'https://unpkg.com/tailwindcss/dist/tailwind.min.css'},
                {rel: 'stylesheet', href: 'https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css'}
            ],
            meta: [
                // hid is used as unique identifier. Do not use `vmid` for it as it will not work
                {
                    hid: 'description',
                    name: 'description',
                    content: 'Blog pessoal e opinativo sobre obras em geral da cultura pop.'
                },
                {
                    hid: 'author',
                    name: 'author',
                    content: 'Lucas Emanuel - https://github.com/Emanuellukas'
                }, {
                    hid: 'keywords',
                    name: 'keywords',
                    content: 'jonaflix, filmes, series, opnioes, entretenimento, cultura'
                }
            ]
        }
    }
}
</script>
