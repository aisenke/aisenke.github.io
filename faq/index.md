---
title: FAQ
layout: default
---

<div class="row-fluid">
	<div class="span12">
		<h2>Frequently Asked Question</h2>
	</div>
</div>

<div class="row-fluid">
	<div class="span12">

		<p>Please choose from sections below to resolve some common issues and questions about our products.</p>

		<p>&nbsp;</p>

		<h3>F4-DiscoverFree</h3>

		<h4>Is F4-DiscoverFre pin to pin compatible to STM32F4 Discovery?</h4>

		<p>F4-DiscoverFree is not pin to pin compatible replacement, but the core microcontroller can use the same library provided by ST Microelectronics. In fact, we included it in our examples. The core microcontroller has more pinouts so that you can have more connections to your extension board.</p>

		<h4>What makes F4-DiscoverFree different than STM32F4 Discovery?</h4>

		<p>If you read the evaluation license agreement of STM32F4 Discovery on ST Microelectronics website you will see that their evaluation kit may not be included in any commercial product nor you are allowed to sell any extension board you developed with. Well, we are not lawyers, but our interpretation is that you may not commercialize any of your creation with STM32F4 Discovery. This is exactly where we come in. We do not limit our user to use our board for evaluation purpose only. We encourage our users to sell. You are free to copy and modify the design and even produce the exact same product as ours.</p>

		<h4>Can F4-DiscoverFree be used to develop application under commercial toolchains like Keil or IAR?</h4>

		<p>We are encourage our users to develop application using the free and open source software. However, you may also contact us in case you have a particular requirement with any commercial toolchains. We are here to help at our best we can.</p>

		<h4>What brand of microSD card is compatible to use with F4-DiscoverFree?</h4>

		<p>Any brand of microSD card will do, however we tested only Kingston and SanDisk during development. MicroSD card we used are of SDHC class 4.</p>

		<h4>F4-DiscoverFree keeps rebooting by itself or not working, what should I do?</h4>

		<p>If your board keeps rebooting repeatedly for no reason and you are sure that your program is not buggy, then it is probably the USB cable is bad. Do not use cheap USB cable which mostly cannot deliver enough power to supply F4-DiscoverFree and any extension board connected to it. If the cable is tested to work with an external HDD, then it should work just fine with F4-DiscoverFree. If your cable is in good condition, then probably your extension board withdraws too much current.</p>

		<h4>Will I break my computer or F4-DiscoverFree if I take too much power from the USB port?</h4>

		<p>There are recoverable fuses on-board of both USB interfaces. It should protect you from taking too much power from it. Unfortunately, there is no indicator when this happens. You will notice that the board is not working, but it does not mean it is broken.</p>

		<h4>Demo firmware cannot find songs in the microSD card.</h4>

		<p>Did you insert the microSD card properly? The connector is a push-push type, meaning you push microSD to properly insert it and push it once again to remove it. You should hear a &quot;click&quot; sound when you push it in or out.</p>

	</div>
</div>