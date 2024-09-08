<template>
    <section class="creative-collaborations" id="creativeCollaborations">
       <!-- CREATIVE COLLABORATORS -->
       <div class="creative-collaborations__column">
         <div class="badge">Join Us</div>
         <div class="column-title">
           <h3>Creative Collaborators</h3>
         </div>
         <div class="column-information">
           <ul>
             <li><strong>Collaborate</strong> on art and design projects</li>
             <li><strong>Participate</strong> in community challenges and contests</li>
             <li><strong>Showcase</strong> your work in Apsara exhibitions</li>
             <li><strong>Join</strong> workshops and creative meetups</li>
           </ul>
         </div>
         <div class="column-button">
           <a href="/collaboration-form">Get Involved</a>
         </div>
       </div>
 
       <!-- INSPIRATIONAL IMAGE -->
       <div class="creative-collaborations__column inspiration">
         <img src="../../assets/images/inspiration.png" alt="A vibrant collection of artworks and creative projects">
         <br>
       </div>
 
       <!-- COMMUNITY LEADERS -->
       <div class="creative-collaborations__column">
         <div class="badge">Lead the Way</div>
         <div class="column-title">
           <h3>Community Leaders</h3>
         </div>
         <div class="column-information">
           <ul>
             <li><strong>Lead</strong> creative workshops and webinars</li>
             <li><strong>Mentor</strong> emerging artists and creators</li>
             <li><strong>Organize</strong> community-driven art events</li>
             <li><strong>Innovate</strong> with new artistic techniques and tools</li>
           </ul>
         </div>
         <div class="column-button">
           <a href="/leadership-form">Become a Leader</a>
         </div>
       </div>
     </section>
 </template>
 
 <script>
 export default {
     name: 'CreativeCollaborations'
 }
 </script>
 
 <style lang="scss" scoped>
 .inspiration {
    display: flex;
    align-items: center;
    justify-content: center;

      img {
        width: 250px;
        height: auto;
      }

        @media (max-width: 600px) {
          img {
              width: 80%;
          }
        }
  }
     .creative-collaborations {
         display: flex;
         justify-content: space-evenly;
         align-items: center;
         min-height: 900px;
         width: 100%;
         flex-wrap: wrap;
         background: #f5f4f4;
     }
 
     .creative-collaborations__column {
         max-width: 400px;
     }
 
     .badge {
         background: #ffc22b;
         border-radius: 6px;
         font-style: normal;
         font-weight: bold;
         font-size: 14px;
         line-height: 25px;
         letter-spacing: 0.2em;
         color: var(--dark);
         width: 150px;
         height: 24px;
         display: flex;
         justify-content: center;
         position: relative;
         left: 220px;
         margin-bottom: 30px;
     }
 
     .column-title h3 {
         font-style: normal;
         font-weight: 600;
         font-size: 17px;
         line-height: 25px;
         letter-spacing: 0.2em;
         color: #21243d;
         text-transform: uppercase;
         text-align: center;
         margin-bottom: 40px;
     }
 
 .column-information {
     display: flex;
     justify-content: center;
     align-items: center;
 
     li {
         list-style: none;
         margin: 10px;
         text-align: center;
     }
 }
 
 .column-button {
     display: flex;
     justify-content: center;
     align-items: center;
 
     a {
        background: #ff3e3e;
        border-radius: 10px;
        color: white;
        font-style: normal;
        font-weight: bold;
        font-size: 20px;
        line-height: 29px;
        text-align: center;
        letter-spacing: 2px;
        text-transform: uppercase;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 15px;
        padding: 10px 20%;
        transition: 300ms all ease-in-out;
     }
 }
 
 @media (max-width: 980px) {
     .creative-collaborations__column {
         margin-top: 50px;
         margin-bottom: 50px;
 
         img {
             width: 80%;
         }
     }
 
     .badge {
         position: relative;
         left: 20px;
     }
 
     .column-button {
         a {
          width: 80%   
         }
     }
 
     .column-information {
         ul {
             margin-block-start: 0;
             padding-inline-start: 0;
         }
     }
 }
 </style>
