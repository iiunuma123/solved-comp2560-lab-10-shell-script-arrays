Download Link: https://assignmentchef.com/product/solved-comp2560-lab-10-shell-script-arrays
<br>
Use <em>array</em> to write a shell script to print out the information about the files and directories in the current directory according to the following sample run.

&gt;&gt;&gt;&gt;&gt; ls

compute     print repeat

&gt;&gt;&gt;&gt;&gt; compute

practice: shell command and array

list all directories and files in current directory: compute print repeat

total number of files and directories: 3                                    the first element in this list: compute                                      all elements in this list:

compute                                   print                             repeat                            &gt;&gt;&gt;&gt;&gt;




Part II (choice A)

Two files <em>courses</em> and <em>emails</em> are given where columns are separated by tabs.




courses:

<table width="0">

 <tbody>

  <tr>

   <td width="43">101</td>

   <td width="81">60212 90</td>

  </tr>

  <tr>

   <td width="43">101</td>

   <td width="81">60256 81</td>

  </tr>

  <tr>

   <td width="43">102</td>

   <td width="81">60231 70</td>

  </tr>

  <tr>

   <td width="43">102</td>

   <td width="81">60212 85</td>

  </tr>

  <tr>

   <td width="43">103</td>

   <td width="81">60256 n/a</td>

  </tr>

 </tbody>

</table>




emails:

<ul>

 <li><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="dcedeced9ca9abb5b2b8afb3aef2bfbd">[email protected]</a></li>

 <li><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="350405077540425c5b51465a471b5654">[email protected]</a></li>

 <li><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="bc8d8c8ffcc9cbd5d2d8cfd3ce92dfdd">[email protected]</a></li>

</ul>

Write a bash script to find the emails of all students taking a specific course, which is given as a command line argument.

Hints: use <em>grep</em> command for the search, and use <em>array</em> to store intermediate data.

Sample output:




&gt;&gt;&gt;&gt;&gt; mysolution

usage: mysolution course-number &gt;&gt;&gt;&gt;&gt; mysolution 60200 course number 60200 not found

&gt;&gt;&gt;&gt;&gt; mysolution 60256

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="3a0b0a0b7a4f4d53545e49554814595b">[email protected]</a>

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="a1909192e1d4d6c8cfc5d2ced38fc2c0">[email protected]</a>







Part II (choice B)




Two files 60-256 and 60-212 are given. Each contains two columns for student ids and the marks. Columns are separated by tabs. Write a bash script to print out all the ids of the students who passed both 60-256 and 60-212.













Part III (optional)




In the current directory, there are several files starting with 60-. The total number of such files could be changed, and the names of these files are not known. Each file contains two columns: student ids and the marks. Columns are separated by tabs. Write a bash script to print out all the ids of the students who passed all the courses.







2