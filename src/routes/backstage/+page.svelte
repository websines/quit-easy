<script>
  import Leaf from '../../assets/leaf.jpg'
  import Footer from '../../lib/footer.svelte'
  import Header from '../../lib/header.svelte'
  import Title from '../../lib/title.svelte'
</script>

<main class="font-Inter">
  <Header />
  <Title
    page_title="backstage"
    links={['outline', 'getting involved', 'contacting', 'media', 'about']} />
  <section name="content" id="outline" class="my-12">
    <div
      class="flex flex-col sm:flex-row w-full p-4 mx-4 items-center
      justify-center">
      <div class="flex flex-col w-full justify-start">
        <div class="p-4 mt-4 sm:-translate-y-[40px]">
          <h1 class="text-3xl sm:text-4xl font-semibold">Outline</h1>
        </div>
        <p class="text-base p-4">
          quiteasily is
          <span>
            <li>for removing addiction from the Earth quickly and easily</li>
            <li>using virality for creating conversations</li>
            <li>directing people into spreading the message locally</li>
          </span>
          . Most methods leave people feeling like they're 'addicts' on the
          fringes of society, overlooking that some things are just inherently
          addictive. We're starting with pornography because it has the greatest
          social impact. Our campaigns take a two pronged approach; firstly,
          with conversations showing the hidden harms these create, and
          secondly, showing that it’s easy and enjoyable to quit. Please enjoy!
        </p>
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
  <section id="getting involved" class="p-4">
    <div class="flex flex-col p-4 my-8 w-full items-center justify-center">
      <h1 class="text-3xl sm:text-4xl font-semibold my-4">Getting involved</h1>
      <p>
        If you’re interested in making a difference, prepare to create change
        locally. You can help out in many ways, depending on your time
        commitment.
        <br />
        <span>
          For instance, you can
          <li>Repost memes we’ve created</li>
          <li>Create your own content using #quiteasily</li>
          <li>Start putting up posters in your local community</li>
          <li>Connect quiteasily to people who need to see it</li>
          <li>Create change locally.</li>
        </span>
        We’ve got guides and resources to help :)
      </p>
      <div
        class="rounded-3xl border-[1px] border-solid border-black px-6 py-6
        hover:bg-black hover:text-white hover:border-white my-4 cursor-pointer">
        <a href="/getting-involved">
          <span class="text-2xl">getting involved</span>
        </a>
      </div>
    </div>
  </section>
  <section id="contacting">
    <div class="flex flex-col p-4 my-8 w-full items-center justify-center">
      <h1 class="text-3xl sm:text-4xl font-semibold my-4">Contacting</h1>
      <p class="text-base p-4">
        Nobody likes email, so let’s try minimising the time we spend on it.
        Please make sure you Summarise your email in the subject. Write
        concisely. For example, to: quiteasily subject: [role] with [past]
        experience would like to help out with [task or idea] for [time] a week
        Hey! easypeasy really changed my life and I'd love to help out. I'm a
        [role] with a background in [the past] and think that I can help out
        doing [task or idea that might help.] I'm available to help between
        [time] on [days], and can meet any time that suits you, and have gotten
        started doing [task]. Wishing you well, [you] For pretty much
        everything, please email hello[at][domain name].org ... but if you've
        got an opportunity you feel needs priority attention, like being a
        celebrity, government department, or anything else huge -- please email
        youdontunderstand[at][domain name].org We’ll try answering all emails as
        fast as we can, so we ask you please respect these sorting systems.
        We’re only human!
      </p>
    </div>
  </section>
  <section id="media">
    <div class="flex flex-col p-4 my-8 w-full items-center justify-center">
      <h1 class="text-3xl sm:text-4xl font-semibold my-4">Media</h1>
      <p class="text-base p-4 text-center">
        For media inquiries, please contact
        <br />
        media+quiteasily@[peaceful foundation domain name]
      </p>
    </div>
  </section>
  <section id="about">
    <div class="flex flex-col p-4 my-8 w-full items-center justify-center">
      <h1 class="text-3xl sm:text-4xl font-semibold my-4">About</h1>
      <p class="text-base p-4 text-center">
        quiteasily is an organisation under the peaceful foundation for
        organising how to coordinate people to
      </p>
    </div>
  </section>
  <Footer footer_link="quiteasily.org" />
</main>
