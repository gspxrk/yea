<template>
    <footer>
        <section class="columns">
            <aside class="left-column">
                <p> Join us: </p>

                <a href="https://www.instagram.com/official.apsara/" target="_blank">
                    <img src="../assets/images/footer/instagram-logo.png" alt=""/> 
                    instagram
                </a>

                <a href="https://www.youtube.com/channel/UCMCY4g7AgvGKwKyYQSmTq5A" target="_blank">
                    <img src="https://e7.pngegg.com/pngimages/208/269/png-clipart-youtube-play-button-computer-icons-youtube-youtube-logo-angle-rectangle-thumbnail.png" alt="" /> 
                    YouTube
                </a>
                
            </aside>

            <aside class="right-column">
               <p> Important Links: </p>

                <a href="https://www.hindustanpencils.com/category/products/apsara/apsara-pencils/" target="_blank">
                    store
                </a>
                
                <a href="/privacy">
                    privacy policy
                </a>
            </aside>
        </section>

        <section class="copyright">
            <p> © Sleepy Development, {{ currentYear }}</p>
        </section>
    </footer>
</template>


<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Footer-Component',
    data() {
        return {
            date: new Date()
        }
    },
    computed: {
        currentYear() {
            return this.date.getFullYear()
        }
    }

}
</script>


<style lang="scss" scoped>


    footer {

        background: #2c3e50;
        color: white;
        display: flex;
        padding: 20px;

        justify-content: center;
        flex-direction: column;

        .columns {
            display: flex;
            align-items: baseline;

            aside {
                display: flex;
                flex-direction: column;
                width: 50%;
                justify-content: center;
                align-items: center;

                p {
                    font-weight: bold;
                    font-size: 1.4em;
                    text-decoration-line: underline;
                    text-decoration-style: solid;
                    text-decoration-color: #ffc22b;
                    text-underline-offset: 10px;
                }

                a {
                    color: white;
                    display: flex;
                    align-items: center;
 
                    text-transform: capitalize;
                    margin: 5px;

                    img {
                        width: 30px;
                        height: 30px;
                        margin-right: 20px;
                    }
                }
            }

            .left-column a {
                width: 120px;
                padding: 3px;
            }
        }


        .copyright {
            margin-top: 30px;
            text-align: center;
        }
    }



    @media (max-width: 520px) {
        .columns {
            flex-direction: column;
            justify-content: center;
            align-items: center!important;

            aside {
                width: 90%!important;
                margin-bottom: 30px;
            }
        }
    }


    @media (max-width: 350px) {
        footer .columns aside{
            p {
                font-size: 1.2em;
            }
        }
    }

</style>
