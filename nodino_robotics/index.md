---
title: Nodino Robotics
layout: default
---

<div class="row-fluid">
	<div class="span12">

		<h2 style="text-align: center;"><span class="notranslate">Nodino Robotics<span>&trade; - Open Source Hardware</span></h2>

		<p class="lead" style="text-align: center;">Robotics platform development status: Alpha<br />
		FR-4 made legs, servo firmware done, working serial console<br />
		wireless communication is up and running!</p>

		<p style="text-align: center;"><img alt="" src="/img/nodino-rc7.jpg" style="width: 614px; height: 461px;" /></p>

		<p>&nbsp;</p>

		<p><span class="notranslate">Nodino Robotics&trade;</span> open source hardware is an idea to provide robotic enthusiasts with open hardware and software design to build simple robots at home, in school and research centre. We started the hardware design to be as simple as possible, so that anyone can download the blue print, duplicate and build one. For our first platform, we chose to integrate an STM32F407VGT6 microcontroller for some reason:</p>

		<ol>
			<li>It is an ARM Cortex&trade;-M4F with 168MHz of clock speed.</li>
			<li>We can program it using the free and open source GCC for ARM Embedded.</li>
			<li>Many software applications developed over ARM Cortex&trade;-M family.</li>
			<li>Easy to migrate among ARM chip vendors.</li>
			<li>Affordable price.</li>
		</ol>

		<p>We expect to see some RTOSes ported to this platform and see how the robot performs. At the moment we have a working bare-metal system using newlib-nano library, with working support for multiple R/C servo control, serial port, accelerometer reading, elmchan-FatFs, 2.4GHz wireless transmission, GPIOs, LEDs, buttons and analog data acquisition.</p>

		<p>Some of on going software projects are:</p>

		<ol>
			<li>RT-Thread: working port with newlib-nano, still trying to figure out how to hook multiple R/C servo controller.</li>
			<li>PicoC: a small C language interpreter with the need to re-flash the microcontroller. The program can be saved and loaded from microSD card.</li>
		</ol>

		<p>Project blue print, software and instruction is available on GitHub. We would like to remind you that this project is still at Alpha stage and will go through a lot of changes, but hackers are welcomed to join the development. On the robot, we added two rows 2x15 headers (male/female) solderable. We plan to permanently soldered a female headers instead of male ones for our final version. But, we leave it unsoldered for the moment, giving the community a chance to decide which one is better over the other.</p>

		<p>Happy hacking! We will often update this page for changes, please refer to our <a href="/Blog">blog</a> for chronological changes we made to the robotics platform.</p>

	</div>
</div>