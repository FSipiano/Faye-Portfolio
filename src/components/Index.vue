<script setup>
</script>

<template>
   <section class="page">
  <div class="container">
    <ContactButton class=""
          ></ContactButton>
          <h1 class="title">Faye_Sipiano</h1>

<h2 class="subtitle"> Freelance tech writer and front end developer
</h2>
<div class="links"> 
            <a
            href="https://dev.to/javascriptcoff1"
            target="_blank"
            rel="noopener noreferrer"
            class="button4"
          >
            Dev.to
</a>
          <a
            href="https://www.youtube.com/channel/UCQap2rd2RT364EyxJsx9GYw?view_as=subscriber"
            target="_blank"
            rel="noopener noreferrer"
            class="button4"
            >
              Youtube
          </a>
          <a
            href="https://github.com/FSipiano"
            target="_blank"
            rel="noopener noreferrer"
            class="button4"
          >
            GitHub
          </a>
          <a
            href="https://twitter.com/techwritecoffee"
            target="_blank"
            rel="noopener noreferrer"
            class="button4"
          >
              Twitter
          </a>
        </div>
        <div class="">
          <img :src="'src/components/icons/profileImage.jpg'"
          height="400px"
          width="300px"
          
        >
        </div>
        <div class="container">
        <p class="paragraph">
          Hi, I'm Faye.
        </p>
        <p class="paragraph">I love learning about coding and writing about what I have learned.
          I also ride horses, enjoy roadtrips and cooking. 
          I have written copy for multiple
          industries, including Finance, NFT gaming, Science, Education and Transport, and have prepared winning submissions for awards in FinTech 
          as well as funding applications for tech start-ups.
        </p> 
        <p class="paragraph">
          I specialise in explaining difficult technological concepts in a way that everyone can understand.
          I also maintain an Open Source 
          <a class = "underline text-indigo-700"
          href= "https://github.com/FSipiano/newbieDictionary">
          Newbie Dictionary
          </a>
          on GitHub that aims to give newcomers a helping hand through the overwhelming jargon in this industry.
        </p>
        <BlogCardContainer>
      </BlogCardContainer>
        </div>
        <div class="button4">
          <ContactButton
          ></ContactButton>
        </div>
  </div>
</section>
</template>

<style>
@media
 (max-width: none) { 
   .container { 
     max-width: none}
     }

.container { max-width: 100% }

.page {
  background-color: #edededce;
}

.container {
  margin: 10 auto;
  min-height: 100vh;
  display: grid;
align-items: center;
  text-align: center;
}

.links {
  margin:10 0.5em 0.5em 2;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  align-items: top;
  justify-content: center;
  font-weight: 400px;
  font-size: 48px;
  color: #35495e;
  letter-spacing: 2px;
}

.subtitle {
  font-size: 32px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  justify-self: center;
  align-items: center;
}

a.button4 {
display:inline-block;
padding:0.3em 1.2em;
margin:0 0.5em 0.5em 2;
border:0.16em solid rgba(75, 132, 134, 0.277);
border-radius:2em;
box-sizing: border-box;
text-decoration:none;
font-family:'Roboto',sans-serif;
font-weight:300;
color:#283991;
text-shadow: 0 0.04em 0.04em rgba(0,0,0,0.35);
text-align:center;
transition: all 0.2s;
}
a.button4:hover
{
border-color: rgb(202, 2, 2);
}
@media all and (max-width:30em)
{
a.button4
{
display:block;
margin:0.2em auto;
color: #283991;
}
}

.paragraph {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  padding: 5em 5em;
  align-items: center;
  text-align: center;
  justify-content: center;
  font-size: 20px;
  color: #242424;
}

.profile {
  border-radius: 5%;
  display: grid;
  max-height: 400;
  max-width: 350;
  margin-left: auto;
  margin-right: auto;
  width: 35%;
}
</style>