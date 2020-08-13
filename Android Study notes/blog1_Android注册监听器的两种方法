## 法一：新手多使用匿名类的方式注册监听器，这样虽然方便，但当监听方法较多时会导致结构混乱，
```java
public class MainActivity extends Activity {
        private Button button;
        @Override
        protected void onCreate(Bundle savedInstanceState) {
            super.onCreate(savedInstanceState);
            setContentView(R.layout.activity_main);
            button = (Button) findViewById(R.id.button);
            button.setOnClickListener(new OnClickListener() {
                @Override
                public void onClick(View v) {
 
// 在此处添加逻辑 }
 
}); }
 
} 
```
## 法二：实现接口方式注册监听器，这样即使监听方法较多时结构也较为清晰。

```java
public class MainActivity extends Activity implements OnClickListener {
        private Button button;
        @Override
        protected void onCreate(Bundle savedInstanceState) {
            super.onCreate(savedInstanceState);
            setContentView(R.layout.activity_main);
            button = (Button) findViewById(R.id.button);
            button.setOnClickListener(this);
}

        @Override
        public void onClick(View v) {
            switch (v.getId()) {
            case R.id.button:
// 在此处添加逻辑

                break;
            default:
break; }

 
} }
```
