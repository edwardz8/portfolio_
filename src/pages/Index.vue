<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Zach Edwards</div>
        <div class="leading-tight subtitle-color">Frontend Engineer</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/undraw_code.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div>
    <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">
        Hello and welcome! My name is Zach and I'm a frontend engineer motivated to deliver user experiences people will not just enjoy but one that will improve their daily lives and help connect them with others. 
        I am always learning and have an undeniable passion for technology and curiosity for app design as well as cloud computing, containerization and data visualization. I'm in search of a team I can contribute to, help grow, learn from and dedicate my time and energy too for years to come.
        
        <br/><br/><span class="about_me_break">Check out the source code of some of my work on</span>
        <a
          class="github-link"
          href="https://github.com/edwardz8"
        > GitHub</a>. You can also demo and view code of my most recent personal projects below.
      </p>

       <p class="text-lg sm:text-xl mt-6"
      >The RotoRink Player Rater is a full-stack project built with SQL, Node.js and React along with its current technologies, including React Hooks and the Context state management API.</p>

      <div class="items-center py-6">
        <div class="flex flex-col justify-between items-center mb-16">
          <h2 class="font-bold mt-6 mb-6">RotoRink Player Rater</h2>
          <g-image src="../../static/player_rater.png" class="mb-6"></g-image>
          <div class="sm:flex sm:items-center flex-wrap">
            <a
              href="https://rotorinkplayerrater.netlify.com"
              class="text-xs font-semibold rounded-full px-4 py-1 mx-3 leading-normal bg-white border border-blue text-blue hover:text-black"
            >Demo</a>
            <a
              href="https://github.com/edwardz8/player-rater"
              class="text-xs font-semibold rounded-full px-4 py-1 mx-3 leading-normal bg-white border border-blue text-blue hover:text-black"
            >Client Code</a>
            <a
              href="https://github.com/edwardz8/player-rater-server"
              class="text-xs font-semibold rounded-full px-4 py-1 leading-normal bg-white border border-purple text-purple hover:text-black"
            >Server Code</a>
          </div>
        </div>
      </div>
    </div>

    

    <div class="container-inner mx-auto">
      <p
        class="text-lg sm:text-xl"
      >Basebook is front-end project with with Vue.js and Firebase and allows users to look up player stats and comment on their favorite teams and players.</p>

      <div class="items-center py-6 mt-6">
        <div class="flex flex-col justify-between items-center mb-16">
          <h2 class="font-bold mt-6 mb-6">Basebook</h2>
          <g-image src="../../static/0.png" class="mb-6"></g-image>
          <div class="sm:flex sm:items-center flex-wrap">
            <a
              href="http://basebook11.surge.sh/"
              class="text-xs font-semibold rounded-full px-4 py-1 mx-3 leading-normal bg-white border border-blue text-blue hover:text-black"
            >Demo</a>
            <a
              href="https://github.com/edwardz8/vue-basebook"
              class="text-xs font-semibold rounded-full px-4 py-1 leading-normal bg-white border border-purple text-purple hover:text-black"
            >Code</a>
          </div>
        </div>
      </div>
    </div>

      <div class="container-inner mx-auto">
      <p
        class="text-lg sm:text-xl"
      >RotoLinks is a personal project I've dedicated my free time to as well. My end goal for the fantasy golf draft app is to implement paypal so users can enter small golf drafts to compete with their friends and distribute the collective cash prize to whoever picks the best plays, which will be based off the lowest total score. It also contains a live leaderboard of the current European or PGA tournament.</p>

      <div class="items-center py-6">
        <div class="flex flex-col justify-between items-center mb-16">
          <h2 class="font-bold mt-6 mb-6">RotoLinks</h2>
          <g-image src="../../static/rotolinks-img.png" class="mb-6"></g-image>
          <div class="sm:flex sm:items-center flex-wrap">
            <a
              href="http://rotolinks5.surge.sh/"
              class="text-xs font-semibold rounded-full px-4 py-1 mx-3 leading-normal bg-white border border-blue text-blue hover:text-black"
            >Demo</a>
            <a
              href="https://github.com/edwardz8/rotolinks"
              class="text-xs font-semibold rounded-full px-4 py-1 leading-normal bg-white border border-purple text-purple hover:text-black"
            >Code</a>
          </div>
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden education-container">
      <div
        class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative"
      >
        <h2 class="font-bold mb-6" id="projects">Experience and Education</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

        <ul class="text-md sm:text-l">
           <li class=" mb-6">
            <div>Frontend Developer - Ministry Brands</div>
            <div class="text-sm text-gray-600">2020-Present</div>
            <div
              class="text-md text-gray-600"
            >Develop user experiences with javascript, html and css/sass in an agile development environment.</div>
          </li>
          <li class=" mb-6">
            <div>Front-end Developer - Metadata Technology North America</div>
            <div class="text-sm text-gray-600">2018-2020</div>
            <div
              class="text-md text-gray-600"
            >Technologies include: Angular, TypeScript and RxJS. Docker. Highcharts. NGRX. Vue. Work with large API datasets in an agile development environment.</div>
          </li>
          <li class=" mb-6">
            <div>Web Developer - K2 Alliance Group</div>
            <div class="text-sm text-gray-600">2017</div>
            <div
              class="text-md text-gray-600"
            >Led development team across all tiers of front-end and database management, including troubleshooting, integrating plug-ins and requesting external API data.</div>
          </li>
          <li class="checkmark mb-6">
            <div>Frontend Developer Program - The Iron Yard</div>
            <div class="text-sm text-gray-600">2017</div>
            <div class="text-lg text-gray-600">The Iron Yard Boot Camp - Nashville, TN</div>
          </li>
          <li class="checkmark mb-6">
            <div>M.A. English Education</div>
            <div class="text-sm text-gray-600">2012-2014</div>
            <div class="text-lg text-gray-600">Tennessee Technological University</div>
          </li>
          <li class="checkmark mb-6">
            <div>B.S. English and Speech</div>
            <div class="text-sm text-gray-600">2011-2012</div>
            <div class="text-lg text-gray-600">Tennessee Technological University</div>
          </li>
        </ul>
      </div>
      <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6" id="about">Zach's Stack:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div>
            <g-image
              src="../../static/profile_pic_2020.jpeg"
              alt="avatar"
              class="w-32 h-32 rounded-full mb-8 lg:mb-0"
            />
          </div>
          <div class="flex-1 text-lg sm:text-xl ml-6">
            <p>
              I've worked with JavaScript - along with several other languages - and a number of its libraries 
              and frameworks, for over 3 years and as my programming skills grow so does
               my passion and curiosity for cloud and test-driven development as well as data visualization. When I'm not learning about the latest and greatest technologies, building sites with GraphQL and Vue or React and completing labs on A Cloud Guru or coding challenges on LeetCode, you can find me on the golf course ( I'm currently between a 5 and 6 handicap ) working on my game, playing fantasy sports or spending time with my lovely wife, Alicia. I'm also a published fiction writer. To learn more about me you can find my resume on
              <a
                class="github-link"
                href="https://www.linkedin.com/in/zach-edwards-905b105a/"
              >LinkedIn</a>.
            </p>
          </div>
        </div>

        <div class="grid-row">
           <div>
            <h3>React</h3>
            <g-image src="../../static/react.svg" class="w-32 h-32 rounded-full mb-8 lg:mb-0" />
          </div>
          <div>
            <h3>Node</h3>
            <g-image src="../../static/node.png" class="w-32 h-32 rounded-full mb-8 lg:mb-0" />
          </div>
          <div>
            <h3>MongoDB</h3>
            <g-image src="../../static/mongodb.png" class="w-32 h-32 rounded-full mb-8 lg:mb-0" />
          </div>
          <div>
            <h3>GraphQL</h3>
            <g-image
              src="../../static/GraphQL_Logo.png"
              class="w-32 h-32 rounded-full mb-8 lg:mb-0"
            />
          </div>
           <div>
            <h3>Vue</h3>
            <g-image src="../../static/vue.png" class="w-32 h-32 rounded-full mb-8 lg:mb-0" />
          </div>
           <div>
            <h3>AWS</h3>
            <g-image src="../../static/aws1.png" class="w-32 h-32 rounded-full mb-8 lg:mb-0" />
          </div>
          <div>
            <h3>Docker</h3>
            <g-image src="../../static/docker.png" class="w-32 h-32 rounded-full mb-8 lg:mb-0" />
          </div>
          <div>
            <h3>SQL</h3>
            <g-image src="../../static/sql.png" class="w-32 h-32 rounded-full mb-8 lg:mb-0" />
          </div>
        </div>

        <!-- Youtube Video -->
        <!-- <div class="responsive-container">
          <object
            class="responsive-iframe w-full h-full top-0 left-0 border-0"
            src="../../static/bb_search.mov"
          ></object>
        </div>-->
      </div>
      <!-- end get-to-know me -->
    </div>

    <div class="overflow-x-hidden">
      <div class="contact-me bg-background-secondary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6" id="contact">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px">
              <use xlink:href="#dots-triangle" />
            </svg>
          </div>

          <div class="text-lg sm:text-lg mb-16">
            <form class="mb-12" name="contact" method="post" netlify action="/">
              <input type="hidden" name="form-name" value="contact" />
              <div class="flex flex-wrap mb-6 -mx-4">
                <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                  <label class="block mb-2 text-copy-primary" for="name">Name</label>

                  <input
                    type="text"
                    name="name"
                    id="name"
                    placeholder="Jon Snow"
                    class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4"
                    required
                  />
                </div>

                <div class="w-full px-4 md:w-1/2">
                  <label class="block text-copy-primary mb-2" for="email">Email Address</label>

                  <input
                    type="email"
                    name="email"
                    id="email"
                    placeholder="email@example.com"
                    class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4"
                    required
                  />
                </div>
              </div>

              <div class="w-full mb-12">
                <label class="block text-copy-primary mb-2" for="message">Message</label>

                <textarea
                  id="message"
                  rows="5"
                  name="message"
                  class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none appearance-none focus:border-green-700 mb-2 px-4 py-4"
                  placeholder="Enter your message here."
                  required
                ></textarea>
              </div>

              <div class="flex justify-end w-full">
                <input
                  type="submit"
                  value="Submit"
                  class="block bg-black hover:bg-blue-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3"
                />
              </div>
            </form>
          </div>
        </div>
      </div>
      <!-- end contact-me -->
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Home"
  }
};
</script>

<style scoped>
.subtitle-color,
.github-link {
  color: #1493ff;
}
.grid-row {
  display: flex;
  flex-wrap: wrap;
}
.grid-row > div {
  margin: 2rem;
  text-align: center;
}

@media screen and (max-width: 800px) {
  .checkmark,
  .education-container {
    display: none;
  }
}
</style>