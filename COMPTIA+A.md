<h1>BOOOMARK(PG)[100]</h1>

<h3>Integrated Memory Controller</h3>

<p>All current microprocessors have <em>intergrated memory controller</em> (IMC)</p>

<p>moved from the moterhboard chip intO teh CPU To optimize the flow of information into and out from the CPU, and <em>(IMC)</em> enables faster control</p>
<p>over the things like the large <em>L3 cache</em> shared among multiple cores.</p>

<p>Just like in so many other areas of computing manufactureres implement a variety of IMC's in their CPU's in practice this means that diffrent CPU's handle diffrent types and capacities of RAM I'll save the details on those RAM veriations for chapter 4 for now add "diffrent RAM support" to your list of things to look at when making a cpu reccomendation for a client.</p>

<h3>Intergrated Graphics Procssing Unit</h3>
<p>As you'll read about in much more detail in chapter 17, the video processing portion
of the computer---made up of the parts that put a changing image on the monitior---
Tradtionally has a discrete microprocessor that differs in both fucntion and architecture
from the CPU's designed for gneral-purpose computing. The generic term for the video processor is 
<em>graphics processing unit (GPU) I'll spare you the details until we get to video in chapter 17, but it turns out that graphics prcessors can handle certain task much </em>
more efficiently than the standard CPU. Intergrating a GPU into the CPU enhacnes the overall
performance of the computer while at the same time reducing energy use, size, and cost. With the proliferation of mobile devices and protable computers today all these benifits have obvious merit.</p>

<h3>Security</h3>
<p>All modern processors employ the <em>NX bit technology</em> that enables the CPU to protect certain section of memory this feature, couples with implementation by the operating system, stops malicious attacks from getting to essential op[erating system files. Microsoft calls the feature <em>Data Execution Prevention (DEP),</em> turned on by default in every OS Everybody calls the NX bit technology something diffrent (buy you dont have need to memorize any of this for the exams)</p>

<ul>
  <li>Intel  XD bit (eXecute Disable</li>
  <li>AMD  Enhanced Virus Protection</li>
  <li>ARM  XN(Execute Never</li>
</ul>

