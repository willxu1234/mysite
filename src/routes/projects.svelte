<script>
  import Card from "../components/Card.svelte";
</script>

<style>
  .left {
    margin-right: 2vw;
    width: 100%;
  }
  .right {
    margin-left: 2vw;
    width: 100%;
  }

  .right ul li a {
    color: rgb(245, 245, 131);
  }
</style>

<svelte:head>
  <title>Projects</title>
</svelte:head>

<h1>Projects</h1>

<Card color="white">
  <span class="left" slot="left">
    <h1>Native Web Components</h1>
    <h4>
      <em>March 2019 - June 2019</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Built an easily pluggable, native web component library using vanilla
        JavaScript, HTML, and CSS
      </li>
      <li>
        Created a script allowing code coverage utilities to accurately parse
        test files for comprehensiveness
      </li>
      <li>
        <a href="https://github.com/ucsd-cse112/team13" target="_blank">
          See the code
        </a>
      </li>
    </ul>
  </span>
</Card>
<Card color="black">
  <span class="left" slot="left">
    <h1>Waverider Rideshare App</h1>
    <h4>
      <em>September 2018 - December 2018</em>
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
<Card color="white">
  <span class="left" slot="left">
    <h1>Theta Tau LED Speakers</h1>
    <h4>
      <em>September 2018 - December 2018</em>
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
<Card color="black">
  <span class="left" slot="left">
    <h1>HQ Trivia Video Analysis Script</h1>
    <h4>
      <em>April 2018 - June 2018</em>
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
<Card color="white">
  <span class="left" slot="left">
    <h1>Self-driving RC Car</h1>
    <h4>
      <em>April 2018 - June 2018</em>
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
<Card color="black">
  <span class="left" slot="left">
    <h1>Alpha Phi Omega Website</h1>
    <h4>
      <em>December 2016 - June 2017</em>
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
<Card color="white">
  <span class="left" slot="left">
    <h1>ECE 5 Line-Following Car</h1>
    <h4>
      <em>November 2016 - December 2016</em>
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
<Card color="black">
  <span class="left" slot="left">
    <h1>Web-based Motion Sensor</h1>
    <h4>
      <em>September 2016 - December 2016</em>
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