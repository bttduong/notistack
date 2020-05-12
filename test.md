- `Manifest.permission.BLUETOOTH`

   ```groovy
   dependencies  {
     implementation 'com.b:1.0.0'
   }
   ```
   
   
   
   ```java
 A a = new A.Builder(this.getApplicationContext(), "YOUR_ID")
   .setAutoScreen(true)
   .build();
  A.setSingletonInstance(a); // Set global instance.
```
