<template>
  <div id="info">
    <div class="container">
      <div class="row rowoverlay">
        <div class="col-sm">
          <p>Experience</p>
          <ul>
            <a target="_blank" href="CV 2021 Final.pdf"><li>cv</li></a>
            <a target="_blank" href="Resume_Aaron_Dishy_2021.pdf">
              <li>resume</li>
            </a>
          </ul>
        </div>
        <div class="col-sm">
          <p>Social</p>
          <ul>
            <!-- <a href="https://twitter.com/dI5Hy"><li>twitter</li></a> -->
            <a href="https://utoronto.academia.edu/AaronDishy"
              ><li>publications</li></a
            >
            <a href="https://www.are.na/aaron-dishy"
              ><li>research interests</li></a
            >
            <a href="https://www.librarything.com/profile/aarondishy"
              ><li>library</li></a
            >
          </ul>
        </div>
        <div class="col-sm" id="education">
          <p>Education</p>
          <ul>
            <li>
              Juris Doctor (J.D) (Expected)<br /><a
                href="https://www.osgoode.yorku.ca/"
                >Osgoode Hall Law School</a
              ><br />York University<br />(2020-2023)
            </li>
            <li>
              Master of Information (M.I)<br />Critical Information Policy
              Studies<br />Thesis Option<br /><a
                href="https://www.utoronto.ca/"
                >University of Toronto</a
              ><br />(2016 - 2018)
            </li>
            <li>
              Bachelor of Arts (B.A)<br />Art History & Religious Studies<br />(with
              distinction)<br /><a href="https://www.mcgill.ca/"
                >McGill University</a
              ><br />(2012 - 2016)
            </li>
          </ul>
        </div>
      </div>

      <div class="row">
        <div>
          <img src="../assets/computer.gif" alt="gif" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "aaron-info",
};
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
  left: 0;
  bottom: 0;
  right: 0;
  padding-left: 1.5%;
  height: 100%;
}
img {
  width: 40%;
  padding-left: 13%;
  padding-top: 10%;
}

ul {
  padding: 0 0 0 5%;
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
  ul {
    padding: 0 0 0 7%;
  }
}

@media only screen and (min-width: 760px) and (max-width: 780px) {
  ul {
    padding: 0 0 0 8%;
  }
  img {
    width:30%;
    padding-left: 10%;
    padding-top: 15%;
  }
}

@media only screen and (min-width: 1000px) and (max-width: 1100px) {
  ul {
    padding: 0 0 0 6.25%;
  }
  img {
    width:30%;
    padding-left: 10%;
    padding-top: 15%;
  }
 }
</style>
