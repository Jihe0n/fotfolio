<template>
  <div class="about">


<!-- <h1 contenteditable data-heading="Create.">Create.</h1> -->

<section class="section section--about" id="about">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 10" preserveAspectRatio="none">
        <polygon points="100 0 100 10 0 10" />
    </svg>


  <div class="section1">
<div class="woman">
</div>

<div class="content">
	<h2>About me</h2>

    <div class="section__inner">
        <div class="block">
            <h3 class="h3_left">私は私の仕事が好きです。</h3>
            <h3> 好きだから楽しむようになり、もっと上手になりたくなります。</h3>
            <h3>ユーザーの立場で考えることが好きで、ずっと悩み、より良い方</h3>
            <h3>向性について人々と話し合い、ユーザーの記憶に残るようにする</h3>
            <h3 class="h3_left">ことが私の仕事です。</h3>

            <br>
            <h3>好きな仕事を楽しみながらできること、私が夢見る私の姿です。</h3>
        </div>
    </div>  



</div>
</div>






<!-- 
    <div class="section__inner">
        <div class="block">
            <a class="pre" href="#about"><span>#2</span>Building</a>
            <h2>Volker works for companies and agencies, creating responsive web applications.</h2>
            <p class="lead">Building the right foundation to ongoing optimization and support. In short, he tries to make the web a better place.</p>
        </div>
    </div> -->

</section>




  </div>
</template>

<script>

// import PictureView from '@/components/pictureView.vue';


export default {
  components: {
    
  },
  data(){
    return{
     isModalViewed: false,
 
    }
  },
  methods: {
    openModa(){
      this.isModalViewed = true;
    }
  }
}
</script>

