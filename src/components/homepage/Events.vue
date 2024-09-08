<template>
    <div class="creativity-corner">
        <section class="creativity-corner__image">
            <img src="../../assets/images/inspiration.png" alt="Apsara Creativity"/>
        </section>

        <section class="creativity-corner-details">
            <h2> Get Inspired with Apsara ✨ </h2>
            <p>
                At Apsara, we believe that creativity can be found everywhere. Whether you're sketching your first drawing or working on your next big project, our tools are designed to inspire your creative journey.
            </p>
            <p> 
                Check out the tips and tricks we’ve put together to help you unlock your imagination. Explore how others are using Apsara products, or challenge yourself with our latest art prompts. Share your creations and join the creative community!
            </p>

            <a href="https://apsara.com/inspiration"> Explore Inspiration</a>
        </section>
    </div>
</template>


<script>
export default {
    name: 'Events'
}
</script>

<style scoped lang="scss">
    .creativity-corner {
        width: 100%;
        max-width: 950px;
        min-height: 500px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-bottom: 30px;
        padding-top: 30px;

        @media (max-width: 900px) {
            flex-direction: column-reverse;
        }
    }

    .creativity-corner__image {
        width: 40%;
        display: flex;
        justify-content: center;
        align-items: center;

        img {
            width: 100%;
            border-radius: 10px;
        }

        @media (max-width: 900px) {
            width: 90%;
        }

        @media (max-width: 400px) {
           img {
            width: 100%;
           }
        }
    }

    .creativity-corner-details {
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin-left: 40px;

        @media (max-width: 900px) {
            width: 90%;
            margin-bottom: 60px;
            margin-left: 0;
        }
    }

    h2 {
        text-align: center;
        font-size: 2rem;
    }

    p {
        text-align: center;
        font-size: 1.1rem;
    }

    a {
        background: #ffc22b;
        border-radius: 10px;
        color: var(--dark)!important;
        font-style: normal;
        font-weight: bold;
        font-size: 18px;
        line-height: 29px;
        text-align: center;
        letter-spacing: 2px;
        text-transform: uppercase;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 45px;
        padding: 10px 30px;
        max-width: 80%;
        transition: 300ms all ease-in-out;

        &:hover {
            padding: 10px 50px;
        }
    }
</style>
