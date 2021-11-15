# handwashing-problem
Dr. Semmelweis and the Discovery of Handwashing

Meet Dr. Ignaz Semmelweis


![ignaz_semmelweis_1860](https://user-images.githubusercontent.com/11906325/141856759-2073f06f-5ee8-4d24-877b-8335c9296f63.jpeg)



This is Dr. Ignaz Semmelweis, a Hungarian physician born in 1818 and active at the Vienna General Hospital. If Dr. Semmelweis looks troubled it's probably because he's thinking about childbed fever: A deadly disease affecting women that just have given birth. He is thinking about it because in the early 1840s at the Vienna General Hospital as many as 10% of the women giving birth die from it. He is thinking about it because he knows the cause of childbed fever: It's the contaminated hands of the doctors delivering the babies. And they won't listen to him and wash their hands!

In this notebook, we're going to reanalyze the data that made Semmelweis discover the importance of handwashing. Let's start by looking at the data that made Semmelweis realize that something was wrong with the procedures at Vienna General Hospital.

<h3>Techniques used include:</h3>
<ul>
  <li>Importing Data</li>
  <li>Data Wrangling & Manipulation</li>
  <li> Data Visualization </li>
  <li> Bootstrap Analyis </li>
  <li Statistics </li>
  </ul>
<h3> Pokemon Dataset </h3>

<h3>Data Background</h3>

For the years 1841 to 1846, the number of women giving birth at the two clinics of the Vienna General Hospital is shown in the table below. You'll observe that delivery was extremely risky; an astonishing number of women died as a result of childbirth, the majority of whom died of childbed fever.


<table class="tableizer-table">
<thead><tr class="tableizer-firstrow"><th>year</th><th>births</th><th>deaths</th><th>clinic</th></tr></thead><tbody>
 <tr><td>1841</td><td>3036</td><td>237</td><td>clinic 1</td></tr>
 <tr><td>1842</td><td>3287</td><td>518</td><td>clinic 1</td></tr>
 <tr><td>1843</td><td>3060</td><td>274</td><td>clinic 1</td></tr>
 <tr><td>1844</td><td>3157</td><td>260</td><td>clinic 1</td></tr>
 <tr><td>1845</td><td>3492</td><td>241</td><td>clinic 1</td></tr>
 <tr><td>1846</td><td>4010</td><td>459</td><td>clinic 1</td></tr>
 <tr><td>1841</td><td>2442</td><td>86</td><td>clinic 2</td></tr>
 <tr><td>1842</td><td>2659</td><td>202</td><td>clinic 2</td></tr>
 <tr><td>1843</td><td>2739</td><td>164</td><td>clinic 2</td></tr>
 <tr><td>1844</td><td>2956</td><td>68</td><td>clinic 2</td></tr>
 <tr><td>1845</td><td>3241</td><td>66</td><td>clinic 2</td></tr>
 <tr><td>1846</td><td>3754</td><td>105</td><td>clinic 2</td></tr>
</tbody></table>
