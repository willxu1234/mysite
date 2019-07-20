<script>
  import Card from "../components/Card.svelte";
</script>

<style>
  .left {
    /* margin-right: 2vw; */
    width: 100%;
    color: white;
  }
  .right {
    /* margin-left: 2vw; */
    width: 100%;
    color: white;
  }

  .right ul li a {
    color: rgb(0, 204, 255);
  }

  .project {
    margin-bottom: 0.1em;
  }

  .date {
    margin-top: 0;
    color: rgb(180, 180, 180);
    font-size: 0.8em;
  }
</style>

<svelte:head>
  <title>Projects</title>
</svelte:head>

<h1>Projects</h1>

<Card duration={400}>
  <span class="left" slot="left">
    <h2 class="project">Native Web Components</h2>
    <h4 class="date">
      <em>Mar 2019 - Jun 2019</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Built an easily pluggable, native web component library using vanilla
        JavaScript, HTML, and CSS.
      </li>
      <li>
        Created a script allowing code coverage utilities to accurately parse
        test files for comprehensiveness.
      </li>
      <li>
        Mimicked a real life work setting by operating in a team of ten, while
        satisfying the demands of an investor.
      </li>
      <li>
        <a href="https://github.com/ucsd-cse112/team13" target="_blank">
          See the code
        </a>
      </li>
    </ul>
  </span>
</Card>
<Card duration={800}>
  <span class="left" slot="left">
    <h2 class="project">Waverider Rideshare App</h2>
    <h4 class="date">
      <em>Sep 2018 - Dec 2018</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>Worked in a ten person team to mimic actual software teams.</li>
      <li>
        Connected drivers with empty spaces in their cars with riders to
        circumvent UCSD's suboptimal public transportation system.
      </li>
      <li>
        Built REST APIs using NodeJS and Express to handle a variety of driver
        and rider use cases.
      </li>
      <li>
        Developed the interface using ReactNative to expedite development
        without compromising quality.
      </li>
      <li>
        Drafted and presented reports about the various features of the app.
      </li>
    </ul>
  </span>
</Card>
<Card duration={1200}>
  <span class="left" slot="left">
    <h2 class="project">Theta Tau LED Speakers</h2>
    <h4 class="date">
      <em>Sep 2018 - Dec 2018</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Selected and interfaced a WS2801 LED strip with a Raspberry Pi through
        SPI connection.
      </li>
      <li>
        Took GPIO readings and used a Python3 script to reindex each LED in a
        matrix to match the orientation of the lights on the speaker.
      </li>
      <li>
        Created a drawing interface to expedite and simplify drawing pictures on
        the screen for other group members to use.
      </li>
      <li>
        Displayed dynamic personalized messages on the LED matrices using a
        sliding-window approach.
      </li>
      <li>Added a rainbow effect.</li>
      <li>
        Internalized criticism and swiftly made changes accordingly, in a matter
        similar to that of a corporate setting.
      </li>
      <li>
        <a
          href="https://github.com/willxu1234/tt_build_project"
          target="_blank"
          rel="noopener">
          See the code
        </a>
      </li>
    </ul>
  </span>
</Card>
<Card duration={1600}>
  <span class="left" slot="left">
    <h2 class="project">HQ Trivia Video Analysis Script</h2>
    <h4 class="date">
      <em>Apr 2018 - Jun 2018</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Programmed a Jupyter notebook to use screen-capture OCR to detect and
        categorize questions from a pre-recorded HQ trivia video.
      </li>
      <li>
        Employed BeautifulSoup to scrape Google search metadata and predict the
        answer.
      </li>
      <li>Able to correctly guess answers 70% of the time.</li>
      <li>
        <a
          href="https://github.com/willxu1234/HQ_video_analysis/"
          target="_blank"
          rel="noopener">
          See the code
        </a>
      </li>
    </ul>
  </span>
</Card>
<Card duration={2000}>
  <span class="left" slot="left">
    <h2 class="project">Self-driving RC Car</h2>
    <h4 class="date">
      <em>Apr 2018 - Jun 2018</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Constructed and trained a self-driving RC car running an open-source
        library (
        <a href="http://www.donkeycar.com/" target="_blank">
          Donkey Car
        </a>
        ) on a Raspberry Pi.
      </li>
      <li>
        Performed off-board model training on UCSD’s supercomputer center’s GPU
        cluster.
      </li>
      <li>
        Injected code into the donkey framework interfacing an open-source,
        voice-recognition API (
        <a
          href="https://github.com/bishoph/sopare"
        
          target="_blank">
          SoPaRe
        </a>
        ) and onboard Raspberry Pi to allow for voice control of the vehicle.
      </li>
    </ul>
  </span>
</Card>
<Card duration={2400}>
  <span class="left" slot="left">
    <h2 class="project">Alpha Phi Omega Website</h2>
    <h4 class="date">
      <em>Dec 2016 - Jun 2017</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Was a member of the webmaster committee for two consecutive quarters.
      </li>
      <li>Created mockups for new potential website designs.</li>
      <li>
        Employed Ruby on Rails to add two features to the UCSD chapter of Alpha
        Phi Omega's website.
      </li>
      <li>
        Collaborated in a Git-based team environment using Atlassian BitBucket.
      </li>
    </ul>
  </span>
</Card>
<Card duration={2800}>
  <span class="left" slot="left">
    <h2 class="project">ECE 5 Line-Following Car</h2>
    <h4 class="date">
      <em>Nov 2016 - Dec 2016</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>Connected an Arduino to an RC car to follows a dark line.</li>
      <li>Assembled and adjusted a PID controller to ensure line fidelity.</li>
      <li>Won the class competition for best overall car.</li>
    </ul>
  </span>
</Card>
<Card duration={3200}>
  <span class="left" slot="left">
    <h2 class="project">Web-based Motion Sensor</h2>
    <h4 class="date">
      <em>Sep 2016 - Dec 2016</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Led a group of four to participate in IEEE's quarterly project; the
        theme being data-driven web design.
      </li>
      <li>
        Developed a website running on the Raspberry Pi using the MEAN stack.
      </li>
      <li>
        Separately assembled a motion sensor, of which the output data was
        displayed dynamically through the web server.
      </li>
    </ul>
  </span>
</Card>
