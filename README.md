Download Link: https://assignmentchef.com/product/solved-cs112-programming-assignment-4-little-search-engine-test-cases
<br>
<h1>getKeyword (pts: 3,3,3,2,2)</h1>

<ol>

 <li>sWord</li>

</ol>

Ans: sword

<ol start="2">

 <li>paraphrase; Ans: paraphrase</li>

 <li>really?!?!</li>

</ol>

Ans: really

<ol start="4">

 <li>Between, Ans: null</li>

 <li>either:or Ans: null</li>

</ol>

<h1>loadKeywordsFromDocument (pts: 6,7,7)</h1>

<ol>

 <li>Lots of noise – <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/pohlx.txt">txt</a></li>

 <li>Lots of keywords – <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/Tyger.txt">Ty</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/Tyger.txt">g</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/Tyger.txt">txt</a></li>

</ol>

<h1>3.      Repetition of keywords – <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/jude.txt">j</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/jude.txt">ude.txt </a>insertLastOccurrence (pts: 2,3,2,3,2)</h1>

<ol>

 <li>Extreme left insertion</li>

</ol>

Frequencies: [82,76,71,71,70,65,61,56,54,51,48,45,41,36,34,30,25,20,20,18,17,17,14,12,85] Ans: [11,5,2,0]

<ol start="2">

 <li>Extreme right insertion</li>

</ol>

Frequencies: [82,76,71,71,70,65,61,56,54,51,48,45,41,36,34,30,25,20,20,18,17,17,14,12,4] Ans: [11,17,20,22,23]

<ol start="3">

 <li>In between test 1</li>

</ol>

Frequencies: [82,76,71,71,70,65,61,56,54,51,48,45,41,36,34,30,25,20,20,18,17,17,14,12,50] Ans: [11,5,8,9,10]

<ol start="4">

 <li>In between test 2</li>

</ol>

Frequencies: [82,76,71,71,70,65,61,56,54,51,48,45,41,36,34,30,25,20,20,18,17,17,14,12,26] Ans: [11,17,14,15,16]

<ol start="5">

 <li>Insertion with a frequency match</li>

</ol>

Frequencies: [82,76,71,71,70,65,61,56,54,51,48,45,41,36,34,30,25,20,20,18,17,17,14,12,17] Ans: [11,17,20]

<h1>mergeKeywords (pts: 7,9,9)</h1>

<ol>

 <li>Single document – <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/metamorphosis.txt">txt</a></li>

 <li>2 documents with no intersection – <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/Tyger.txt">Ty</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/Tyger.txt">g</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/Tyger.txt">txt</a> and <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/metamorphosis.txt">metamorphosis.txt </a>3. 2 documents with a few intersections – <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/pohlx.txt">pohlx.txt</a> and <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/pohly.txt">pohl</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/pohly.txt">y</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/pohly.txt">.txt </a><strong>top5Search (pts: 3,4,7,8,8)</strong></li>

</ol>

docs to use: <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc1.txt">doc1.txt</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc1.txt">,</a> <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc2.txt">doc2.txt</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc2.txt">,</a> <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc3.txt">doc3.txt</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc3.txt">,</a> <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc4.txt">doc4.txt</a>, <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc5.txt">doc5.txt</a>, <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc6.txt">doc6.txt</a>, <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc7.txt">doc7.txt</a> and <a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc8.txt">doc8.txt</a><a href="https://www.cs.rutgers.edu/courses/112/classes/spring_2020_venugopal/progs/prog4/testcases/doc8.txt">.</a>

<ol>

 <li>No matches for either</li>

</ol>

Keywords: strange (no match), case (no match) Ans: no list

<ol start="2">

 <li>No match for 1 keyword, but more than 5 total matches</li>

</ol>

Keywords: color (doc5,3,7,2,4,1), strange (No match)

Ans: doc5,3,7,2,4 (1 pt penalty if &gt; 5 results)

<ol start="3">

 <li>Matches on both keywords, no common docs, more than 5 total matches</li>

</ol>

Keywords: orange (doc5,2,7,3,1), weird (doc6,8)

Ans:doc5,6,2,8,7 (1 pt penalty if &gt; 5 results)

<ol start="4">

 <li>4 common docs, no common result frequencies, more than 5 total matches</li>

</ol>

Keywords: red (doc3,2,4,1,7,6), orange (doc5,2,7,3,1)

Ans: doc5,3,2,4,7 (2 pt penalty if &gt; 5 results)

<ol start="5">

 <li>2 docs in different lists with the same frequency, more than 5 results</li>

</ol>

Keywords: red (doc3,2,4,1,7,6), car (doc1,3,7,6,4)

Ans: (doc1,3,2,7,4) (doc4 freq matches doc6) (2 pt penalty if &gt; 5 results)





