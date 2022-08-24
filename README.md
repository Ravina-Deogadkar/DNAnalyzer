<p>
  <img src="https://user-images.githubusercontent.com/96280466/186224441-46dd2029-b9dc-4b3d-aad8-bfd1e1e62f2e.png" width="300" align="right"/>
</p>
<h1 id="dnanalyzer">DNAnalyzer
</h1>
<blockquote>
  <p>A highly efficient, powerful, and feature-rich algorithm for analyzing genomic sequences
  </p>
</blockquote>
<p>This software uses a modified version of the Boyer-Moore algorithm to analyze genomic sequences for the genes of amino acids, start and stop codons, regions with high GC-content, transcription factors, and regulatory elements. In the near future, machine learning models and artificial intelligence will be added to enhance the algorithm.
</p>
<h2 id="background">Background
</h2>
<p>The human genome is comprised of over 3 billion base pairs, making manual analysis nearly impossible. Consequently, using powerful computational and statistical methods to decode the functional information hidden in DNA sequences are necessary. The genome is also extremely intricate and contains a plethora of structured data types, which need to be organized and converted into analyzable data appropriately.
  <code>[1]
  </code>
</p>
<h2 id="features">Features
</h2>
<ul>
  <li>Start and stop codons
    <ul>
      <li>Indicate the start and stop of an amino acid. There are 20 different amino acids. A protein consists of one or more chains of amino acids (called polypeptides) whose sequence is encoded in a gene.
        <code>[2]
        </code>
      </li>
    </ul>
  </li>
  <li>High coverage regions
    <ul>
      <li>Regions of a DNA genome that code for a protein and have a relatively high proportion (45-60% GC-content) of cytosine and guanine nucleotides to the 4 nucleotide bases.
        <code>[3]
        </code>
      </li>
    </ul>
  </li>
  <li>Longest genes
    <ul>
      <li>Most susceptible to disease implications and are especially linked to neurodevelopmental disorders (e.g., autism).
        <code>[4]
        </code>
      </li>
    </ul>
  </li>
  <li>Transcription factors
    <ul>
      <li>Proteins that help turn specific genes &quot;on&quot; or &quot;off&quot; by binding to nearby DNA.
        <code>[5]
        </code>
      </li>
    </ul>
  </li>
  <li>Regulatory elements
    <ul>
      <li>Binding sites for transcription factors, which are involved in gene regulation.
        <code>[6]
        </code>
      </li>
    </ul>
  </li>
  <li>FASTA files (.fa)
    <ul>
      <li>Supports multi-line and single-line FASTA database files.
        <code>[7]
        </code>
      </li>
    </ul>
  </li>
</ul>
<h2 id="impact">Impact
</h2>
<p>Researchers are working to extract valuable information from software such as this in order to better understand human health and disease.
</p>
<h2 id="future-support-and-improvements">Future Support and Improvements
</h2>
<h3 id="gui">GUI
</h3>
<p>  A GUI-based application that will run natively on Windows/macOS/Linux to perform the algorithms implemented in the software.
</p>
<h3 id="needleman-wunsch-algorithm">Needleman-Wunsch Algorithm
</h3>
<p>  This algorithm is used primarily for gene sequencing looking for the optimal match between multiple gene sequences.
  <code>[8]
  </code>
</p>
<h3 id="cytogenic-location">Cytogenic Location
</h3>
<p>  This program will implement the Cytogenic Location organization technique which is a technique for finding where specific genes will be located by giving the chromosome, arm, region and band. 7q31.2, for example, would be the CFTR gene located on the 7th chromosome&#39;s long arm, in the 3rd region on the 1st band, and the 2nd sub-band.
  <code>[9]
  </code>
</p>
<h3 id="data-sources-">Data sources:
</h3>
<ul>
  <li>
    <a href="https://en.wikipedia.org/wiki/DNA_and_RNA_codon_tables">https://en.wikipedia.org/wiki/DNA_and_RNA_codon_tables
    </a>
  </li>
  <li>
    <a href="http://algoart.com/aatable.htm">http://algoart.com/aatable.htm
    </a>
  </li>
  <li>
    <a href="https://www.bioinformatics.org/sms2/shuffle_dna.html">https://www.bioinformatics.org/sms2/shuffle_dna.html
    </a>
  </li>
</ul>
<h2 id="citations">Citations
</h2>
<ol>
  <li>Genomic Data Science Fact Sheet. (n.d.). Genome.gov. 
  </li>
  <li>DNA and RNA codon tables. (2020, December 13). Wikipedia. 
  </li>
  <li>GC-content - an overview | ScienceDirect Topics. (n.d.). Www.sciencedirect.com. 
  </li>
  <li>Length matters: Disease implications for long genes. (2013, October 22). Spectrum | Autism Research News. 
  </li>
  <li>Suter, D. M. (2020). Transcription Factors and DNA Play Hide and Seek. Trends in Cell Biology. 
  </li>
  <li>What is noncoding DNA?: MedlinePlus Genetics. (n.d.). Medlineplus.gov. 
  </li>
  <li>BLAST TOPICS. (2019). Nih.gov. 
  </li>
  <li>Wikipedia Contributors. (2021, March 24). Needleman–Wunsch algorithm. Wikipedia; Wikimedia Foundation. 
  </li>
  <li>Cytogenic Location. (2020, December 13). Wikipedia. 
  </li>
</ol>
<p><b>Copyright (c) 2022, DNAnalyzer. All rights reserved.</b>
</p>
