<template>
    <section class="about-us-wrapper">
      <div class="about-us-content column">
            <div class="about-us__image">
                <img src="https://www.hindustanpencils.com/wp-content/uploads/2024/01/apsara-logo-200x60-1.png" alt="Apsara Logo | A butterfly with a blue and a purple wing">
            </div>

            <div class="about-us__text column">
                <p>
                    At Apsara, we’re passionate about inspiring creativity and enhancing learning. Our goal is to empower students, artists, and professionals with the tools and resources they need to bring their ideas to life.
                </p>

                <p>
                    Since our inception, we’ve been dedicated to providing high-quality stationery products that foster imagination and innovation. <br>
                    Whether you're a student preparing for exams or an artist working on your next masterpiece, we are here to support you.
                </p>

                <p> 
                    Led by a team of creative enthusiasts and industry experts, Apsara is committed to excellence and continuous improvement in everything we do. We are always eager to hear from our community and explore new ways to inspire and support our users.
                </p>

                <p> 
                    If you'd like to collaborate with us, or if you have any questions or feedback, we would love to hear from you!
                </p>
            </div>
        </div>
    </section>

    <section class="about-us-content faq">
        <div class="about-us__text column">
            <h2>FAQ</h2>
            <details>
                <summary> <strong>Q:</strong> What products does Apsara offer?</summary>
                    <div class="about-us_faq_answers">
                        <strong>Answer: </strong>
                        
                        <p> We offer a wide range of stationery products, including pencils, erasers, notebooks, and art supplies. Our products are designed to cater to the needs of students, professionals, and artists.</p>
                    </div>
            </details>

            <details>
                <summary> <strong>Q:</strong> Where can I purchase Apsara products?</summary>
                    <div class="about-us_faq_answers">
                        <strong>Answer: </strong>

                        <p> Apsara products are available at major retailers, bookstores, and online. Visit our website to find a store near you or shop directly from our online store.</p>
                    </div>
            </details>

            <details>
                <summary> <strong>Q:</strong> How can I become a part of the Apsara community?</summary>
                    <div class="about-us_faq_answers">
                        <strong>Answer: </strong>

                        <p> We welcome enthusiasts and professionals alike to join our community. Follow us on social media, participate in our events, and share your creative work with us to become part of our vibrant community.</p>
                    </div>
            </details>

            <details>
                <summary> <strong>Q:</strong> How can I provide feedback on Apsara products?</summary>
                    <div class="about-us_faq_answers">
                        <strong>Answer: </strong>

                        <p> We value your feedback and would love to hear from you. You can reach out to us via our contact page or social media channels with any comments or suggestions you have.</p>
                    </div>
            </details>

        </div>
    </section>
</template>

<script>
    export default {
        name: "About"
    }
</script>

<style lang="scss" scoped>

    section {
        max-width: 100%;
    }

    .column {
        display: flex;
        flex-direction: column;
    }
    .about-us-wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        position: relative;
        top: 80px;
        width: 80%;
        min-height: 600px;
        flex-wrap: wrap;
        padding: 20px;
        margin: 0 auto;
    }

    .about-us-content {
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 auto;
    }

    .about-us__image {
        margin-top: 40px;
        img {
            max-width: 100%;
        }
    }

    .about-us__text {
        display: flex;
        justify-content: center;
        max-width: 600px;
        width: 100%;
    }


    .faq {
        margin-bottom: 40px;
        margin-top: 50px;
        width: 80%;
    }


    details {
        margin-bottom: 20px;
        max-width: 600px;
        display: flex;
        justify-content: center;
        flex-direction: column;
        width: 100%;
    }

    details strong {
        margin-bottom: 15px;
    }

    summary {
        color: #21243d;
        margin-bottom: 15px;
        max-width: 100%;
    }

    summary strong {
        color: #6E798C;
        font-size: 18px;
    }

    .about-us_faq_answers {
        display: flex;
        flex-direction: column;
    }

    details a {
        text-decoration: none;
        color: #016492;
        font-size: 16px;
        margin-bottom: 5px;
    }

    .socialMedia__discord {
        display: flex;
        justify-content: center;
        width: 100%;
        margin: 0 auto;
        margin-bottom: 50px;
    }

    .socialMedia__discord>iframe {
        width: 90%;
        max-width: 500px;
    }
</style>
