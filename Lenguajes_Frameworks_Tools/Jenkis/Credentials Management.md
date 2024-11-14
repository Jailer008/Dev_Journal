
## Steps to Add Credentials
1. Go to **Credentials** on the left panel.
2. Select **Global** and choose **Add Credentials**.
3. Enter the **Username** and **Password**, then save.

## Usage Example
Reference credentials by ID in a pipeline:
```groovy
withCredentials([usernamePassword(credentialsId: 'myCred')]) {
    // Use credentials here
}
```

## Related Topics

- [[Jenkins Security]]- ￼￼Jenkins Overview