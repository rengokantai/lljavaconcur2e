# lljavaconcur2e
## 2.Attaching a New Service to Our Overlay Network
### 1 Recognize the Java threading mechanisms available to program concurrent software
```
public class MyThread extends Thread{
  public void run(){
  }
}
```

```
public class MyRunnable implements Runnable{
  public void run(){
  }
}

MyRunnable myRunnable = new MyRunnable();
new Thread(myRunnable).start();
```
