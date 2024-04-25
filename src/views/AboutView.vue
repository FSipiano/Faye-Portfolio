<template>
  <div class="page">
   <div class="">
     <div class="">
       <div class="">
         <h2 class="">
           Let's work together to create your vision
         </h2>
         <p class="">
           I’d love to hear from you! Send me an email,
 <a class=""
            href="https://twitter.com/JavaScriptCoff1">
         a DM on Twitter,
         </a>
      or use the form below and
           I'll respond as soon as I can!
         </p>
 
         <p class="">Email me at:</p>
         <a class=""
         href="mailto:fayesipiano@outlook.com">
           fayesipiano@outlook.com
         </a>
 
         <form enctype=”multipart/form-data” action="https://formsubmit.co/fayesipiano@outlook.com" method="POST" class="">
           <div>
             <label for="first_name" class="">First name</label>
             <div class="">
               <input
               type="text"
               name="first_name" id="first_name"
               autocomplete="given-name" required autofocus
               class="">
             </div>
           </div>
           <div>
             <label for="last_name" class="required">Last name</label>
             <div class="">
               <input type="text" name="last_name" id="last_name" autocomplete="family-name" required
               class="i">
             </div>
           </div>
           <div class="">
             <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
             <div class="mt-1">
               <input id="email" name="email" type="email" required
               autocomplete="email"
               class="">
             </div>
           </div>
           <div class="">
             <label for="company" class="">Company</label>
             <div class="mt-1">
               <input
               type="text"
               name="company"
               id="company"
               autocomplete="organization" required
               class="">
             </div>
           </div>
           <div class="sm:col-span-2">
             <div class="">
               <label
               for="phone"
               class="">Phone</label>
               <span id="phone_description"
               class="">Optional</span>
             </div>
             <div class="">
               <input
               type="text"
               name="phone" id="phone"
               autocomplete="tel"
               aria-describedby="phone_description"
               class="">
             </div>
           </div>
           <div class="">
             <div class="f">
               <label
               for="how_can_we_help"
               required
               class="">What did you have in mind?
                 I can help you to design, develop and build, write, market and strategise
               </label>
               <span id="how_can_we_help_description" class="">Max. 500 characters</span>
             </div>
             <div class="mt-1">
               <textarea id="how_can_we_help"
               name="how_can_we_help"
               aria-describedby="how_can_we_help_description"
               rows="4"
               class=""></textarea>
             </div>
           </div>
           <div class="">
             <button
             type="submit"
             class="">
               Submit
             </button>
           </div>
         </form>
       </div>
     </div>
   </div>
 </div>
 </template>
 
 <script>
 export default {
   data(){
    return {
         title: 'Faye_Sipiano - Contact'
       }
     },
     head() {
       return {
         title: this.title,
         meta: [
           {
             hid: 'description',
             name: 'description',
             content: 'My custom description'
           }
         ]
       }
     }
 }
 </script>
 <style>
 .page {
   background-color: #edededce;
 }
 </style>