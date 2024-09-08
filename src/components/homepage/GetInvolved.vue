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
         background: #ffc22b; /* Matching background color */
         border-radius: 10px; /* Rounded corners */
         color: var(--dark)!important; /* Text color */
         font-style: normal; /* Normal font style */
         font-weight: bold; /* Bold text */
         font-size: 18px; /* Font size */
         line-height: 29px; /* Line height */
         text-align: center; /* Center text alignment */
         letter-spacing: 2px; /* Letter spacing */
         text-transform: uppercase; /* Uppercase text */
         display: flex; /* Flexbox layout */
         justify-content: center; /* Center content horizontally */
         align-items: center; /* Center content vertically */
         margin-top: 45px; /* Margin at the top */
         padding: 10px 30px; /* Padding inside the button */
         max-width: 80%; /* Maximum width of the button */
         transition: 300ms all ease-in-out; /* Smooth transition for hover effect */

         &:hover {
             padding: 10px 50px; /* Increase padding on hover */
         }
     }
 }
 </style>
