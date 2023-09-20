<script>
    import BImg1 from "$lib/images/banner1.png"
    import BImg2 from "$lib/images/banner2.png"
    import BImg3 from "$lib/images/banner3.png"
    import BImg4 from "$lib/images/banner4.png"
    import BImg5 from "$lib/images/banner5.png"
    import line_one from "$lib/images/line_one.png"
    import down_line from "$lib/images/down_line.png"
    import hompage from "$lib/video/homepage.mp4"
    
</script>
<div class="cont">
    <div class="">
        <div class="tpp banner">
            <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active" data-bs-interval="5000">
                        <img src={BImg1} class="d-block w-100" alt="banner1">
                    </div>
                    <div class="carousel-item" data-bs-interval="5000">
                        <img src={BImg2} class="d-block w-100" alt="banner2">
                    </div>
                    <div class="carousel-item" data-bs-interval="5000">
                        <img src={BImg3} class="d-block w-100" alt="banner3">
                    </div>
                    <div class="carousel-item" data-bs-interval="5000">
                        <img src={BImg4} class="d-block w-100" alt="banner4">
                    </div>
                    <div class="carousel-item" data-bs-interval="5000">
                        <img src={BImg5} class="d-block w-100" alt="banner5">
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div>
        <div class="line">
            <img src={line_one} alt="line img">
        </div>
    </div>
    <div id="homeC">
        <div id="lLeft">
            <img src={down_line} alt="downline">
        </div>
        <div id="video">
            <video id="vid" autoplay="true" muted="muted" loop="true">
                <source src={hompage} type="video/mp4"/>
            </video>
        </div>
        <div id="about">
            <textarea id="about-textarea" readonly>
                About the Artist
                Trouser Project started in 2018 when I bought too many trousers from charity shops.
                I started using bleach to add designs, and over the years have learnt many more up-cycling
                techniques. I love to screen print, Lino print, cut & sew, hand paint, add patches.
                Giving new life to old clothes - it’s sustainable and sexy and you’re going to be the only person
                with this item of clothing.

                I sell my work in Afflecks in Manchester alongside lots of other independent brands. Find our
                collective shop Avant Garms on the second floor. I travel a lot for pop ups/ markets/ festivals so
                follow me on Instagram to keep updated. I also love working on custom requests, you can send
                me old clothing of yours and ask for any design.

            </textarea>
        </div>
        <div id="lRight">
            <img src={down_line} alt="down line">
        </div>
    </div>
</div>

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<!-- <script>
    window.addEventListener('DOMContentLoaded', (event) => {
        var v = document.getElementById("vid");
        v.play();
    });
</script> -->
