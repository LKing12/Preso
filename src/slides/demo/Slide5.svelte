<div class="flex-row" style="min-height: 100vh; text-align:center;justify-content: space-evenly;align-items: center;">
    <img src="bg.jpg" alt="background" class="fixed object-cover w-screen h-screen" />
    <div
        class="card card-large animate__animated animate__slideInRight start-1:animate__hinge end-1:animate__slideInRight"
    >
        <p class="label">Design</p>
        <h1 class="text-left">Use background image</h1>
        <p class="major">
            A picture is worth a thousand words. Illustrate your point with a background image. Then place whatever you
            want on top of it.
        </p>
    </div>
</div>
<style>
    .card-large{
        position: absolute;
        margin: 1.25rem;
        padding: 1.25rem;
        background-color: rgba(255, 255, 255, 1);
        border-radius: 0.5rem;
        position: relative;
        opacity: 0.9;

    }
    @media (min-width: 640px) {
        .card{
            padding: 2.5rem;
        }
    }
    @media (min-width: 768px) {
        .card {
            width: 50%;
        }
        }
    @media (min-width: 1024px) {
        .card {
            width: 33.3333333333%;
        }
    }
</style>