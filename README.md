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
#### 03:32
There are two types of Threads in Java: User Threads and Daemon Threads.
When a JVM starts if contains a single User Thread.  
- Known as main Thread  

Use Threads and Daemon THreads differ in what happens when they exit.
- The lifecycle a User Thread can outlive the Main Thread.
- All Daemon Threads terminate automatically when all User Threads terminate

- The JVM itself exits when all User Threads have exited and any remaining Threads are all Daemon Threads.
