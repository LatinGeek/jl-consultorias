<template>
    <div
        style="margin-bottom:1em; height: 600px; width: 300px; background-color: white; border: solid; overflow: hidden; text-overflow: ellipsis;">
        <div style="background-color: gray;">
            <img v-bind:src=imageSrc style="height: 300px;" />
        </div>
        <div class="container" style="padding-top: 1em; overflow: hidden; height: 300px;">
            <p style="font-size: medium;"><b>{{ title }}</b></p>
            <div style="display: -webkit-box;-webkit-line-clamp: 9;-webkit-box-orient: vertical;overflow: hidden;text-overflow: ellipsis;">
                {{ desc }}
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'linkedin-post',
    props: {
        imageSrc: String,
        title: String,
        desc: String
    }
}
</script>