# compilation instructions
javac --source-path myapp -d bin myapp/*


kanghui@Kangs-MacBook-Air bin % cd ..                                
kanghui@Kangs-MacBook-Air vttp5_sdf_day01l % ls -la
total 16
drwxr-xr-x   7 kanghui  staff  224 Oct  2 14:09 .
drwxr-x---+ 23 kanghui  staff  736 Oct  2 13:36 ..
drwxr-xr-x  12 kanghui  staff  384 Oct  2 12:37 .git
-rw-r--r--@  1 kanghui  staff  130 Oct  2 14:06 HelloWorld.java
-rw-r--r--@  1 kanghui  staff   68 Oct  2 13:55 README.md
drwxr-xr-x   2 kanghui  staff   64 Oct  2 14:20 bin
drwxr-xr-x@  2 kanghui  staff   64 Oct  2 14:09 myapp
kanghui@Kangs-MacBook-Air vttp5_sdf_day01l % javac --source-path . -d bin ./*.java
kanghui@Kangs-MacBook-Air vttp5_sdf_day01l % java -cp bin HelloWorld
Hello World...
