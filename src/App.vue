<script setup>
</script>

<template>
  <div class="flex flex-col bg-[#FBF8F3] min-w-[400px] antialiased font-roboto">
    <!-- navbar -->
    <nav class="flex items-center justify-between pt-10 p-5 md:p-10 xl:px-40">
      <div class="text-blue-500 text-2xl font-black italic">Chirp.</div>
      <div class="flex items-center justify-end">
        <img src="./assets/HamburgerMenu.svg" alt="" class="flex md:hidden" />

        <div
          class="
            hidden
            md:flex
            items-center
            justify-end
            space-x-5
            xl:space-x-10
          "
        >
          <a
            href="#"
            class="
              text-xl text-gray-500
              font-semibold
              hover:text-gray-600
              transition-colors
            "
            >Home</a
          >

          <a
            href="#"
            class="
              text-xl text-gray-500
              font-semibold
              hover:text-gray-600
              transition-colors
            "
            >Pricing</a
          >

          <a
            href="#"
            class="
              text-xl text-gray-500
              font-semibold
              hover:text-gray-600
              transition-colors
            "
            >FAQ</a
          >

          <button
            class="
              bg-[#1DA1F2]
              flex
              items-center
              justify-center
              space-x-3
              py-4
              px-5
              rounded-lg
              hover:bg-[#1a89ce]
              transition-colors
              xl:py-6 xl:px-8
            "
          >
            <img src="./assets/Twitter.svg" alt="Sign in with Twitter" />
            <span class="text-white font-semibold text-lg">
              Sign in with Twitter
            </span>
          </button>
        </div>
      </div>
    </nav>

    <!-- hero -->
    <div
      class="
        pb-20
        px-5
        md:p-10
        xl:px-40
        flex flex-col-reverse
        xl:flex-row
        items-start
        justify-between
        space-y-10
        xl:space-x-20
        2xl:space-x-80
        xl:space-y-0
      "
    >
      <div class="flex flex-col space-y-4 md:space-y-8 xl:flex-1 mt-10">
        <h1 class="text-4xl md:text-[4.5rem] leading-[1.2] font-bold">
          Twitter analytics taken to a whole new level.
        </h1>

        <div class="text-gray-500 font-normal text-[1.4rem] leading-[1.5]">
          Chirp is suit of Twitter analytics that will help you better
          understand your audience, which tweets they like, and most
          importantly, when they are the most active on Twitter.
        </div>

        <div class="flex flex-col md:flex-row">
          <button
            class="
              bg-[#1DA1F2]
              flex
              items-center
              justify-center
              space-x-3
              py-4
              px-5
              rounded-lg
              hover:bg-[#1a89ce]
              transition-colors
            "
          >
            <img src="./assets/Twitter.svg" alt="Sign in with Twitter" />
            <span class="text-white font-semibold text-lg"
              >Sign in with Twitter</span
            >
          </button>

          <button class="flex items-center justify-center space-x-3 py-2 px-5">
            <span class="text-[#1DA1F2] font-bold text-lg">Learn more</span>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5 stroke-[#1DA1F2]"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M14 5l7 7m0 0l-7 7m7-7H3"
              />
            </svg>
          </button>
        </div>

        <div class="flex items-start justify-start relative pb-10">
          <img
            src="./assets/userAvatar01.svg"
            alt="User Avatar 1"
            class="rounded-full absolute left-0"
          />
          <img
            src="./assets/userAvatar02.svg"
            alt="User Avatar 2"
            class="rounded-full absolute left-[20px]"
          />
          <img
            src="./assets/userAvatar03.svg"
            alt="User Avatar 3"
            class="rounded-full absolute left-[40px]"
          />
          <img
            src="./assets/userAvatar04.svg"
            alt="User Avatar 4"
            class="rounded-full absolute left-[60px]"
          />
          <img
            src="./assets/userAvatar05.svg"
            alt="User Avatar 5"
            class="rounded-full absolute left-[80px]"
          />
          <img
            src="./assets/userAvatar06.svg"
            alt="User Avatar 6"
            class="rounded-full absolute left-[100px]"
          />
          <img
            src="./assets/userAvatar07.svg"
            alt="User Avatar 7"
            class="rounded-full absolute left-[120px]"
          />
          <img
            src="./assets/userAvatar08.svg"
            alt="User Avatar 8"
            class="rounded-full absolute left-[140px]"
          />
          <img
            src="./assets/userAvatar09.svg"
            alt="User Avatar 9"
            class="rounded-full absolute left-[160px]"
          />
        </div>

        <div class="text-lg xl:text-xl text-gray-500 xl:w-2/3">
          Join <span class="font-bold text-[#1a80c0]"> 195 </span> others who
          have analyzed their followers and scheduled
          <span class="font-bold text-[#1a80c0]"> 1342 </span> tweets!
        </div>
      </div>

      <div class="md:hidden flex xl:flex xl:w-1/3 self-start">
        <img
          src="./assets/HeroImage(DesktopView).png"
          alt="Hero Image (Desktop View)"
          class="min-w-full"
        />
      </div>

      <div class="hidden md:flex xl:hidden">
        <img
          src="../src/assets/HeroImage(TabletView).png"
          alt="Hero Image (Desktop View)"
          class=""
        />
      </div>
    </div>

    <!-- body -->
    <div class="flex flex-col space-y-10 bg-white p-5 md:p-10 xl:px-40">
      <h4 class="text-4xl font-bold md:w-1/2">
        Features that help you Tweet smarter.
      </h4>

      <div class="grid grid-flow-row xl:grid-cols-2 gap-4">
        <!-- feature cards -->
        <div
          class="
            cursor-pointer
            hover:shadow-lg
            transition-all
            hover:scale-110
            bg-white
            active:scale-100
            p-10
            border border-gray-300
            rounded-xl
            flex flex-col
            space-y-5
            shadow-md
          "
        >
          <div class="text-5xl">📈</div>
          <div class="text-2xl font-bold">Analytics</div>
          <div class="text-lg text-gray-500">
            We constantly monitor your audience as it grows — so you can tweet
            when your followers are most likely to be online and ready to engage
            with your content.
          </div>
        </div>

        <div
          class="
            cursor-pointer
            hover:shadow-lg
            transition-all
            hover:scale-110
            bg-white
            active:scale-100
            p-10
            border border-gray-300
            rounded-xl
            flex flex-col
            space-y-5
            shadow-md
          "
        >
          <div class="text-5xl">🤓</div>
          <div class="text-2xl font-bold">Smart Analyzer</div>
          <div class="text-lg text-gray-500">
            Chirp automatically recognizes your followers' most active times and
            automatically sends you notifications if you're missing out on an
            opportunity.
          </div>
        </div>

        <div
          class="
            cursor-pointer
            hover:shadow-lg
            transition-all
            hover:scale-110
            bg-white
            active:scale-100
            p-10
            border border-gray-300
            rounded-xl
            flex flex-col
            space-y-5
            shadow-md
          "
        >
          <div class="text-5xl">🗞️</div>
          <div class="text-2xl font-bold">Schedule Your Tweets</div>
          <div class="text-lg text-gray-500">
            Quality tweets drive tons of engagement. With Chirp, you can write
            tweets in an advance and schedule them when your audience is most
            likely to read.
          </div>
        </div>

        <div
          class="
            cursor-pointer
            hover:shadow-lg
            transition-all
            hover:scale-110
            bg-white
            active:scale-100
            p-10
            border border-gray-300
            rounded-xl
            flex flex-col
            space-y-5
            shadow-md
          "
        >
          <div class="text-5xl">☀️</div>
          <div class="text-2xl font-bold">Dark Mode</div>
          <div class="text-lg text-gray-500">
            Friendly on the eyes, no matter what time you write your Tweets. All
            colors are chosen to make sure your eyes are at ease at all times.
          </div>
        </div>
      </div>
    </div>

    <!-- tweet cards -->
    <div class="bg-[#D7F5F5] flex flex-col p-5 md:p-10 xl:px-40 space-y-10">
      <div class="text-4xl font-bold tracking">What our customers say</div>

      <div class="grid grid-flow-row xl:grid-cols-3 gap-4">
        <!-- card -->
        <div
          class="
            flex flex-col
            bg-white
            p-5
            rounded-xl
            space-y-5
            shadow-md
            hover:scale-105
            transition-all
            hover:shadow-lg
          "
        >
          <div class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <img
                src="./assets/userAvatar01.svg"
                alt="userAvatar01"
                class="w-16 h-16"
              />
              <div class="flex flex-col">
                <div class="text-lg font-semibold">Sara May</div>
                <div class="text-sm text-gray-500">@sara_may</div>
              </div>
            </div>

            <div class="">
              <img
                src="../src/assets/Twitter(Blue).svg"
                alt="Twitter"
                class="w-10 h-10"
              />
            </div>
          </div>

          <div class="text-xl text-gray-500">
            I just tried our @chirp and it's amazing, love all the analytics I
            can see.
          </div>

          <div class="flex items-center justify-between">
            <div class="flex items-center space-x-2">
              <img src="./assets/Like.svg" alt="" />
              <div class="text-xl text-gray-500">2</div>
            </div>
            <div class="text-xl text-gray-500">March 2, 2021</div>
          </div>
        </div>
        <!-- card -->
        <div
          class="
            flex flex-col
            bg-white
            p-5
            rounded-xl
            space-y-5
            shadow-md
            hover:scale-105
            transition-all
            hover:shadow-lg
          "
        >
          <div class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <img
                src="./assets/userAvatar04.svg"
                alt="userAvatar01"
                class="w-16 h-16"
              />
              <div class="flex flex-col">
                <div class="text-lg font-semibold">Jack Scott</div>
                <div class="text-sm text-gray-500">@jackscott_</div>
              </div>
            </div>

            <div class="">
              <img
                src="../src/assets/Twitter(Blue).svg"
                alt="Twitter"
                class="w-10 h-10"
              />
            </div>
          </div>

          <div class="text-xl text-gray-500">
            I initially started using Chirp to support the co-founder as I
            personally knew him, but after having tried it out for a few weeks,
            I can genuinely say this changed my Twitter game.
          </div>

          <div class="flex items-center justify-between">
            <div class="flex items-center space-x-2">
              <img src="./assets/Like.svg" alt="" />
              <div class="text-xl text-gray-500">32</div>
            </div>
            <div class="text-xl text-gray-500">March 2, 2021</div>
          </div>
        </div>
        <!-- card -->
        <div
          class="
            flex flex-col
            bg-white
            p-5
            rounded-xl
            space-y-5
            shadow-md
            hover:scale-105
            transition-all
            hover:shadow-lg
          "
        >
          <div class="flex items-center justify-between">
            <div class="flex items-center space-x-3">
              <img
                src="./assets/userAvatar02.svg"
                alt="userAvatar01"
                class="w-16 h-16"
              />
              <div class="flex flex-col">
                <div class="text-lg font-semibold">Jessica May</div>
                <div class="text-sm text-gray-500">@jmay98</div>
              </div>
            </div>

            <div class="">
              <img
                src="./assets/Twitter(Blue).svg"
                alt="Twitter"
                class="w-10 h-10"
              />
            </div>
          </div>

          <div class="text-xl text-gray-500">
            Absolutely love everything about Chirp, from the design to how
            everything works smoothly.
          </div>

          <div class="flex items-center justify-between">
            <div class="flex items-center space-x-2">
              <img src="./assets/Like.svg" alt="" />
              <div class="text-xl text-gray-500">221</div>
            </div>
            <div class="text-xl text-gray-500">March 2, 2021</div>
          </div>
        </div>
      </div>
    </div>

    <!-- plans section -->
    <div
      class="
        bg-white
        flex flex-col
        justify-center
        items-center
        p-5
        md:p-10
        xl:px-40
      "
    >
      <div class="text-4xl font-bold mb-2">One simple price plan.</div>
      <div class="text-lg text-gray-500 w-2/3 text-center">
        Start growing your Twitter account by analyzing your follower's
        patterns.
      </div>

      <div
        class="
          mt-10
          border border-[#e9a42d]
          p-10
          bg-[#FBF8F3]
          rounded-xl
          flex flex-col
          w-full
          divide-y-2
          space-y-5
          md:max-w-md
        "
      >
        <div class="space-y-2 flex flex-col">
          <div class="text-3xl text-gray-500 font-thin">Monthly</div>
          <div class="flex items-end">
            <div class="font-extrabold text-[5rem] leading-[1] text-gray-900">
              $9
            </div>
            <div class="text-2xl text-gray-500">/mo</div>
          </div>
        </div>
        <div class="flex flex-col py-5">
          <div class="flex items-start space-x-3 mb-5">
            <img src="./assets/Checkmark.svg" alt="Checkmark" />
            <div class="text-2xl text-gray-500 font-thin">
              Unlimited* scheduled tweets and threads.
            </div>
          </div>
          <div class="flex items-start space-x-3 mb-5">
            <img src="./assets/Checkmark.svg" alt="Checkmark" />
            <div class="text-2xl text-gray-500 font-thin">
              Schedule up to 3 weeks in advance.
            </div>
          </div>
          <div class="flex items-start space-x-3 mb-5">
            <img src="./assets/Checkmark.svg" alt="Checkmark" />
            <div class="text-2xl text-gray-500 font-thin">
              Real-time audience analytics tracking up 5k followers.
            </div>
          </div>
        </div>
        <div class="flex flex-col">
          <button
            class="
              scale-110
              mt-10
              bg-[#1DA1F2]
              flex
              items-center
              justify-center
              space-x-3
              py-3
              px-5
              rounded-lg
              hover:bg-[#1a89ce]
              transition-colors
              xl:py-6 xl:px-8
            "
          >
            <img src="./assets/Twitter.svg" alt="Start trial with twitter" />
            <span class="text-white font-semibold text-2xl">
              Start trial with twitter
            </span>
          </button>
        </div>
      </div>
    </div>

    <!-- footer -->
    <footer
      class="
        flex flex-col
        md:flex-row
        items-start
        justify-between
        pt-10
        p-5
        md:p-10
        xl:px-40
        bg-[rgb(215,245,245)]
        space-y-2
      "
    >
      <div class="text-blue-500 text-2xl font-black italic">Chirp.</div>
      <div class="flex items-center space-x-3">
        <img src="./assets/Twitter(Black).svg" alt="Twitter" />
        <a href="#" class="text-black text-xl">Privacy Policy</a>
        <a href="#" class="text-black text-xl">Terms of Use</a>
      </div>
    </footer>
  </div>
</template>

<style>
</style>
