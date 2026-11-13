<!-- Palette: cream FFF8F0 · blush F4C2C2 · lavender C8B6E2 · sage B5C9B0 · sky A9C6E0 · ink 5B4B5E -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=C8B6E2&height=210&section=header&text=hi%2C%20i%27m%20aditya&fontSize=50&fontColor=5B4B5E&fontAlign=50&fontAlignY=38&desc=robotics%20%C2%B7%20edge%20ai%20%C2%B7%20computer%20vision&descSize=18&descAlignY=60&descColor=5B4B5E" width="100%" alt="header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3200&pause=900&color=8A6FA8&center=true&vCenter=true&width=560&lines=third-year+ECS+student+%40+Ramdeobaba+%F0%9F%8C%B8;building+drones+that+fly+without+GPS+%F0%9F%9B%B8;making+small+models+run+on+small+computers+%F0%9F%A7%A0;learning+in+public%2C+one+commit+at+a+time+%E2%9C%A8" alt="typing intro" />
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/adi465996"><img src="https://img.shields.io/badge/linkedin-C8B6E2?style=for-the-badge&logo=linkedin&logoColor=5B4B5E" height="34" alt="LinkedIn" /></a>
<a href="mailto:adi465996@gmail.com"><img src="https://img.shields.io/badge/email-F4C2C2?style=for-the-badge&logo=gmail&logoColor=5B4B5E" height="34" alt="Email" /></a>
<a href="https://x.com/AdityaS9766"><img src="https://img.shields.io/badge/x-B5C9B0?style=for-the-badge&logo=x&logoColor=5B4B5E" height="34" alt="X" /></a>

</div>

<br/>

<h2 align="center">🌷 about me</h2>

<p align="center">
I'm a third-year B.Tech student in Electronics &amp; Computer Science at Ramdeobaba University, Nagpur.<br/>
I like the messy middle between AI and hardware: getting models, sensors and flight controllers<br/>
to work together on real devices, and making them <i>reliable</i>, not just impressive.
</p>

<br/>

<h2 align="center">🌿 what i'm up to right now</h2>

<table align="center">
  <tr>
    <td align="center" width="260">🚁<br/><b>leading NIDAR</b><br/><sub>team of 10, building a Gazebo simulation and an exploration stack for a GPS-denied drone</sub></td>
    <td align="center" width="260">🚗<br/><b>VehicleGPT</b><br/><sub>an offline, in-vehicle assistant you can ask questions about your car's logs</sub></td>
    <td align="center" width="260">📚<br/><b>learning</b><br/><sub>C++ (Cherno series) and Andrew Ng's ML/DL specializations</sub></td>
  </tr>
</table>

<br/>

<h2 align="center">🪴 projects</h2>

