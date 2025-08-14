<h1>BOOKMARK (PG) [100]</h1>

<h3>Integrated Memory Controller</h3>

<p>All current microprocessors have an <em>integrated memory controller</em> (IMC).</p>

<p>It has moved from the motherboard chip into the CPU to optimize the flow of information into and out of the CPU, and the <em>IMC</em> enables faster control</p>

<p>over things like the large <em>L3 cache</em> shared among multiple cores.</p>

<p>Just like in so many other areas of computing, manufacturers implement a variety of IMCs in their CPUs. In practice, this means that different CPUs handle different types and capacities of RAM. I'll save the details on those RAM variations for Chapter 4. For now, add "different RAM support" to your list of things to look at when making a CPU recommendation for a client.</p>

<h3>Integrated Graphics Processing Unit</h3>

<p>As you'll read about in much more detail in Chapter 17, the video processing portion of the computer—made up of the parts that put a changing image on the monitor— traditionally has a discrete microprocessor that differs in both function and architecture from CPUs designed for general-purpose computing. The generic term for the video processor is <em>graphics processing unit (GPU).</em> I'll spare you the details until we get to video in Chapter 17, but it turns out that graphics processors can handle certain tasks much </p>

<p>more efficiently than the standard CPU. Integrating a GPU into the CPU enhances the overall performance of the computer while at the same time reducing energy use, size, and cost. With the proliferation of mobile devices and portable computers today, all these benefits have obvious merit.</p>
<h3>Security</h3> 

<p>All modern processors employ <em>NX bit technology</em>, which enables the CPU to protect certain sections of memory. This feature, coupled with implementation by the operating system, stops malicious attacks from getting to essential operating system files. Microsoft calls the feature <em>Data Execution Prevention (DEP)</em>, and it's turned on by default in every OS. Everybody calls the NX bit technology something different (but you don’t need to memorize any of this for the exams).</p>

<ul> 
  <li>Intel: XD bit (eXecute Disable)
  </li> <li>AMD: Enhanced Virus Protection</li> 
  <li>ARM: XN (Execute Never)</li> </ul>
  
<h3>Selecting and Installing CPUs</h3>

<p>Now that you know how CPUs work, it's time to get practical. This last section discusses selecting the proper CPU, installing several types of processors, and troubleshooting the few problems techs face with CPUs.</p>

<h3>Selecting CPU</h3>

<p>When selecting a CPU, you need to make certain you get one that the motherboard can accommodate Or. if you're buying a motherboard along with the CPU, then get the right CPU
for the intended purpose Chapter 11 discuses computer roles and helps select the proper peices around the CPU to get the full picture, so we'll wait until then to discuss the "why" of specific processors. instead this section assumes you're placing a new CPU in an already-aquired motherboard. You need to address two key points in selecting a CPU
that will work. First does the motherboard support intel CPU's or AMD CPU's second, what CPU socket does the motherboard here</p>

> Note

> AS mentioned previously, ARM processors come in a complete package with the motherboard and other components. you'll never "install" an ARM processor

<p>to find answers to both those questions, you have two sources: the motherboard book or manual and find the manufacturer's Web site. </p>

<p>Just as intel and AMD make many types of CPU's motherboards are manufactured with various diffrrent types of sockets. there have been hundreds of sockets devolped over the years Table shows a few more popular ones in production today</p>

| Socket   | Platform | CPU                                                                 |
|----------|----------|----------------------------------------------------------------------|
| LGA 2066 | Intel    | Core i3/i5/i7, Xeon (Skylake, Kaby Lake, Cascade Lake)               |
| LGA 1200 | Intel    | Core i5/i7/i9, Xeon (Comet Lake, Rocket Lake)                        |
| LGA 1700 | Intel    | Core i5/i7/i9, Xeon (Alder Lake)                                     |
| AM4      | AMD      | Ryzen                                                                |
| TR4      | AMD      | Ryzen Threadripper                                                   |
| AM5      | AMD      | Ryzen (Zen 4)                                                        |

<h5>Common Sockets</h5>

> Exam Tip

> The COMPTIA A+ 1101 exam objectives do not list any specific CPU sockets, but previous versions frequently included questions about them. Hopefully you wont run into one of these questions, but its not a bad idea to know the sockets just in case. Beyond the exam, just make sure that you understand taht every CPU has a specific socket into which it fits and make a sure client's motherboard has the socket that works with a suggested CPU
