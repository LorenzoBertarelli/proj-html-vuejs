<script>
    export default {
        name: "AppIcons",
        props: {
        twitterIcon: {
            type: String,
            required: true
        },
        instagramIcon: {
            type: String,
            required: true
        },
        facebookIcon: {
            type: String,
            required: true
        },
        linkedinIcon: {
            type: String,
            required: true
        }
    }}
</script>

<template>
  <div>
    <a href="twitterIcon"><i class="fa-brands fa-twitter"></i></a>
    <a href="facebookIcon"><i class="fa-brands fa-facebook-f"></i></a>
    <a href="instagramIcon"><i class="fa-brands fa-instagram"></i></a>
    <a href="linkedinIcon"><i class="fa-brands fa-linkedin"></i></a>
  </div>
</template>

<style lang="scss" scoped>
        a {
        text-decoration: none;
        color: rgb(95, 95, 95);
        padding: 10px;
    }
</style>