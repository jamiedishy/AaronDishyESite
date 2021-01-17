<template>
  <div>
    <div class="container">
      <div class="row">
        <div class="col">
          <div id="info">
            <p>Bio</p>
            <p>
              Aaron Dishy is a digital archivist, and student at Osgoode Hall
              Law School (2023) (expected), based in Toronto, Canada. He holds a
              Bachelor of Arts in art history and religious studies from McGill
              University (2016), as well as a Master of Information in critical
              information policy studies and archives and records management
              from the University of Toronto (2018). Aaron’s work centers new
              media policy, archives management, intellectual property law, and
              the implementation of information and communication technologies.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "aaron-bio",
};
</script>

<style>
#info {
  padding: 1% 0%;
}

#info a {
  color: black;
}

#info a:hover {
  color: grey;
  transition: 0.3s;
}
</style>
