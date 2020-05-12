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
```javascript
import { withSnackbar } from 'notistack';

class MyComponent extends Component {
  handleNetworkRequest = () => {
     fetchSomeData()
        .then(() => this.props.enqueueSnackbar('Successfully fetched the data.'))
        .catch(() => this.props.enqueueSnackbar('Failed fetching data.'));
  };

  render(){
     //...
  };
  
};
