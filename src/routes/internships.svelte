<script>
  import Card from "../components/Card.svelte";
</script>

<style>
  .left {
    margin-right: 2em;
    width: 100%;
  }
  .right {
    margin-left: 2em;
    width: 100%;
  }

  span.location {
    font-size: 0.6em;
  }

  img.border {
    border: 2px black solid;
    margin-bottom: -0.3em;
  }

  img.border {
    border: 2px white solid;
    margin-bottom: -0.3em;
  }
</style>

<svelte:head>
  <title>Internships</title>
</svelte:head>

<h1>Internships</h1>

<Card color="black">
  <span class="left" slot="left">
    <h1>
      <img src="icons/msft.png" alt="" width="50em" class="border" />
      Microsoft
      <span class="location">- Cambridge, MA</span>
    </h1>
    <h4>
      <em>June 2019 - September 2019</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Changed absolute timestamps to friendly timestamps in comments on Office
        for web, iOS, Android, and Win32 using TypeScript/React/Redux build on
        top of a C# application
      </li>
      <li>
        Designed a detailed spec, complete with design requirements and metrics
        to measure success
      </li>
      <li>
        Designed a detailed spec, complete with design requirements and metrics
        to measure success
      </li>
    </ul>
  </span>
</Card>

<Card color="white">
  <span class="left" slot="left">
    <h1>
      <img src="icons/nuro.png" alt="" width="50em" class="border" />
      Nuro
      <span class="location">- Mountain View, CA</span>
    </h1>
    <h4>
      <em>June 2018 - September 2018</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Discussed progress and goals in a weekly meeting with the CEO and a
        small, but vital team.
      </li>
      <li>
        Developed a module in a Publish-Subscribe framework that ensures the
        quality of sensor data.
      </li>
      <li>
        Created a packet multiplexer to categorize high quantities of incoming
        real-time data.
      </li>
      <li>
        Projected map features onto camera frames in real-time using OpenCV and
        OpenGL renderables.
      </li>
      <li>
        Refactored pre-existing code by exposing functionality, enabling its use
        in other classes.
      </li>
    </ul>
  </span>
</Card>
<Card color="black">
  <span class="left" slot="left">
    <h1>
      <img src="icons/velo.png" alt="" width="50em" class="white-border" />
      Velodyne
      <span class="location">- San Jose, CA</span>
    </h1>
    <h4>
      <em>June 2016 - September 2016</em>
    </h4>
    <h4>
      <em>June 2017 - September 2017</em>
    </h4>
  </span>
  <span class="right" slot="right">
    <ul>
      <li>
        Coded several Python and Matlab scripts to ensure proper functionality
        of LiDAR sensors.
      </li>
      <li>
        Devised experiments to simulate Dual LiDAR point returns using office
        architecture to save company money without compromising quality.
      </li>
      <li>
        Upgraded the sensor’s web interface with a new ‘Manual Mode’ feature.
      </li>
      <li>
        Fabricated and coded an Arduino-based tachometer to precisely measure
        the RPM of a sensor.
      </li>
      <li>
        Updated a test script to control a ThorLabs motor, building an interface
        for the script and DLL.
      </li>
    </ul>
  </span>
</Card>