<style scoped>


 body {
   position: sticky
 }

 @media (min-width: 6.25em) {
    html {
      font-size: 17px;
    }
  }
  
  @media (min-width: 12.5em) {
    html {
      font-size: 18px;
    }
  }
  
  @media (min-width: 18.75em) {
    html {
      font-size: 19px;
    }
  }
  
  @media (min-width: 25em) {
    html {
      font-size: 20px;
    }
  }
  
  @media (min-width: 31.25em) {
    html {
      font-size: 21px;
    }
  }
  
  @media (min-width: 37.5em) {
    html {
      font-size: 22px;
    }
  }
  
  @media (min-width: 43.75em) {
    html {
      font-size: 23px;
    }
  }
  
  @media (min-width: 50em) {
    html {
      font-size: 24px;
    }
  }
  
  @media (min-width: 56.25em) {
    html {
      font-size: 25px;
    }
  }
  
  @media (min-width: 62.5em) {
    html {
      font-size: 26px;
    }
  }
  
  @media (min-width: 68.75em) {
    html {
      font-size: 27px;
    }
  }
  
  @media (min-width: 75em) {
    html {
      font-size: 28px;
    }
  }
  
  @media (min-width: 81.25em) {
    html {
      font-size: 29px;
    }
  }
  
  @media (min-width: 87.5em) {
    html {
      font-size: 30px;
    }
  }
  
  @media (min-width: 93.75em) {
    html {
      font-size: 31px;
    }
  }
  
  @media (min-width: 100em) {
    html {
      font-size: 32px;
    }
  }
  
  @media (min-width: 106.25em) {
    html {
      font-size: 33px;
    }
  }
  
  @media (min-width: 112.5em) {
    html {
      font-size: 34px;
    }
  }
  
  @media (min-width: 118.75em) {
    html {
      font-size: 35px;
    }
  }
  
  @media (min-width: 125em) {
    html {
      font-size: 36px;
    }
  }
  
  *, *::before, *::after {
    -webkit-box-sizing: inherit;
            box-sizing: inherit;
    margin: 0;
    padding: 0;
  }
  
  a {
    text-decoration: none;
  }
  
  /**
   * The fixed Side 
   */
  .side {
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    z-index: 1000;
    width: 50px;
    border-right: 1px dashed rgba(0, 0, 0, 0.3);
    color: rgba(0, 0, 0, 0.5);
    font-family: "nimbus-sans", sans-serif;
    text-transform: uppercase;
    letter-spacing: .0875rem;
    font-size: 10px;
    -webkit-transition: all 0.3s cubic-bezier(0.05, 0.69, 0.14, 1);
    transition: all 0.3s cubic-bezier(0.05, 0.69, 0.14, 1);
  }
  
  .side:hover {
    color: rgba(0, 0, 0, 0.5);
  }
  
  .side .side__inner {
    position: relative;
    height: 100%;
    white-space: nowrap;
  }
  
  .side a {
    color: inherit;
    word-spacing: 0;
    -webkit-transition: all 0.3s cubic-bezier(0.05, 0.69, 0.14, 1);
    transition: all 0.3s cubic-bezier(0.05, 0.69, 0.14, 1);
  }
  
  .side .top,
  .side .bottom {
    position: absolute;
    left: 0;
    -webkit-transform: rotate(-90deg) perspective(1px);
            transform: rotate(-90deg) perspective(1px);
    -webkit-transform-origin: 50px 50px;
            transform-origin: 50px 50px;
    height: 50px;
    line-height: 50px;
    white-space: nowrap;
    word-spacing: .5rem;
  }
  
  .side .top {
    top: 25px;
    text-align: right;
    color: black;
  }
  
  .side .bottom {
    top: auto;
    bottom: 75px;
  }
  
  .side .bottom:hover a {
    color: rgba(0, 0, 0, 0.2);
  }
  
  .side .bottom:hover a:hover {
    color: rgba(0, 0, 0, 0.8);
  }
  
  /**
   * The first navigation
   */
  .anchornav {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  
  .anchornav li {
    display: block;
  }
  
  .anchornav li::after {
    content: '';
    width: 1.3rem;
    display: block;
    height: 2px;
    background: black;
  }
  
  .anchornav li:last-child::after {
    display: none;
  }
  
  .anchornav a {
    display: block;
    padding: 1em 0;
    font-family: "nimbus-sans", sans-serif;
    text-transform: uppercase;
    font-size: 12px;
    letter-spacing: 1.4px;
    color: inherit;
    -webkit-transition: all 0.3s cubic-bezier(0.05, 0.69, 0.14, 1);
    transition: all 0.3s cubic-bezier(0.05, 0.69, 0.14, 1);
  }
  
  .anchornav a span {
    display: inline;
    padding: .5em 0 0;
    opacity: .3;
    letter-spacing: normal;
    font-family: "ff-meta-serif-web-pro", serif;
    text-transform: none;
  }
  
  .anchornav a:hover {
    color: #de5f5f;
  }
  
  .anchornav a:hover span {
    opacity: 1;
    color: #181818;
  }
  
  /**
   * The different sections
   */
  .section {
    position: relative;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
        -ms-flex-flow: column nowrap;
            flex-flow: column nowrap;
    -webkit-box-align: stretch;
        -ms-flex-align: stretch;
            align-items: stretch;
    min-height: 60vh;
    width: 100%;
    margin-top: 3%;
    -ms-flex-line-pack: center;
        align-content: center;
    padding: 20vh 50px 20vh 75px;
  }
  
  .section svg {
    position: absolute;
    top: -50px;
    left: 0;
    right: 0;
    width: 100%;
    height: 50px;
  }
  
  .section svg.bottom {
    bottom: 0;
    top: auto;
    fill: grey;
  }
  
  .section .section__inner {
    height: 100%;
    max-width: 800px;
    margin: auto auto auto 0;
  }
  
  .section.section--hello {
    background-color: #FDEF52;
    color: #181818;
  }
  
  .section.section--intro {
    background-color: white;
    color: #555;
  }
  
  .section.section--about {
    padding-top: 30px;
    background-color: #de5f5f;
    color: white;
  }
  
  .section.section--about svg {
    fill: #de5f5f;
  }
  
  .section.section--clients {
    background-color: #343436;
    color: white;
  }
  
  .section.section--clients svg {
    fill: #343436;
  }
  
  .section.section--portfolio {
    background-color: orange;
    color: white;
  }
  
  .section.section--portfolio svg {
    top: -20px;
    fill: orange;
  }
  
  .section.section--portfolio svg.bottom {
    top: auto;
    bottom: -50px;
  }
  
  .section.section--portfolio1 {
    background-color: #3A99D8;
    color: white;
  }
  
  .section.section--portfolio1 svg {
    top: -50px;
    fill: #3A99D8;
  }
  
  .section.section--pepperhill svg {
    top: -50px;
    fill: #3A99D8;
  }
  
  .section.section--contact svg {
    fill: white;
  }
  
  /**
   * Typo
   */
  h1, .h1, h2, .h2, h3, .h3, h4, .h5 {
    font-family: "nimbus-sans", sans-serif;
    font-weight: bold;
    margin: 0 0 1em;
    line-height: 1;
    letter-spacing: -1px;
  }
  
  @media (min-width: 30rem) {
    h1, .h1, h2, .h2, h3, .h3, h4, .h5 {
      letter-spacing: -2px;
    }
  }
  
  h1 a, .h1 a, h2 a, .h2 a, h3 a, .h3 a, h4 a, .h5 a {
    color: inherit;
  }
  
  h1 a:hover, .h1 a:hover, h2 a:hover, .h2 a:hover, h3 a:hover, .h3 a:hover, h4 a:hover, .h5 a:hover {
    border-bottom: .1875rem solid;
  }
  
  h1 span, .h1 span, h2 span, .h2 span, h3 span, .h3 span, h4 span, .h5 span {
    color: #de5f5f;
  }
  
  h1, .h1 {
    font-size: 1.2rem;
  }
  
  @media (min-width: 30rem) {
    h1, .h1 {
      font-size: 2.5rem;
    }
  }
  
  h2, .h2 {
    font-size: 1.2rem;
  }
    h3, .h3 {
    font-size: 1.25rem;
 
    
  }
  
  @media (min-width: 30rem) {
    h2, .h2 {
      font-size: 2.5rem;
    }
  }
  
  .pre {
    display: inline-block;
    font-size: 12px;
    margin: 0;
    opacity: .8;
    letter-spacing: 1.4px;
    word-spacing: .2rem;
    text-transform: uppercase;
    margin-bottom: 1em;
    color: inherit;
  }
  
  .pre span {
    font-size: .9em;
    margin-right: .4em;
    opacity: .5;
  }
  
  .pre:hover {
    opacity: 1;
  }
  
  p {
    font-size: .75rem;
    line-height: 1.4;
  }
  
  @media (min-width: 30rem) {
    p {
      font-size: .875rem;
    }
  }
  
  p a {
    font-weight: bold;
    color: inherit;
  }
  
  p a:hover {
    border-bottom: .1875rem solid;
  }
  
  .lead {
    display: block;
    font-size: .875rem;
    margin: 0;
  }
  
  @media (min-width: 30rem) {
    .lead {
      font-size: 1rem;
    }
  }
  
  .portfolio {
    font-size: .75rem;
  }
  
  .portfolio.block {
    display: inline-block;
    width: 100%;
  }
  
  @media (min-width: 30rem) {
    .portfolio.block {
      width: 30%;
    }
  }
  
  .portfolio .link {
    display: block;
    margin: 2em 0 0 0;
    color: #555;
    letter-spacing: 2px;
    font-size: 12px;
  }
  
  .portfolio p {
    font-size: inherit;
    color: #343436;
    opacity: .7;
  }
  




.woman {
  /* position: relative; */
  margin: 0 auto;
  margin-right: 40%;
  background: url('../assets/man3.png') no-repeat center center;
  height: 494px;
  width: 218px;
  z-index: 2;
}

@media screen and (min-width: 786px) {
  .woman {
    /* background-size: 300px 680px; */
    height: 600px;
    width: 500px;
  }
}

.content {
  max-width: 90%;
  /* position: relative; */
  font-family: 'Playfair Display', serif;
  margin: 0 auto;
  padding-bottom: 20px;
}

@media screen and (min-width: 600px) {
  .content {
    left: 60%;
    max-width: 550px;
    width: 35%;
    top: 10%;
    position: absolute;
  }
}

.content:before {
  content: "";
  height: 10px;
  background: #000;
  width: 60%;
  position: absolute;
  top: -1.5rem;
}

.h3_left{
  text-align: left;
}





</style>