Download Link: https://assignmentchef.com/product/solved-ece8930-program-1
<br>
<ol>

 <li><strong>Assignment</strong></li>

</ol>

Implement Bitcoin blockchain data structure. This will be done in the following steps:

<ul>

 <li>Define 6 users – requires creating elliptic curve (EC) public key pairs for six different users. Can be done either in a program using OpenSSL or in a program using OpenSSL libraries. <em>Requires: </em>understanding EC key generation and storage.</li>

 <li>Create transactions for the 6 users. Since different types of transactions have different formats. You can use the general format given in [2]. Start initially with one user having all the coins, which are then transferred to other users and then traded between users. <em>Requires: </em>Understanding BTC transaction data structures, EC encryption, decryption and EC signatures.</li>

 <li>Create a Merkle tree for the transactions. What a Merkle tree is and how to create one is covered in class. <em>Requires: </em>Hashing and DSA signatures.</li>

 <li>Create genesis block.</li>

 <li>Add set of five blocks to the genesis block</li>

 <li>Provide within the program verification that each cryptographic primitive is being done correctly</li>

</ul>




<ol>

 <li><strong>Expected Environment</strong></li>

</ol>

The preferred programming environment for this assignment is C. It may be possible to do the entire assignment in Python or another language, but that is not supported by the instructor. If you decide to use another language, then questions regarding calling of ssl primitives and programming will not be supported by the instructor. To do this assignment you will need:

<ul>

 <li>a C compiler (preferably GNU C in a Linux environment. Other programming languages are allowed, but you may have to tutor the instructor.)</li>

 <li>Debugger, like GDB, suggested,</li>

 <li>Open SSL (Used for calling cryptography primitives)</li>

</ul>




<ol>

 <li><strong>To compile with gcc</strong></li>

</ol>

<ul>

 <li>gcc –g –o block block.c –lssl -lcrypto</li>

</ul>

<ol>

 <li><strong>To run either:</strong></li>

</ol>

<ul>

 <li><strong>./block</strong></li>

 <li><strong>gdb ./block</strong></li>

 <li><strong>Emacs block.c</strong>

  <ul>

   <li><strong>$x gdb-many-windows</strong></li>

   <li><strong>$x gdb</strong></li>

   <li><strong>$x gdb-display-memory-buffer</strong></li>

   <li><strong>break main</strong></li>

   <li><strong>r</strong></li>

  </ul></li>

</ul>

<strong> </strong>

<ol>

 <li><strong>Reference</strong></li>

</ol>

[1] Bitcoin Block. <a href="https://en.bitcoin.it/wiki/Block">https://en.bitcoin.it/wiki/Block</a>

[2] Bitcoin Transaction. <a href="https://en.bitcoin.it/wiki/Transaction">https://en.bitcoin.it/wiki/Transaction</a>




<strong> </strong>

<strong> </strong>

<ul>

 <li><strong>s</strong></li>

</ul>