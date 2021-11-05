<template>
  <div id="app" class="container">
    <form>
    <div class="row py-4">
      <style="display: flex;">
    <div id="u" style="display: flex;">


<div id="a">
      <h4>RESUME<hr style=”height:3px;background:#00f;color:#f00;”></h4>
    <h1>Ahmad<br /> Alfi</h1>
     <h2>Graphic Artist<hr /></h2>
    <img src="ags.jpg" height="300px" width="400px" border="radius:100%"/>

<div id="b">
        <h3>PROFILE</h3>
        <div style=”border-bottom:3px dashed #00f;”></div>
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a1 }}</h5><br />
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a2 }}</h5><br />
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a3 }}</h5><br />
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a4 }}</h5><br />
        <h3>{{ user.b1 }}</h3>
        <div style=”border-bottom:3px dashed #00f;”></div>
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a5 }}</h5><br />
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a6 }}</h5><br />
        <h3>{{ user.b1 }}</h3>
        <div style=”border-bottom:3px dashed #00f;”></div>
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a7 }}</h5>
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a8 }}</h5>
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a9 }}</h5>
        <h3>{{ user.b1 }}</h3>
        <div style=”border-bottom:3px dashed #00f;”></div>
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a10 }}</h5>
        <h4>{{ user.b1 }}</h4>
        <h5>{{ user.a11 }}</h5>
         </div>
    </div>


<div id="c" style="display: flex;">
        <div id="d">
        <h3>WORK EXPERIENCE</h3>
        <div style=”border-bottom:3px dotted #00f;”></div>
        <h4>Creative Rooms</h4>
        <h5>Feb 2013-Jun 2014</h5><br />
        <h4>Creative Rooms</h4>
        <h5>Feb 2013-Jun 2014</h5><br />
        <h4>Creative Rooms</h4>
        <h5>Feb 2013-Jun 2014</h5><br />
</div>
<div id="h">
          <h4>Senior Art Director</h4>
          <h5>{{ user.b15 }}<br /> rhoncus sem qravida et.</h5>
          
          <h4>Senior Art Director</h4>
          <h5>{{ user.b15 }}<br /> rhoncus sem qravida et.</h5>
          
          <h4>Senior Art Director</h4>
          <h5>{{ user.b15 }}<br /> rhoncus sem qravida et.</h5>
          </div>
          </div>


<div id="i" style="display: flex;">
<div id="j">
        <h3>EDUCATION</h3>
        <div style=”border-bottom:3px dotted #00f;”></div>
        <h4>Master Degree</h4>
        <h5>Feb 2011-Jun 2014</h5>
        <h4>Master Degree</h4>
        <h5>Feb 2011-Jun 2014</h5>
        <h4>Master Degree</h4>
        <h5>Feb 2011-Jun 2014</h5>
        </div>
<div id="k">
          <h4>University Of Creative Minds</h4>
          <h5>Jakarta, Indonesia.</h5>
          
          <h4>University Of Creative Minds</h4>
          <h5>Jakarta, Indonesia.</h5>
          
          <h4>University Of Creative Minds</h4>
          <h5>Jakarta, Indonesia.</h5>
          </div>
          </div>


<div id="l" style="display: flex;">
<div id="m">
        <h3>SKILLS</h3>
        <div style=”border-bottom:3px dotted #00f;”></div>
        <h4>{{ user.c1 }}</h4>
        <h5>{{ user.c2 }}</h5><br />
        <h5>{{ user.c3 }}</h5><br />
        <h5>{{ user.c4 }}</h5><br />
        <h5>{{ user.c5 }}</h5><br />
        <h5>{{ user.c6 }}</h5><br />
        <h5>{{ user.c7 }}</h5><br />
</div>
<div id="n">
          <h4>{{ user.c8 }}</h4>
          <h5>{{ user.c9 }}</h5><br />
          <h5>{{ user.c10 }}</h5><br />
          <h5>{{ user.c11 }}</h5><br />
          <h5>{{ user.c12 }}</h5><br />
          <h5>{{ user.c13 }}</h5><br />
          <h5>{{ user.c }}</h5><br />
</div>
</div>
</div>
</div>
      <agenda-inpt />
      <agenda-shw />
    </div>
    </form>
  </div>
</template>
<script>
export default {
  nama: "AgendaShw",
  computed: {
    agenda() {
      return this.$store.state.listAgenda;
    },
  },
};
</script>