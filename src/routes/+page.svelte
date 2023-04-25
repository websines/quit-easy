<script>
  import BookSVG from '$lib/svg.svelte'
  import BookCover from '../assets/book-cover.jpg'
  import Leaf from '../assets/leaf.jpg'
  import Footer from '../lib/footer.svelte'
  import Header from '../lib/header.svelte'
</script>

<main class="font-Inter">
  <Header />
  <section name="hero" class="my-4 sm:p-10 p-6 w-full">
    <div class="w-full flex flex-row items-center justify-center">
      <div class="flex flex-col space-y-2 items-center">
        <a href="/">
          <h1 class="font-normal text-4xl sm:text-6xl tracking-wider">
            quit easily
          </h1>
        </a>
        <p class="text-sm sm:text-base">
          quitting addictions without willpower
        </p>
      </div>
      <BookSVG />
    </div>
  </section>
  <section name="books">
    <div
      class="p-2 mx-4 flex flex-col md:flex-row justify-center items-center
      w-full">
      <div class="flex flex-col justify-center items-center sm:mr-6">
        <h1 class="font-bold tracking-wide">pornography</h1>
        <hr class="h-[1px] bg-black w-[90%] my-3 border border-black" />
        <div class="flex flex-row justify-center items-center space-x-2">
          <img
            src={BookCover}
            alt="book"
            class="w-[150px] h-[235px] sm:w-[317px] sm:h-[463px]" />
          <img
            src={BookCover}
            alt="book"
            class="w-[150px] h-[235px] sm:w-[317px] sm:h-[463px]" />
        </div>
      </div>
      <div class="flex flex-row justify-center items-center">
        <div
          class="flex flex-col justify-center items-center sm:mr-6 mt-4 sm:mt-0">
          <h1 class="font-bold tracking-wide">alcohol</h1>
          <hr class="h-[1px] bg-black w-[90%] my-3 border border-black" />
          <div class="flex flex-row justify-center items-center space-x-2">
            <img
              src={BookCover}
              alt="book"
              class="w-[150px] h-[235px] sm:w-[317px] sm:h-[463px]" />
          </div>
        </div>
        <div
          class="flex flex-col justify-center items-center sm:mr-6 mt-4 sm:mt-0">
          <h1 class="font-bold tracking-wide">smoking</h1>
          <hr class="h-[1px] bg-black w-[90%] my-3 border border-black" />
          <div class="flex flex-row justify-center items-center space-x-2">
            <img
              src={BookCover}
              alt="book"
              class="w-[150px] h-[235px] sm:w-[317px] sm:h-[463px]" />
          </div>
        </div>
      </div>
    </div>
  </section>
  <section name="content" class="my-12">
    <div
      class="flex flex-col sm:flex-row w-full p-2 mx-4 items-center
      justify-center">
      <div class="flex flex-col w-full justify-start">
        <div class="p-4 my-4 sm:-translate-y-[40px]">
          <h1 class="text-3xl sm:text-4xl font-semibold">
            why are these so different?
          </h1>
        </div>
        <div class="flex flex-col w-full p-4 mr-4">
          <h2 class="text-xl sm:text-2xl font-medium my-2">Zero willpower</h2>
          <p class="text-base">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos
            ex rem ipsa. Ut porro explicabo laudantium neque! Neque, assumenda
            velit et, sapiente quia rem voluptatem incidunt quaerat non tempora
            fuga!
          </p>
        </div>
        <div class="flex flex-col w-full p-4 mr-4">
          <h2 class="text-xl sm:text-2xl font-medium my-2">Completely free</h2>
          <p class="text-base">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos
            ex rem ipsa. Ut porro explicabo laudantium neque! Neque, assumenda
            velit et, sapiente quia rem voluptatem incidunt quaerat non tempora
            fuga!
          </p>
        </div>
        <div class="flex flex-col w-full p-4 mr-4">
          <h2 class="text-xl sm:text-2xl font-medium my-2">Actually works</h2>
          <p class="text-base">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos
            ex rem ipsa. Ut porro explicabo laudantium neque! Neque, assumenda
            velit et, sapiente quia rem voluptatem incidunt quaerat non tempora
            fuga!
          </p>
        </div>
        <div class="flex flex-col w-full justify-center items-center my-4">
          <p class="text-2xl my-4">If it helps, we'd love yours too!</p>
          <div
            class="rounded-3xl border-[1px] border-solid border-black px-10 py-6
            hover:bg-black hover:text-white hover:border-white my-4
            cursor-pointer">
            <a href="/getting-involved">
              <span class="text-2xl">getting involved</span>
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
  <Footer footer_link="easypeasymethod" />
</main>