<table align="center">
  <tr>
    <td valign="top" width="50%">
      <h3>🚁 NIDAR: GPS-denied autonomous drone</h3>
      <p><sub><b>role:</b> team lead (10 people)</sub></p>
      <ul>
        <li>ROS 2 + Gazebo + ArduPilot SITL simulation</li>
        <li>MAVROS pipeline to control the drone from a Jetson</li>
        <li>LiDAR filter node that drops readings while the drone is tilted, feeding EKF3 (ExternalNav)</li>
        <li>Lightweight C++ ORB detection (also tried AKAZE and Canny)</li>
        <li>ArUco marker position correction for landing</li>
        <li>Exploring Nav2 for safe exploration under a tight Jetson compute budget</li>
      </ul>
      <p><sub><code>ROS 2</code> <code>Gazebo</code> <code>ArduPilot</code> <code>MAVROS</code> <code>C++</code> <code>Jetson</code> <code>OpenCV</code></sub></p>
      <p><sub>🏅 Reached the pre-final rounds at the ISRO Robotics Challenge (IRoC-U 2026), working on computer vision</sub></p>
    </td>
    <td valign="top" width="50%">
      <h3>🚗 VehicleGPT: Tata Elxsi Teliport S4</h3>
      <p><sub><b>status:</b> Round 1 submitted</sub></p>
      <ul>
        <li>Offline natural-language search over vehicle CAN-style logs</li>
        <li>Design rule: <i>the model translates, a deterministic engine answers</i>, so numbers come from the database, never from model text</li>
        <li>SQLite time-series store with FTS5 log search and an event ledger</li>
        <li>Qwen2.5-0.5B via llama.cpp with grammar-constrained JSON output</li>
        <li>Tested on a Raspberry Pi with the CPU and RAM limits of a car computer in mind</li>
      </ul>
      <p><sub><code>Python</code> <code>llama.cpp</code> <code>SQLite</code> <code>Raspberry Pi</code> <code>CAN</code></sub></p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>🌾 AgriShield: crop disease &amp; pest detection</h3>
      <p><sub><b>role:</b> ML architecture + backend deployment · Smart India Hackathon</sub></p>
      <ul>
        <li>Multimodal model (image + weather + more) with gated fusion</li>
        <li>Modality dropout and learned "missing" embeddings, so it still works when a farmer can't provide every input</li>
        <li>Offline-first app design for villages with patchy networks</li>
        <li>First crops: rice, wheat, maize and cotton</li>
      </ul>
      <p><sub><code>PyTorch</code> <code>Deep Learning</code> <code>Multimodal Fusion</code> <code>Backend</code></sub></p>
    </td>
    <td valign="top" width="50%">
      <h3>🧪 local AI experiments</h3>
      <ul>
        <li><b>Local AI companion:</b> multi-model setup on Ollama (Gemma, Qwen, DeepSeek) with cold-swap loading, critique loops and a SQLite + ChromaDB memory</li>
        <li><b>Offline psychology assistant:</b> a fine-tuning pipeline for Gemma, from dataset generation (with JSON repair and checkpoint recovery) to ShareGPT JSONL for Unsloth</li>
      </ul>
      <p><sub><code>Ollama</code> <code>Unsloth</code> <code>ChromaDB</code> <code>Fine-tuning</code></sub></p>
    </td>
  </tr>
</table>

<div align="center">
  <br/>
  <a href="https://github.com/Pain-apk/IOT_project">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=pain-apk&repo=IOT_project&bg_color=FFF8F0&title_color=8A6FA8&text_color=5B4B5E&icon_color=F4A9A8&border_color=E9DDF5" alt="IOT_project" />
  </a>
</div>

<br/>

<h2 align="center">🧺 toolbox</h2>

<div align="center">

**robotics &amp; systems**<br/>
<img src="https://skillicons.dev/icons?i=cpp,python,c,linux,docker,git,bash&theme=light" alt="core" />

**ai &amp; vision**<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,sqlite&theme=light" alt="ai" />

<sub>
<b>also work with:</b> ROS 2 · Gazebo · ArduPilot · MAVROS · Nav2 · Jetson · TensorRT · ONNX · llama.cpp · Ollama · ESP32 · Arduino
</sub>

<br/>

<sub>🌱 <i>earlier web experiments:</i> React · Node.js · Django · Next.js · MongoDB</sub>

</div>

<br/>

<h2 align="center">🔧 tinkering shelf</h2>

<p align="center">
<sub>
flashing ESP32 boards with DroneBridge · recovering write-protected SD cards · patching a Linux kernel module for laptop fan control · untangling dual-boot and GPU quirks<br/>
(the kind of thing that never makes a resume but teaches the most)
</sub>
</p>

<br/>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pain-apk&show_icons=true&hide_border=false&include_all_commits=true&count_private=true&bg_color=FFF8F0&title_color=8A6FA8&text_color=5B4B5E&icon_color=F4A9A8&border_color=E9DDF5" height="150" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=pain-apk&layout=compact&langs_count=6&bg_color=FFF8F0&title_color=8A6FA8&text_color=5B4B5E&border_color=E9DDF5" height="150" alt="top languages" />
</div>

<br/>

<div align="center">

<sub><i>"The real danger is not that computers will begin to think like men, but that men will begin to think like computers."</i> · Sydney J. Harris</sub>

<br/><br/>

<sub>thanks for stopping by 🌸 feel free to look around, or say hi.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=F4C2C2&height=110&section=footer" width="100%" alt="footer" />

</div>
