<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>tailwind</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  </head>

  <body class="bg-[#121214]">
    <header class="w-[1280px] m-[auto]">
      <nav class="flex gap-[30px] items-center justify-between pt-[20px]">
        <div class="flex items-center justify-center gap-[30px]">
          <img class="w-[97px] h-[30px]" src="images/splice.png" alt="" />
          <ol class="text-[#A6A8AD] text-[16px] flex gap-[20px]">
            <a class="hover:text-[white]" href="#"><li>Sounds</li></a>
            <a class="hover:text-[white]" href="#"><li>Skills</li></a>
            <a class="hover:text-[white]" href="#"><li>Plugins</li></a>
            <a class="hover:text-[white]" href="#"><li>Studio</li></a>
            <a class="hover:text-[white]" href="#"><li>Community</li></a>
            <a class="hover:text-[white]" href="#"><li>Blog</li></a>
            <a class="hover:text-[white]" href="#"><li>Pricing</li></a>
          </ol>
        </div>

        <div>
          <button
            class="w-[95px] h-[35px] bg-[white] rounded-[20px] hover:bg-[transparent] hover:text-[white]"
          >
            Sign up
          </button>
        </div>
      </nav>
    </header>
    <main class="mt-[30px]">
      <section class="bg-no-repeat bg-cover">
        <img class="w-[100%]" src="images/bg.jpg" alt="" />
      </section>
      <section class="w-[1400px] m-[auto] mt-[30px]">
        <h2 class="text-[white] text-[28px] text-center">About Catalog</h2>
        <div class="flex justify-between items-center">
          <div>
            <h2 class="text-[white] text-[28px]">
              A catalog so deep, it’s dangerous.
            </h2>
            <p class="text-[white] mt-[15px]">
              Expertly created and curated samples in any style imaginable.
              Start swimming in sound.
            </p>
            <button
              class="w-[159px] h-[36px] text-[white] text-center mt-[18px] bg-[#0033FF]"
            >
              Explore Sounds
            </button>
          </div>
          <div>
            <img src="images/songs.png" alt="" />
          </div>
        </div>
      </section>
      <section class="w-[1400px] m-[auto] mt-[30px]">
        <div class="flex justify-between items-center">
          <div>
            <img src="images/sound.png" alt="" />
          </div>
          <div>
            <h2 class="text-[white]">A workflow that actually flows.</h2>
            <p class="w-[422px] text-[white] mt-[15px]">
              Preview samples in your track’s key and tempo, drag and drop
              sounds into your DAW, and organize your favorite samples, MIDI and
              presets in one place.
            </p>
            <button
              class="w-[159px] h-[36px] text-[white] text-center mt-[18px] bg-[#0033FF]"
            >
              Workflow
            </button>
          </div>
        </div>
      </section>
      <section class="w-[1400px] m-[auto] mt-[100px] mb-[50px]">
        <div class="flex justify-evenly items-center">
          <div class="w-[361px] bg-[white] p-[32px]">
            <img src="images/box-1.jpg" alt="" />
            <p class="mt-[30px] text-[20px]">
              I can always find what I’m looking for on Splice, whether it’s the
              exact sound I want or just a bit of inspiration.
            </p>
            <p class="text-[#767676] text-[14px] mt-[16px]">Andrew Huang</p>
          </div>
          <div class="w-[361px] bg-[white] p-[32px]">
            <img src="images/box-2.jpg" alt="" />
            <p class="mt-[30px] text-[20px]">
              I can always find what I’m looking for on Splice, whether it’s the
              exact sound I want or just a bit of inspiration.
            </p>
            <p class="text-[#767676] text-[14px] mt-[16px]">KSHMR</p>
          </div>
          <div class="w-[361px] bg-[white] p-[32px]">
            <img src="images/box-3.jpg" alt="" />
            <p class="mt-[30px] text-[20px]">
              I can always find what I’m looking for on Splice, whether it’s the
              exact sound I want or just a bit of inspiration.
            </p>
            <p class="text-[#767676] text-[14px] mt-[16px]">Kesha Lee</p>
          </div>
        </div>
      </section>
    </main>
    <footer class=" bg-[#344346]">
      <nav class="flex gap-[30px] items-center justify-between pt-[20px] w-[1280px] m-[auto] h-[78px] ">
        <div class="flex items-center justify-center gap-[30px]">
          <p class=" text-[#A6A8AD] hover:text-[white] text-[12px]">© 2022 Splice.com All Rights Reserved</p>
          <ol class="text-[#A6A8AD] text-[16px] flex gap-[20px]">
            <a class="hover:text-[white] text-[12px]" href="#"><li>Terms of Use</li></a>
            <a class="hover:text-[white] text-[12px]" href="#"><li>Privacy Policy</li></a>
            <a class="hover:text-[white] text-[12px]" href="#"><li>Jobs</li></a>
            <a class="hover:text-[white] text-[12px]" href="#"><li>Contact</li></a>
            <a class="hover:text-[white] text-[12px]" href="#"><li>Help</li></a>
          </ol>
        </div>
      </nav>
    </footer>
  </body>
</html>
