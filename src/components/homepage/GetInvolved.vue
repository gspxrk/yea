<template>
    <section class="get-involved" id="getInvolved">
       <!-- CONTACT MESSAGE -->
       <div class="get-involved__message">
         <h3>Do you have questions for us?</h3>
         <p>We would love to answer them! Feel free to reach out with any inquiries you may have.</p>
         <a href="/contact" class="contact-button">Contact Us</a>
       </div>
     </section>
 </template>
 
 <script>
 export default {
     name: 'GetInvolved'
 }
 </script>
 
 <style lang="scss" scoped>
 .get-involved {
     display: flex;
     justify-content: center;
     align-items: center;
     width: 100%;
     background: #f5f4f4;
     padding: 40px 0;
 }
 
 .get-involved__message {
     text-align: center;
     max-width: 600px;
     margin: 0 auto;
 
     h3 {
         font-size: 1.5rem;
         margin-bottom: 10px;
     }
 
     p {
         font-size: 1rem;
         margin-bottom: 20px;
     }
 
     .contact-button {
         background: #007bff;
         border-radius: 10px;
         color: white;
         font-size: 18px;
         text-decoration: none;
         padding: 10px 20px;
         transition: background 0.3s;
 
         &:hover {
             background: #0056b3;
         }
     }
 }
 </style>
