---
sidebar: auto
---

<div class="blob-container">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 500" class="blob">
    <path
      d="M106.5,22.4C86.5,2.5,55.4,4.1,35.1,23.7S1,72.2,2.3,96.7C3.6,121.3,37.5,160.6,47.2,192.9S22.3,269.6,40.8,292.9
      c18.6,23.3,51.7,42.2,73.4,41.5c21.7-0.7,32-28.7,52.5-48.3c20.6-19.5,52-30.6,56.8-53.3s-8.2-46.3-3.1-68.3
      c5-22,28.1-35.4,38.3-32.2C189.1,127.4,160.9,124.6,137.5,121s-47.4-10.8-52.3-28.2C82.3,56.6,127.5,42.3,106.5,22.4z"
    />
  </svg>
</div>

<style scoped>
.blob-container {
  position: absolute;
  width: 100%;
  height: 100%;
  overflow: hidden;
  top: 0;
  left: 0;
  z-index: -1;
}

.blob {
  position: absolute;
  width: 100%;
  height: 100%;
  top: -10%;
  left: -10%;
  fill: #3498db; /* Change color as needed */
  animation: moveBlob 10s infinite linear;
}

@keyframes moveBlob {
  0% {
    transform: translate(0, 0);
  }
  100% {
    transform: translate(10%, 10%);
  }
}
</style>

# Welcome to the FTC Starter Pack!

<img src="https://github.com/vintheruler1/FTC-Starter-Pack/blob/main/images/Banner.png?raw=true">

## Getting Started

This FTC starter pack was mainly used to teach the team 5467 how to code during FTC Centerstage. So this will be using SDK and FTC Robot Controller version 9.0.1.

### Prerequisites

You will need to have Android Studio installed on your computer. You can download it [here](https://developer.android.com/studio).

Java 8 is also required. You can download it [here](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html).

### Installing

First, you will need to download the starter pack. You can do this by clicking the green button that says "Clone or download" and then click "Download ZIP".

<img src="https://github.com/vintheruler1/FTC-Starter-Pack/blob/main/images/github_clone.png?raw=true" width=25% height=25%>

Then, you will need to unzip the file. You can do this by right clicking the file and clicking "Extract All".

You can now open the project in Android Studio. You can do this by opening Android Studio and clicking "Open an existing Android Studio project". Then, you will need to find the folder that you just unzipped and click "Open".

Congratulations! You have now installed the starter pack!
