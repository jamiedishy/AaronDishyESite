<template>
  <div>
    <head>
        <link rel="icon" href="Mail.png" type="image/gif" sizes="16x16">
        <title>Aaron Dishy</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="author" content="Jamie Dishy">
    </head>

    <div class="container" id="nav">
        <div class="row">
            <div class="col-sm">
                <p >Aaron Dishy</p>
            </div>
            <div class="col-sm">
                <a href="mailto:hello@aarondishy.net">hello@aarondishy.net</a>
            </div>
            <div class="col-sm">
                <p id="nav-space">(514)-266-6428</p>
            </div>
        </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'aaron-header'
}
</script>

<style scoped>
a {
    color: black;
}
a:hover {
    color: grey;
    transition: 0.3s;
}
#nav {
    padding-top: 60px;
}
@media only screen and (max-width: 760px) {
    #nav {
        display: none;
    }
}
</style>
