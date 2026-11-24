---
layout: default
---

<h1 style="text-align: center;">UCL Students in Gaza - Art Sale </h1>


This art sale was launched by students at UCL as a mutual-aid action to support a number of Palestinian students in Gaza who hold offers to join masters courses at UCL. The students, currently in Gaza, all received partial scholarships from UCL. However, these cover only a fraction of the international tuition fees UCL is charging, which are around £40,000. They also face significant costs covering their rent and living expenses in London. All money from this art sale will be used to support the students with their expenses.

The artworks in this collection have been generously donated to this fundraising effort. If you have any questions or artworks you would like to contribute, please get in touch with uclactionforpalestine@gmail.com.

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>

---