Lab Report 3
Part 1 
A failure-inducing input

@Test 
public void testReverseinPlace(){
  int[] input 2 = {2, 4, 1};
  ArrayExamples.reverseInplace(input2);
  assertArrayEquals(new int[]{1, 4, 2}, input2);

  }

An input that doesn't induce a failure

@Test
public void testReverseInPlace(){
int[] input1 = {3};
ArrayExamples.reverseInPlace(input1);
assertArrayEquals(new int[]{3}, input 1};


Symptom

![image](screen1.png) 
