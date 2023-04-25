<script>
  import BookSVG from '$lib/svg.svelte'
  import Leaf from '../../assets/leaf.jpg'
  import Footer from '../../lib/footer.svelte'
  import Header from '../../lib/header.svelte'
  import Title from '../../lib/title.svelte'
</script>

<main class="font-Inter">
  <Header />
  <Title
    page_title="getting involved"
    links={['online', 'local', 'social', 'global', 'contribute']} />
  <section class="m-4 p-8">
    <div class="flex flex-col justify-center items-center p-4 m-4">
      <span>
        Here's steps for the most social impact using your reach and resources.
        All are self-contained, for varying levels of time and interest.
        <br />
        You can make a difference
        <ul>
          <li>Online, sharing memes, stories and creations</li>
          <li>Locally, using posters, letters and calm events</li>
          <li>
            Socially, through cultivating calmness and having conversations
          </li>
          <li>Globally, by working towards a better world for everyone.</li>
        </ul>
      </span>
      <div class="my-4">
        <img
          src="https://www.figma.com/file/oHg2MuiOybIcasglfyWWyC/landing-page?node-id=489-6&t=RpVJX1Xj0dyPQP7o-4"
          alt="something" />
      </div>

    </div>
  </section>
  <section name="content" id="online" class="my-12">
    <div
      class="flex flex-col sm:flex-row w-full p-2 mx-4 items-center
      justify-center">
      <div class="flex flex-col w-full justify-start">
        <div class="p-4 my-4 sm:-translate-y-[40px]">
          <h1 class="text-3xl sm:text-4xl font-semibold">Online</h1>
        </div>
        <div class="flex flex-col w-full p-4 mr-4">
          <p class="text-base">
            easypeasy memes are hosted on
            <br />
            coomer.org hosts memes You can't control the internet, but it'd be
            cool if we could all be kind.
            <br />
            Meme magic is powerful and I'd love thinking we could direct it into
            something beautiful that brings people togethe
          </p>
        </div>
        <div class="flex flex-col w-full justify-center items-center my-4">
          <p class="text-lg my-4 p-4">
            So please, whatever you do, don't succumb to hatred -- the world's
            got enough of that already
          </p>
          <div
            class="rounded-3xl border-[1px] border-solid border-black px-10 py-6
            hover:bg-black hover:text-white hover:border-white my-4
            cursor-pointer">
            <a href="/getting-involved">
              <span class="text-2xl">shareable meme zone</span>
            </a>
          </div>
        </div>
      </div>
      <div
        class="hidden sm:flex flex-col space-y-2 items-center justify-center
        w-full mt-12">
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-y-[10px]
          translate-x-[20px]" />
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-x-[20px]" />
      </div>
    </div>
  </section>
  <section name="content" id="local" class="my-12">
    <div
      class="flex flex-col sm:flex-row w-full p-2 mx-4 items-center
      justify-center">
      <div class="flex flex-col w-full justify-start">
        <div class="p-4 my-4 sm:-translate-y-[40px]">
          <h1 class="text-3xl sm:text-4xl font-semibold">Local</h1>
        </div>
        <div class="flex flex-col w-full p-4 mr-4">
          <p class="text-base">
            easypeasy memes are hosted on
            <br />
            coomer.org hosts memes You can't control the internet, but it'd be
            cool if we could all be kind.
            <br />
            Meme magic is powerful and I'd love thinking we could direct it into
            something beautiful that brings people togethe
          </p>
        </div>
        <div class="flex flex-col w-full justify-center items-center my-4">
          <p class="text-lg my-4 p-4">
            So please, whatever you do, don't succumb to hatred -- the world's
            got enough of that already
          </p>
          <div
            class="rounded-3xl border-[1px] border-solid border-black px-10 py-6
            hover:bg-black hover:text-white hover:border-white my-4
            cursor-pointer">
            <a href="/getting-involved">
              <span class="text-2xl">shareable meme zone</span>
            </a>
          </div>
        </div>
      </div>
      <div
        class="hidden sm:flex flex-col space-y-2 items-center justify-center
        w-full mt-12">
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-y-[10px]
          translate-x-[20px]" />
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-x-[20px]" />
      </div>
    </div>
  </section>
  <section name="content" id="social" class="my-12">
    <div
      class="flex flex-col sm:flex-row w-full p-2 mx-4 items-center
      justify-center">
      <div class="flex flex-col w-full justify-start">
        <div class="p-4 my-4 sm:-translate-y-[40px]">
          <h1 class="text-3xl sm:text-4xl font-semibold">Social</h1>
        </div>
        <div class="flex flex-col w-full p-4 mr-4">
          <p class="text-base">
            easypeasy memes are hosted on
            <br />
            coomer.org hosts memes You can't control the internet, but it'd be
            cool if we could all be kind.
            <br />
            Meme magic is powerful and I'd love thinking we could direct it into
            something beautiful that brings people togethe
          </p>
        </div>
        <div class="flex flex-col w-full justify-center items-center my-4">
          <p class="text-lg my-4 p-4">
            So please, whatever you do, don't succumb to hatred -- the world's
            got enough of that already
          </p>
          <div
            class="rounded-3xl border-[1px] border-solid border-black px-10 py-6
            hover:bg-black hover:text-white hover:border-white my-4
            cursor-pointer">
            <a href="/getting-involved">
              <span class="text-2xl">shareable meme zone</span>
            </a>
          </div>
        </div>
      </div>
      <div
        class="hidden sm:flex flex-col space-y-2 items-center justify-center
        w-full mt-12">
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-y-[10px]
          translate-x-[20px]" />
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-x-[20px]" />
      </div>
    </div>
  </section>
  <section name="content" id="global" class="my-12">
    <div
      class="flex flex-col sm:flex-row w-full p-2 mx-4 items-center
      justify-center">
      <div class="flex flex-col w-full justify-start">
        <div class="p-4 my-4 sm:-translate-y-[40px]">
          <h1 class="text-3xl sm:text-4xl font-semibold">Global</h1>
        </div>
        <div class="flex flex-col w-full p-4 mr-4">
          <p class="text-base">
            easypeasy memes are hosted on
            <br />
            coomer.org hosts memes You can't control the internet, but it'd be
            cool if we could all be kind.
            <br />
            Meme magic is powerful and I'd love thinking we could direct it into
            something beautiful that brings people togethe
          </p>
        </div>
        <div class="flex flex-col w-full justify-center items-center my-4">
          <p class="text-lg my-4 p-4">
            So please, whatever you do, don't succumb to hatred -- the world's
            got enough of that already
          </p>
          <div
            class="rounded-3xl border-[1px] border-solid border-black px-10 py-6
            hover:bg-black hover:text-white hover:border-white my-4
            cursor-pointer">
            <a href="/getting-involved">
              <span class="text-2xl">shareable meme zone</span>
            </a>
          </div>
        </div>
      </div>
      <div
        class="hidden sm:flex flex-col space-y-2 items-center justify-center
        w-full mt-12">
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-y-[10px]
          translate-x-[20px]" />
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-x-[20px]" />
      </div>
    </div>
  </section>
  <section name="content" id="contribute" class="my-12">
    <div
      class="flex flex-col sm:flex-row w-full p-2 mx-4 items-center
      justify-center">
      <div class="flex flex-col w-full justify-start">
        <div class="p-4 my-4 sm:-translate-y-[40px]">
          <h1 class="text-3xl sm:text-4xl font-semibold">Contribute</h1>
        </div>
        <div class="flex flex-col w-full p-4 mr-4">
          <p class="text-base">
            easypeasy memes are hosted on
            <br />
            coomer.org hosts memes You can't control the internet, but it'd be
            cool if we could all be kind.
            <br />
            Meme magic is powerful and I'd love thinking we could direct it into
            something beautiful that brings people togethe
          </p>
        </div>
        <div class="flex flex-col w-full justify-center items-center my-4">
          <p class="text-lg my-4 p-4">
            So please, whatever you do, don't succumb to hatred -- the world's
            got enough of that already
          </p>
          <div
            class="rounded-3xl border-[1px] border-solid border-black px-10 py-6
            hover:bg-black hover:text-white hover:border-white my-4
            cursor-pointer">
            <a href="/getting-involved">
              <span class="text-2xl">shareable meme zone</span>
            </a>
          </div>
        </div>
      </div>
      <div
        class="hidden sm:flex flex-col space-y-2 items-center justify-center
        w-full mt-12">
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-y-[10px]
          translate-x-[20px]" />
        <img
          src={Leaf}
          alt="leaf"
          class="sm:w-[379px] sm:h-[259px] -translate-x-[20px]" />
      </div>
    </div>
  </section>
  <Footer footer_link="quiteasily.org" />
</main>
