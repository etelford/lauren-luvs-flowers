<template>
    <div id="app" class="bg-green-100 border-green-100 h-screen flex flex-col items-center justify-start pb-16">
        <div class="mt-6 bg-white w-full border-t border-b border-green-400 px-6 md:px-0">
            <div class="container w-full md:w-3/4 lg:w-3/5 xl:w-1/2 mx-auto">
                <div class="py-8 text-2xl text-green-800 leading-8">
                    <div class="flex flex-col md:flex-row md:space-x-2 items-center">
                        <span class="text-6xl">💐</span>
                        <p class="mt-4 md:mt-0"> Hello, my name is <span class="font-semibold">Lauren</span> and I'm an aspiring <span class="font-semibold">floral designer</span> based in <span class="font-semibold">Austin, Texas</span>. Welcome to my portfolio!</p>
                    </div>

                    <p class="mt-6 text-lg text-green-600">I hold Level 1 knowledge and skill-based certificates from the Texas State Florist Association.</p>

                    <p class="mt-6 text-lg text-green-700"><span class="text-xl">📫</span> Send an email to <a class="underline font-semibold hover:text-green-900" href="mailto:laurenluvsflowers@gmail.com">laurenluvsflowers@gmail.com</a> to get in touch!</p>

                    <p class="mt-6 text-green-600 text-lg">Click on any image below to view some of my work.</p>
                </div>
            </div>
        </div>

        <div class="bg-green-100 w-full px-6 md:px-0">
            <div class="container w-full md:w-3/4 lg:w-3/5 xl:w-1/2 mx-auto">
                <div class="mt-8 mb-24 grid grid-cols-2 sm:grid-cols-4 gap-4">
                    <a
                        href="/lg/01-corsage.jpg"
                        class="glightbox rounded-xl"
                        data-title="Corsage"
                        data-description="Spray roses, ruscus, and ribbon."
                    >
                        <img src="/sm/01-corsage.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/02-eucalyptus-autumn-bouquet.jpg"
                        class="glightbox rounded-xl"
                        data-title="Eucalyptus Autumn Bouquet"
                        data-description="Silver dollar eucalyptus, marigolds, mini sunflowers, and chrysanthemums."
                    >
                        <img src="/sm/02-eucalyptus-autumn-bouquet.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/03-autumn-table-centerpiece.jpg"
                        class="glightbox rounded-xl"
                        data-title="Autumn Centerpiece"
                        data-description="Silver dollar eucalyptus, marigolds, mini sunflowers, and chrysanthemums."
                    >
                        <img src="/sm/03-autumn-table-centerpiece.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/04-lavender-wheat-wreath.jpg"
                        class="glightbox rounded-xl"
                        data-title="Spring Wreath"
                        data-description="Lavender and wheat."
                    >
                        <img src="/sm/04-lavender-wheat-wreath.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/05-formal-roses-with-bow.jpg"
                        class="glightbox rounded-xl"
                        data-title="Roses with Bow"
                        data-description="Christmas greens, red roses, and a hand-tied bow"
                    >
                        <img src="/sm/05-formal-roses-with-bow.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/06-fall-pumpkin-centerpiece.jpg"
                        class="glightbox rounded-xl"
                        data-title="Fall Centerpiece in Pumpkin"
                        data-description="Daisy palms, pink roses, lilies, saladego, ruscus, and leather leaf."
                    >
                        <img src="/sm/06-fall-pumpkin-centerpiece.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/07-rose-bouquet.jpg"
                        class="glightbox rounded-xl"
                        data-title="Rose Bouquet"
                        data-description="Pink roses, hypericum berry, curly willow, and myrtle."
                    >
                        <img src="/sm/07-rose-bouquet.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/08-cascading-rose-bouquet.jpg"
                        class="glightbox rounded-xl"
                        data-title="Cascading Rose Bouquet"
                        data-description="Roses, mini carnations, wax flower, myrtle, and ruscus."
                    >
                        <img src="/sm/08-cascading-rose-bouquet.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/09-christmas-hanging-swag.jpg"
                        class="glightbox rounded-xl"
                        data-title="Christmas Swag"
                        data-description="Christmas greens and hand-tied bow."
                    >
                        <img src="/sm/09-christmas-hanging-swag.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/10-lily-boutonnieres.jpg"
                        class="glightbox rounded-xl"
                        data-title="Lily Boutonnieres"
                        data-description="Lilies and bear grass."
                    >
                        <img src="/sm/10-lily-boutonnieres.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/11-rose-centerpiece.jpg"
                        class="glightbox rounded-xl"
                        data-title="Rose Centerpiece"
                        data-description="Red roses, Christmas greens, lemon leaf, and ting."
                    >
                        <img src="/sm/11-rose-centerpiece.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/12-assorted-flow-bouquet.jpg"
                        class="glightbox rounded-xl"
                        data-title="Funeral Spray"
                        data-description="White daisy palms, peach and pink roses, gerber daisies, baby's breath, and leather leaf."
                    >
                        <img src="/sm/12-assorted-flow-bouquet.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/13-carnation-centerpiece-01.jpg"
                        class="glightbox rounded-xl"
                        data-title="Carnation Centerpiece"
                        data-description="Pink carnations, purple statice, and leather leaf."
                    >
                        <img src="/sm/13-carnation-centerpiece-01.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/14-carnation-centerpiece-02.jpg"
                        class="glightbox rounded-xl"
                        data-title="Carnation Centerpiece"
                        data-description="Pink and yellow carnations and leather leaf."
                    >
                        <img src="/sm/14-carnation-centerpiece-02.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/15-spring-flower-vase-01.jpg"
                        class="glightbox rounded-xl"
                        data-title="Spring Flower Vase (front view)"
                        data-description="Spider chrysanthemums, mini sunflowers, daisy palms, and Peruvian lily."
                    >
                        <img src="/sm/15-spring-flower-vase-01.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/16-spring-flower-vase-02.jpg"
                        class="glightbox rounded-xl"
                        data-title="Spring Flower Vase (top view)"
                        data-description="Spider chrysanthemums, mini sunflowers, daisy palms, and Peruvian lily."
                    >
                        <img src="/sm/16-spring-flower-vase-02.jpg" class="rounded-xl">
                    </a>

                    <a
                        href="/lg/17-my-first-ladies.jpg"
                        class="glightbox rounded-xl"
                        data-title="Inspired by the book 'My First Ladies'"
                        data-description="Peach and yellow roses, carnations, lilies, and delphinium."
                    >
                        <img src="/sm/17-my-first-ladies.jpg" class="rounded-xl">
                    </a>
                </div>
            </div>
        </div>

        <div class="py-6 bg-white w-full px-6 md:px-0 text-gray-400 text-sm text-right">
            <div class="container w-full md:w-3/4 lg:w-3/5 xl:w-1/2 mx-auto">
                <div class="flex flex-col md:flex-row-reverse items-center justify-between">
                    <p>&copy; 2021 by Lauren Hooker.</p>
                    <p class="mt-1">Made with <span class="text-lg">❤️</span> in Austin, TX.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import GLightbox from 'glightbox'
import 'glightbox/dist/css/glightbox.css'

export default {
    name: 'App',
    components: {

    },

    mounted() {
        this.gallery = GLightbox({
            selector: '.glightbox',
            loop: true,
        })
    },

    methods: {
        openGallery() {
            this.gallery.open()
        }
    },

    data() {
        return {
            gallery: null,
        }
    },
}
</script>
