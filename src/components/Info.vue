<template>
  <div id="info">

    <div class="container">
        <div class="row rowoverlay">
            <div class="col-sm">
                <p>Experience</p>
                <ul>
                    <a href="#"><li>cv</li></a>
                    <a href="#"><li>resume</li></a>
                </ul>
            </div>
            <div class="col-sm">
                <p>Social</p>
                <ul>
                    <!-- <a href="https://twitter.com/dI5Hy"><li>twitter</li></a> -->
                    <a href="https://utoronto.academia.edu/AaronDishy"><li>publications</li></a>
                    <a href="https://www.are.na/aaron-dishy"><li>research interests</li></a>
                    <a href="https://www.librarything.com/profile/aarondishy"><li>library</li></a>
                </ul>
            </div>
            <div class="col-sm" id="education">
                <p>Education</p>
                <ul>
                    <li>Bachelor of Arts (B.A)<br>Communications & Art History<br>(with distinction)<br><a href="https://www.mcgill.ca/">McGill University</a><br>(2012 - 2016)</li>
                    <li>Master of Information (M.I)<br>Critical Information Policy Studies<br>Archives & Records<br><a href="https://www.utoronto.ca/">University of Toronto</a><br>(2016 - 2018)</li>
                </ul>
            </div>
        </div>
        
        <div class="row ">
            <div >
                <img src="../assets/computer.gif" alt="gif">
            </div>
        </div>

    </div>

  </div>
</template>

<script>
export default {
  name: 'aaron-info'
}
</script>

<style scoped>
.container {
    position: relative;
}
a {
    color: black;
}
a:hover {
    color: grey;
    transition: 0.3s;
}
.rowoverlay {
    position: absolute;
    top: 0;
    left:0;
    bottom:0;
    right:0;
    padding-left: 1.5%;
    height:100%; 
}
img {   
    width: 40%;
    padding-left: 13%;
    padding-top: 10%;
}
@media only screen and (max-width: 760px) {
    img {
        display: none;
    }
    #info {
        padding-left: 5%;
    }
    #education {
        padding-bottom: 8%;
    }
}

</style>
