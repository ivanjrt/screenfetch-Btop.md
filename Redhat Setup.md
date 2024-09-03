# Configuring the Executable App
- By default Redhat doesn't have Git.
```java
sudo yum install git -y
```

- Clone the Repo:
```java
git clone https://github.com/KittyKatt/screenFetch.git
```

- Add the bin file to the Binaries:
```java
cd screenfetch
sudo cp /screenfetch-dev /usr/bin/screenfetch
```

- Make it Executable:
```java
sudo chmod +x /usr/bin/screenfetch
```

- Now you can launch it with
```java
screenfetch
```

# Add it so opens up when opening the Terminal.
```java
nano ~/.bashrc
```
Add in the last line 
```java
screenfetch
```
