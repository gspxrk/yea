<template>
    <div class="learning">

        <section class="learning-image">
            <img src="../../assets/images/learning.jpg" alt=""/>
        </section>

        <section class="learning-details">
            <h2> Explore Our Stationery Collection ✏️ </h2>
            <p>
            At Apsara, we offer a wide range of stationery designed to enhance your creativity and productivity. 
            Discover our products that have been trusted by students and professionals alike:
            </p>

            <ul>
                <li> High-Quality Pencils for Smooth Writing</li>
                <li> Precision Erasers for Clean Corrections</li>
                <li> Durable Sharpeners for Sharp Points</li>
                <li> Artistic Supplies for Creative Expression</li>
                <li> Notebooks & Sketchpads for Ideas and Notes</li>
                <li> Crafting Tools for Innovative Projects</li>
            </ul>

        </section>
    </div>
</template>

<script>
export default {
    name: 'Learning'
}
</script>

<style lang="scss" scoped>
.learning {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    @media (max-width:900px) {
        flex-direction: column;
    }
}
.learning-details {
    width: 40%;
    display: flex;
    flex-direction: column;

    h2 {
        text-align: center;
        width: 100%;
        text-align: center;
        font-size: 2rem;
    }

    @media (max-width:900px) {
        width: 80%;
    }
}
.learning-image {
    width: 50%;
    display: flex;
    justify-content: center;

    @media (max-width:900px) {
        width: 80%;
    }

   img {
    height: auto;
    width: 80%
   }
}
</style>
