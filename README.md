
<html>
<head>
  <meta charset="UTF-8">
  <title>Application 6 Project - Ride Control System</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      max-width: 900px;
      margin-left: auto;
      margin-right: auto;
      line-height: 1.6;
    }

    h1 {
      color: #2c3e50;
    }

    .video {
      margin-top: 20px;
    }

    iframe {
      width: 100%;
      height: 450px;
    }

    .box {
      background: #f4f4f4;
      padding: 15px;
      border-radius: 8px;
    }
  </style>
</head>

<body>

  <h1>Application 6: Ride Control System</h1>

  <div class="box">
    <p>
      This project is a real-time embedded system that simulates a theme park ride controller.
      It uses an ESP32 with FreeRTOS tasks, sensors, LEDs, and a web dashboard to monitor system state.
    </p>

    <p>
      Key features include:
      <ul>
        <li>Hard real-time emergency stop system (ISR-based)</li>
        <li>RTOS task scheduling for sensors and buttons</li>
        <li>Live web dashboard showing speed and system state</li>
        <li>LED indicators for RUNNING, IDLE, and EMERGENCY modes</li>
      </ul>
    </p>
  </div>

  <h2>System Demo Video</h2>
  
  <div class="video">
    <iframe 
      src="https://www.youtube.com/embed/Ms8Xfg48YRk"
      frameborder="0"
      allowfullscreen>
    </iframe>
  </div>

  <h2>About the System</h2>

  <div class="box">
    <p>
      The system models a theme park ride safety controller in Orlando.
      It prioritizes emergency interrupts (ISR) as hard real-time events,
      while the web dashboard and LED indicators operate as soft real-time features.
    </p>

    <p>
      Technologies used:
      ESP32, FreeRTOS, WiFi server, GPIO interrupts, and web UI (HTML + JavaScript).
    </p>
  </div>

  <h2>Link To The Application</h2>
  <div class="box">
    https://wokwi.com/projects/462501431991802881
  </div>

</body>
</html>
