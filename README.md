# Layout
# ![线性布局截图](https://github.com/JojoBiid/Layout/blob/master/pic/LinearLayout.png)
# ![约束布局截图](https://github.com/JojoBiid/Layout/blob/master/pic/ConstraintLayout.png)
# ![表格布局截图](https://github.com/JojoBiid/Layout/blob/master/pic/TableLayout.png)

# 约束布局
```
<Button
        android:id="@+id/Button1"
        android:layout_width="0dp"
        android:layout_height="40dp"
        android:layout_marginStart="159dp"
        android:layout_marginEnd="159dp"
        android:background="@android:color/holo_blue_dark"
        android:text="blue"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button2"
        android:layout_width="74dp"
        android:layout_height="42dp"
        android:layout_marginEnd="296dp"
        android:layout_marginBottom="252dp"
        android:background="@android:color/holo_red_dark"
        android:text="red"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/button3"
        android:layout_width="74dp"
        android:layout_height="42dp"
        android:layout_marginStart="296dp"
        android:layout_marginBottom="252dp"
        android:background="@android:color/holo_orange_light"
        android:text="yellow"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button2"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/button4"
        android:layout_width="81dp"
        android:layout_height="46dp"
        android:layout_marginStart="81dp"
        android:layout_marginEnd="81dp"
        android:layout_marginBottom="88dp"
        android:background="@android:color/holo_orange_dark"
        android:text="orange"
        app:layout_constraintBottom_toTopOf="@+id/Button1"
        app:layout_constraintEnd_toStartOf="@+id/button3"
        app:layout_constraintStart_toEndOf="@+id/button2"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button5"
        android:layout_width="80dp"
        android:layout_height="40dp"
        android:layout_marginStart="74dp"
        android:layout_marginTop="88dp"
        android:layout_marginEnd="16dp"
        android:layout_marginBottom="130dp"
        android:background="@android:color/holo_green_light"
        android:text="green"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/Button1"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/button2" />

    <Button
        android:id="@+id/button6"
        android:layout_width="80dp"
        android:layout_height="40dp"
        android:layout_marginStart="16dp"
        android:layout_marginTop="88dp"
        android:layout_marginBottom="130dp"
        android:background="@color/colorPrimary"
        android:text="indigo"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toEndOf="@+id/Button1"
        app:layout_constraintTop_toBottomOf="@+id/button3" />

    <Button
        android:id="@+id/button7"
        android:layout_width="368dp"
        android:layout_height="wrap_content"
        android:background="@color/colorAccent"
        android:text="violet"
        tools:layout_editor_absoluteX="8dp"
        tools:layout_editor_absoluteY="245dp" />
```
