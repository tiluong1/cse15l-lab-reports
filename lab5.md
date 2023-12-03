Lab Report 5
 ![image](ss21.png)
  
  1) Hello, I was wondering why am I getting this error. I assume that the bug was coming from testMerge2 which indicates that the merge function did not work for a specific test case. The error states that it timed out at line 44 which indicates that the error might be at that line. Am I on the right track?

2) Hello fellow student, you are on the right track and correct in thinking that the error is coming from testmerge2. The test that is not producing the exepcted output is from line 19 in ListExamples.java according to your symptom. You were also correct on stating that the error is coming from line 44. I suggest running the following code to debug the code : ```<javac -g ListExamples.java>``` to compile the java file, ```<jdb -classpath .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests>``` to run jdb on your test file, ```stop at ListExamplesTests:19```, to create a break point at line 19 in which we find the symtom, finally ```run``` jdb.Good job and let me know if you have any more questions.

3) 
4)
5)



REFLECTION

Part 2
After a full quarter of Cse 15L, I learned a lot of things from the labs that we have done in class. One that really stood out to me was using the vim command to edit files. I realy enjoyed using vim to enable more efficient text editing and thought that it was fascinating. The skill demos were extremely useful when learning how to understand linux and code in general better.I really enjoyed the labs that we do in class and with our classmates and I definetly reccommend it to future students. 
