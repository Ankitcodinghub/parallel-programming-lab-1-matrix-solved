# parallel-programming-lab-1-matrix-solved
**TO GET THIS SOLUTION VISIT:** [parallel_programming Lab 1-Matrix Solved](https://www.ankitcodinghub.com/product/parallel_programming-lab-1-matrix-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92752&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;parallel_programming Lab 1-Matrix  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Part I : Matrix

<ol>
<li>Write a class Column_Major_Matrix that has a member all_column which is
of type vector&lt;vector&lt;T&gt;&gt;
</li>
<li>Write a class Row_Major_Matrix that has a member all_row which is of type
vector&lt;vector&lt;T&gt;&gt;
</li>
<li>Provide a constructor for each class that takes arguments to specify the
dimensions (e.g., Column_Major_Matrix&lt;int&gt; cc1 (1000, 1000); ), and fills up all

elements by randomly generated values of type T.
</li>
<li>Provide getter/setter function to access each column and row by an index.</li>
<li>Overload copy/assignment and move copy/assignment operator to allow the
following in the main function:

Column_Major_Matrix&lt;int&gt; cc1 (1000, 1000); Row_Major_Matrix&lt;int&gt; rr1( 1000, 1000); Column_Major_Matrix&lt;int&gt; cc2 (cc1); Row_Major_Matrix&lt;int&gt; rr2 = (rr1); Column_Major_Matrix&lt;int&gt; cc3 = std::move( cc2 ); Row_Major_Matrix&lt;int&gt; rr3 = std::move( rr2 );
</li>
<li>Overload operator* in Row_Major_Matrix to allow calculation of the product of a Row_Major_Matrix instance to a Column_Major_Matrix instance, and return the resultant product as a Row_Major_Matrix.</li>
<li>Overload operator* in Column_Major_Matrix to allow calculation of the product of a Column_Major_Matrix instance to a Row_Major_Matrix instance, and return the resultant product as a Column_Major_Matrix.</li>
<li>Write type conversion operators (i.e., operator Row_Major_Matrix() and operator Column_Major_Matrix() ) to allow implicit type conversion between Row_Major_Matrix and Column_Major_Matrix. Show it works by:
Column_Major_Matrix&lt;int&gt; cc (55, 1000); Row_Major_Matrix&lt;int&gt; rr (1000, 66); Row_Major_Matrix&lt;int&gt; rr = cc*rr;
</li>
<li>Overload operator% to use exactly 10 threads to multiplex the multiplication, and use std::chrono to show the speedup w/ and w/o multithreading.</li>
</ol>
</div>
</div>
</div>
