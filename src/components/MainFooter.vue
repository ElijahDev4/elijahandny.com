<template>
  <div id="footer">
    <section id="footer">
      <div class="container">
        <div
          class="row text-center text-xs-center text-sm-left text-md-left"
        ></div>
        <div class="row">
          <div class="col-xs-12 col-sm-12 col-md-12 mt-2 mt-sm-5">
            <ul class="list-unstyled list-inline social text-center">
              <li class="list-inline-item">
                <a href="https://github.com/ElijahDev4"
                  ><i class="fa fa-github"></i
                ></a>
              </li>
              <li class="list-inline-item">
                <a href="https://www.linkedin.com/in/ElijahDev"
                  ><i class="fa fa-linkedin"></i
                ></a>
              </li>
            </ul>
          </div>
          <hr />
        </div>
        <div class="row">
          <div
            class="col-xs-12 col-sm-12 col-md-12 mt-2 mt-sm-2 text-center text-white"
          >
            <p class="h6">Elijahdev4@gmail.com <br /></p>
          </div>
          <hr />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "MainFooter"
};
</script>

<style scoped>
@import url("https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css");
section {
  padding: 20px 0;
}
#footer {
  background: #007b5e !important;
}
#footer a {
  color: #ffffff;
  text-decoration: none !important;
  background-color: transparent;
}
#footer ul.social li a i {
  margin-right: 5px;
  font-size: 25px;
  -webkit-transition: 0.2s all ease;
  -moz-transition: 0.2s all ease;
  transition: 0.2s all ease;
}
#footer ul.social li:hover a i {
  font-size: 30px;
  margin-top: -10px;
}
#footer ul.social li a {
  color: #ffffff;
}
#footer ul.social li a:hover {
  color: #eeeeee;
}
</style>
