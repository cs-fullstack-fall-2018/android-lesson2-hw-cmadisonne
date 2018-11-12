# android_lesson2_hw

Answer these questions. Edit this README to enter your answer.


### Question 1

Which two layout constraint attributes on the Zero Button position it vertically equal distance between the other two Button elements? (Pick 2 answers.)

My answer -> 1) app:layout_constraintBottom_toTopOf="@+id/button_count"

2) android:layout_marginBottom="8dp"

3) android:layout_marginStart="16dp"

My answer -> 4) app:layout_constraintTop_toBottomOf="@+id/button_toast"

5) android:layout_marginTop="8dp"


### Question 2

Which layout constraint attribute on the Zero Button positions it horizontally in alignment with the other two Button elements?

My answer -> 1) app:layout_constraintLeft_toLeftOf="parent"

2) app:layout_constraintBottom_toTopOf="@+id/button_count"

My answer -> 3) android:layout_marginBottom="8dp"

4) app:layout_constraintTop_toBottomOf="@+id/button_toast"


### Question 3

What is the correct signature for a method used with the android:onClick XML attribute?

1) public void callMethod()

My answer -> 2) public void callMethod(View view)

3) private void callMethod(View view)

4) public boolean callMethod(View view)


### Question 4
The click handler for the Count Button starts with the following method signature:
``` java
public void countUp(View view)
```
Which of the following techniques is more efficient to use within this handler to change the Button element's background color? Choose one:


My answer -> 1) Use findViewById to find the Count Button. Assign the result to a View variable, and then use ```setBackgroundColor()```.

2) Use the view parameter that is passed to the click handler with ```setBackgroundColor(): view.setBackgroundColor()```
