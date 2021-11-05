<template>
<tbody>
<style="display: flex;" class="app" v-for="user in users" :key="user">
    <div id="u" style="display: flex;"> 
    <div id="a">
    <h2>Ahmad Alfi<br>Ramadhani</br></h2>
    <img src="ags.jpg" height="300px" width="400px"/>
    <div id="b">
        <h3>Contact</h3>
        <hr />
        <h4>Address:</h4>
        <h5>Jl-Majapahit-01,Mranggen,Demak</h5><br />
        <h4>Phone:</h4>
        <h5>(+62)8816705835</h5><br />
        <h4>Email:</h4>
        <h5>ahmadalfi007@gmail.com</h5><br />
        <h4>Linkedin:</h4>
        <h5>Linkedin.com/ahmad/jco</h5><br />
        <h3>Languages</h3>
        <hr />
        <h5>Jowo+A1</h5>
        <h5>Indonesia-A2</h5><br />
        <h3>Hobbies</h3><hr />
        <ul>
            
                <li>Sepakbola</li>
                <li>Futsal</li>
                <li>Turing</li>
                <li>Adventure</li>
            
        </ul>
        </div>
    </div>
    <div id="c">
        <div id="d">
        <h3>Summary</h3>
        <hr />
        <h5>Senior WEB Developer specializing in fron end Development,Exsperientced with all stages of the Development cycle for dynamic WEB projects. Well-versed in numerous programming languages including HTML5, PHP OOP, JavaScript, CSS, MySQL. Strong background in project management and customer relation.</h5><br />
        <h3>Skill Highlights</h3><hr />
        <ul  style="display: flex;">
            <div id="lol">
                <li>Project management</li>
                <li>Strong Decision maker</li>
                <li>Complex problem solver</li>
                </div>
                <div id="lil">
                <li>Creative Design</li>
                <li>Innovative</li>
                <li>Service-Focused</li>
                </div>
            
        </ul>
        
        <h3>Experience</h3> 
            <hr> 
            <b>Web Develover</b> - 09/2015 to 05/2019 <br> 
            <b>Luna Web Design</b>, New York 
            <ul> 
                <li>Cooperate With designers to create clean interfaces and <br />simple, intuitive interactions and 
                    experience. 
                </li> 
                <li>Develop project concepts and maintain optimal<br /> workflow.</li> 
                <li>Work whit senior developer to manage large, complex <br />design project for corporate clients.</li> 
                <li>Complete detailed programming and development tasks<br /> for front end public and internal websites as 
                    well 
                    as challenging back and server code.</li> 
                <li>carry out quality assurance tests to discover errors and<br /> optimize usability.</li> 
            </ul> 
            <h3>Education</h3> 
            <hr> 
            Bachelor of science: <b>Computer information System - 2014 <br />Columbia University</b>, NY 
            <h3>Certifications</h3> 
            <hr> 
            <p>PHP framework (certificate): <b>Zend, Codeigniter, Symfony.</b> Programming languages: <b> HTML5, PHP 
                    OOP, 
                    JavaScript, CSS, MySQL</b></p></div>
    </div>
    </div>
    </tbody>
</template>
<script>
export default {
  name: "AgendaInpt",
  computed: {
    isLoading() {
      return this.$store.state.isLoading;

    },
  }
  }
</script>