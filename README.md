# awesome-microbits-ks2
A primary-school-focused filter of [carlosperate/awesome-microbit](https://github.com/carlosperate/awesome-microbit). 
Curated for **extension activities for more able KS2 pupils and primary code clubs**.

Sections removed entirely: C/C++, Rust, Ada, Other Languages, Interaction Languages, Programming Tools, Interface Chip, Hardware design, CAD, Projects Using micro:bit as a Dev Board. These are developer, security, or engineering-level content.

> **Want to contribute?** See [CONTRIBUTING.md](CONTRIBUTING.md) for how to suggest resources.
---

## 🗂️ Contents

- [🆚 Visual Programming](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-visual-programming)
- [🐍 Python (for more able KS2 / Y6 extension)](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-python)
- [🗿 MakeCode Extensions](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-makecode-extensions)
- [👩‍💻 Classroom Environments](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-classroom-environments)
- [🎓 Machine Learning (brilliant for code clubs)](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-machine-learning)
- [🧰 micro:bit Tools](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-microbit-tools)
- [📱 Mobile Apps](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-mobile-apps)
- [🅰️ Accessibility / SEND](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-accessibility)
- [🖨️ 3D Printing](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-3d-printing)
- [🎨 2D Design](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-2d-design)
- [🏗️ Project Ideas](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-project-ideas)
- [🗞️ Articles & Tutorials](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-articles)
- [🎥 Videos](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-videos)
- [🧑‍🏫 Teaching Resources](https://claude.ai/chat/849e6a4c-5e36-4f28-acf3-c25adf2c2f42#-teaching-resources)

---

## 🆚 Visual Programming

- **[MakeCode](https://makecode.microbit.org/)** - In-browser emulator with blocks and JavaScript. The mainstream primary choice.
    - [MakeCode Multi Editor](https://makecode.microbit.org/---multi) - Two editors side by side, great for simulating radio between a transmitter and receiver.
- **[Scratch 3.0](https://scratch.mit.edu/microbit)** - Officially compatible with micro:bit via Scratch Link. Excellent bridge for pupils already familiar with Scratch.
- **[EduBlocks](https://app.edublocks.org/)** - Blocks interface that transitions pupils from Scratch to Python. Ideal for Y5/6 extension.
- **[MicroBlocks](https://microblocks.fun/)** - A Scratch-inspired visual language that runs _on_ the micro:bit. Programs persist on the board.
- **[Vittascience](https://vittascience.com/microbit/)** - Block programming based on MicroPython with a built-in simulator.
- **[MicroCode](https://microsoft.github.io/microcode/)** - Icon-based editor for micro:bit V2. Minimal text, suitable for younger learners or those with accessibility needs. Can be used directly on the micro:bit with an Arcade Shield.
- **[Open Roberta Lab](https://lab.open-roberta.org/)** - Block programming for robots, also supports micro:bit.

---

## 🐍 Python

For gifted Y5/6 pupils ready to move beyond blocks.

### Editors

- **[microbit.org Python Editor](https://python.microbit.org/)** - The official online Python editor. Best starting point.
- **[Mu](https://codewith.mu/)** - A beginner-friendly offline Python editor. Specifically designed for young learners and the micro:bit.
- **[Thonny](https://thonny.org/)** - Another beginner-friendly Python IDE with micro:bit support out of the box.
- **[Strype](https://www.strype.org/)** - Combines blocks and text using "Frames". Drag-and-drop real Python. A very strong bridging tool.

### Blocks-to-Python

- **[EduBlocks](https://app.edublocks.org/)** - Blocks that output real Python.
- **[Vittascience](https://vittascience.com/microbit/)** - Blocks with Python view.

---

## 🗿 MakeCode Extensions

A few classroom-relevant extensions. (Heavily filtered - removed all the hardware driver extensions that require soldering or advanced electronics knowledge.)

- **[MakeCode Extensions Gallery](https://makecode.microbit.org/extensions/extension-gallery)** - Official list of approved extensions, searchable directly in the editor.
- **[Lego Power Functions](https://github.com/philipphenkel/pxt-powerfunctions)** - Control LEGO Power Functions motors using your micro:bit with an infrared LED. Brilliant cross-over with LEGO clubs.
- **[timeanddate](https://github.com/bsiever/microbit-pxt-timeanddate)** - Adds a software real-time clock (date and time) to the micro:bit.

---

## 👩‍💻 Classroom Environments

- **[micro:bit classroom](https://classroom.microbit.org/)** - Run and manage live code sessions with MakeCode or Python Editor. Teachers can share code with students, track progress, help debug, and save progress. **Essential for teaching.**
- **[MakeCode classroom assignments](https://makecode.microbit.org/online-learning)** - How to create MakeCode assignments via Google Classroom, Microsoft Teams, and others.

---

## 🎓 Machine Learning

Genuinely brilliant for more able KS2 and code clubs. These tools make ML concepts accessible to primary-age children.

### Tools

- **[ML-Machine](https://ml-machine.org/)** - Interactive machine-learning platform. Uses micro:bit sensors to generate data, train a model, then run it with real-time sensor data streamed via Bluetooth. **Highly recommended.**
- **[MAKE: AI Robots](http://makeairobots.com/)** - Bridges Teachable Machine AI and a micro:bit. Train an AI to recognise images, then use those predictions to control motors and lights.
- **[MicroPal](https://scientiffic.notion.site/MicroPal-Guide-141a70906ea5432599e21cecda2a1fac)** - Make a micro:bit project that responds to your voice. Uses Teachable Machine and Web Bluetooth.
- **[PlushPal](https://www.plushpal.app/)** - Online tool for creating interactive toys. Record custom gestures; the micro:bit reacts using ML.

### Projects & lessons

- **[Dance Detector](https://projects.raspberrypi.org/en/projects/dance-detector/)** - Raspberry Pi Foundation project using CreateAI and micro:bit to train a model that identifies dance moves. **Perfect code-club project.**
- **[Machine learning using the micro:bit](https://www.thenational.academy/teachers/programmes/computing-secondary-ks3/units/machine-learning-using-the-micro-bit/lessons)** - Oak National Academy unit of six lessons. Labelled KS3 but much is accessible for Y6.

---

## 🧰 micro:bit Tools

- **[MakeCode Streamer](https://makecode.com/streamer/docs)** - Simplifies creating coding videos. Useful for flipped learning or demo recordings.
- **[micro:bit USB Grapher](https://github.com/bsiever/microbit-usb-grapher)** - Graph, manipulate, and save sensor data via WebUSB. Great for data-handling cross-curricular work.
- **[HOVER:BIT Bluetooth Controller](https://github.com/JakobST1n/microbit-gamepad)** - Web app for sending D-pad events over Bluetooth.

---

## 📱 Mobile Apps

- **[Official Android App](https://play.google.com/store/apps/details?id=com.samsung.microbit)** - Pair, program and flash via Bluetooth.
- **[Official iOS App](https://apps.apple.com/gb/app/micro-bit/id1092687276)** - Same, for iPad/iPhone.
- **[Official Swift Playgrounds](https://microbit.org/get-started/user-guide/mobile/)** - iPad app teaching Swift via interactive books with micro:bit.

---

## 🅰️ Accessibility

Useful for SEND-focused clubs and adaptations.

- **[microbit.org Accessibility](https://microbit.org/accessibility/)** - Micro:bit Educational Foundation guides for supporting learners with different needs.
- **[micro:bit Switch Access](https://weareprintlab.com/courses/at-dual-switch/)** - Instructions to design and 3D print a micro:bit Bluetooth switch accessibility device.
- **[HandShake](https://github.com/mattoppenheim/microbit_hand_shake)** - Gesture recognition project for people with limited motion control.

---

## 🖨️ 3D Printing

Great DT/computing crossover projects. Selected for primary feasibility (skipped the more advanced robots).

- **[Microbot Case](https://www.thingiverse.com/thing:1434797)** - Robot-shaped case for the micro:bit.
- **[micro:bit Stand](https://www.thingiverse.com/thing:2144500)** - Simple stand.
- **[Battery pack holder](https://www.thingiverse.com/thing:2666671)** - Simple battery clip.
- **[micro:bit holder (class set)](https://www.thingiverse.com/thing:2750805)** - Holds 20 micro:bits vertically. Useful for classroom organisation.
- **[micro:bit class rack](https://www.thingiverse.com/thing:3631044)** - Holds 14 micro:bits and battery packs.
- **[Laser Cut micro:bit Box](https://www.thingiverse.com/thing:3433129)** - Storage for 10 or 20 micro:bits.
- **[Binary Watch](https://www.myminifactory.com/object/3d-print-binary-watch-15257)** - Wearable project. Teaches binary.
- **[A4 folder holder](https://www.myminifactory.com/object/3d-print-micro-bit-a4-folder-holder-22039)** - Store micro:bit inside a school folder.
- **[Gamer Case](https://www.printables.com/model/20112-gamer-case-for-bbc-microbit)** - Handheld game case.
- **[3D Printed micro:bit Holders for the Classroom](https://forwardedu.com/blogs/blog/3d-printed-micro-bit-holders-for-the-classroom)** - Comparison review of 7 classroom holder designs.

---

## 🎨 2D Design

Useful for worksheets, display, and creative outputs.

- **[micro:bit-o-matic](https://pycomic.github.io/microbit.html)** - Easily create micro:bit illustrations with custom LED matrix messages.
- **[micro:bit artwork tool](https://microbit.org/design-your-microbit/v2/)** - Official online tool to create a bitmap or vector image of a micro:bit with a custom LED display.
- **[MakeCode blocks cut-out cards](https://microbit.org/teach/classroom-resources/microbit-makecode-blocks-cutout-cards/)** - Printable MakeCode blocks for unplugged activities. **Very useful for CPD and lessons.**
- **[micro:bit SVG](https://github.com/microbit-foundation/microbit-svg)** - Detailed SVG drawing of the board for worksheets.

---

## 🏗️ Project Ideas

Filtered for primary feasibility. Omitted: security/hacking, advanced robotics, drone work, soldering-heavy builds.

- **[Connected Flowerpot](https://www.instructables.com/Connected-Flowerpot-by-Microbit/)** - Soil moisture sensing with RGB status display. Strong science link.
- **[Automatic Plant Watering System](https://www.instructables.com/Automatic-Plant-Watering-System-Using-a-Microbit/)** - Slightly more advanced version - uses a moisture sensor and pump.
- **[micro:bit Quiz System](http://weddell.co.uk/computing/microbit-quiz-system/)** - Wireless LED quiz buttons. Class-wide game potential.
- **[Racing Car Timing Gate](https://github.com/astrotutor9/Microbit-Racing-Car-Timing-Gate)** - Speed trap for toy cars using three micro:bits and radio. Maths + science crossover.
- **[Tilting LEGO Maze](https://www.instructables.com/Tilting-LEGO-Maze-With-Microbit/)** - LEGO maze with tilt control for a ball.
- **[Robot Unicorn](https://github.com/helenleigh/robot-unicorn)** - Gesture-controlled robot unicorn with cardboard, glitter, 3D-printed horn. **Helen Leigh's work - brilliant primary aesthetic.**
- **[Magic Wand](https://www.instructables.com/Microbit-Magic-Wand-Beginner/)** - Two micro:bits, few electronic parts, everyday household objects. Beginner-friendly.
- **["High-Fivey" the Cardboard Robot](https://www.instructables.com/High-Fivey-the-Cardboard-Microbit-Robot/)** - Cardboard robot that high-fives.
- **[Lip Syncing Characters](https://www.instructables.com/Lip-Syncing-Characters-With-Microbit/)** - Characters that lip-sync to your voice. Lovely creative project.
- **[Spy Tech: Intruder Detection](https://www.instructables.com/Spy-tech-Intruder-Detection-Logging-System/)** - Magnet-based intruder alarm.
- **[PIR Movement Alarm](https://www.instructables.com/PIR-Movement-Alarm-With-BBC-Microbit-and-External-/)** - MicroPython passive-infrared alarm.
- **[Obstacle Detecting White Cane](https://www.instructables.com/Obstacle-Detecting-White-Cane/)** - Accessibility project for the visually impaired. Excellent PSHE tie-in.
- **[Water Rocket](https://wikifactory.com/+fablabbratislava/a-microbit-water-rocket/)** - Water rocket with a micro:bit to measure flight data. Science crossover.
- **[Hagrid's Lantern and Magic Wand](https://www.instructables.com/Hagrids-Interactive-Lantern-and-Magic-Wand-With-Ti/)** - Harry Potter-themed 3D printed project.
- **[Programmable Rainbow Light Up Sign](https://www.thingiverse.com/thing:3111622)** - Laser-cut, 3D printed programmable sign.
- **[Bike Light](https://kitronik.co.uk/blogs/resources/zip-tile-microbit-bike-light-isaac-gorsani)** - Rear bike light with Kitronik Zip Tile.

### Project Collections

- **[MakeCode Projects](https://makecode.microbit.org/projects/)** - Official project list, filtered by difficulty.
- **[Raspberry Pi micro:bit Projects](https://projects.raspberrypi.org/en/projects?hardware%5B%5D=microbit)** - Excellent primary-pitched projects from the Raspberry Pi Foundation.
- **[Tinkercademy Projects](https://tinkercademy.com/microbit)** - Tinker Kit-based projects.
- **[Saturday Science & BBC micro:bits](https://saturdayscience.org/bbc-microbit/)** - Practical science/engineering projects.

---

## 🗞️ Articles

- **[Using the Built-in Sensors](https://learn.adafruit.com/micro-bit-lesson-1-using-the-built-in-sensors)** - How to use the accelerometer and magnetometer.
- **[Build a snake game](https://www.cameronmacleod.com/blog/microbit-snake)** - Walkthrough for making a MicroPython snake game. Classic extension project.
- **[Embedded Python: Build a Game on the micro:bit](https://realpython.com/embedded-python/)** - A detailed tutorial on MicroPython game building.
- **[Character Design with micro:bit](https://scientiffic.medium.com/character-design-with-microbit-51c42586caa1)** - Designing emotion on a 5x5 LED matrix.
- **[Synchronized Music on micro:bits](http://blog.flowblok.id.au/2018-02/synchronized-music-on-microbits.html)** - Mesh network for synchronised music across a large area.

### Article Collections

- **[MultiWingSpan](http://www.multiwingspan.co.uk/micro.php)** - Large collection of primary-friendly examples.
- **[SparkFun micro:bit tutorials](https://learn.sparkfun.com/tutorials/tags/microbit)** - Includes kit experiment guides.
- **[Adafruit Learn: micro:bit](https://learn.adafruit.com/category/micro-bit)** - Adafruit's learning section.
- **[Kitronik University](https://kitronik.co.uk/blogs/resources/bbc-microbit-kitronik-university)** - Varied resources from Kitronik.
- **[ElecFreaks Learn](https://www.elecfreaks.com/learn-en/)** - Experiments, tutorials and material.
- **[Little Bird Guides](https://learn.littlebirdelectronics.com.au/categories/microbit)** - Detailed sensor tutorials.

---

## 🎥 Videos

- **[Video Series from The Maker Movies](https://www.youtube.com/playlist?list=PLD0HD_3AJljXDWoasq2x5gHmkKeV7cc-P)** - Short introductory videos for getting started.
- **[SparkFun video resources](https://sparkfuneducation.com/video-resources/microbit.html)** - Growing list of video resources.
- **[SamCodes YouTube Playlist](https://www.youtube.com/playlist?list=PLumNlyd5JxxegaAVScP7Qm1AXPtJdGBCq)** - Component/feature tutorials.
- **[Behind the MakeCode Hardware](https://www.youtube.com/playlist?list=PLMMBk9hE-SeqDYtw9pGNPsQ10V_EGMyGe)** - How different hardware components work.
- **[MicroPython for micro:bit Workshop](https://www.youtube.com/playlist?list=PLPK2l9Knytg6SygFSODc3H1JL4KEm-Ruv)** - MicroPython feature walkthroughs.

---

## 🧑‍🏫 Teaching Resources

Worth checking the full list on the original repo - much of the "Teaching Resources" section continues beyond the content fetched. Always verify age-appropriateness against your own scheme.

- **[Mr Morrison's micro:bit Lessons](https://mrmorrison.co.uk/microbit/)** - Starter lessons, beyond the basics, and data & sustainability, with lesson plans, worksheets, and videos.
- **[microbit.org Lessons](https://microbit.org/teach/lessons/)** - Curriculum-linked units of work and design challenges for planning and teaching computing in primary and secondary schools.
- **[Microsoft 14 Week Curriculum](https://makecode.microbit.org/courses/csintro)** - Targeted to middle school grades 6-8 (ages 11-14). It is also written for teachers who may not have a Computer Science background, or may be teaching an "Intro to CS" for the 1st time.
- **[Code Club micro:bit projects](https://projects.raspberrypi.org/en/codeclub/microbit)**
- **[Raspberry Pi Foundation micro:bit Project Path](https://rpf.io/microbit-intro)** - BBC micro:bit Projects that focus on wellbeing, including topics like mental health, relaxation, and exercise.
-  **[Science Experiment Lessons](https://makecode.microbit.org/courses/ucp-science)** - Geared for students in middle and early high school, these Science Experiment lessons are designed help gain a greater understanding of the forces and behaviour of the physical world.
- **[Arm School Program Resources for Schools](https://www.arm.com/resources/education/schools)** - A suite of teaching and learning resources to help teachers deliver engaging and inspirational lessons in Computing (K-12).

---

_Filtered from [carlosperate/awesome-microbit](https://github.com/carlosperate/awesome-microbit) - CC0 licensed. Curated for UK KS2 primary computing use._
