# setup

- ๐ Hi, Iโm @ruzun88
- ๐ Iโm interested in ...
- ๐ฑ Iโm currently learning ...
- ๐๏ธ Iโm looking to collaborate on ...
- ๐ซ How to reach me ...

<!---
ruzun88/ruzun88 is a โจ special โจ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# gitpod
> ๊นํ๋๋ฅผ ์ฌ์ฉํ๋ฉด, ์๋์ ๋ค๋ฅธ ์ฒ๋ฆฌ๋ค์ ํ์ ์์   

- https://chrome.google.com/webstore/category/extensions?hl=ko& ์์ gitpod ๊ฒ์ ๋ฐ Extension ์ค์น
- github repository๋ก ๊ฐ์ gitpod ํด๋ฆญ



# cmd
mkdir c:\factory

# ์๋ฐ
https://adoptium.net/temurin/releases/   
๋ค์ด๋ก๋ ํ,   
```
cd c:\Users\Administrator\Downloads
move OpenJDK11U-jdk_x64_windows_hotspot_11.0.17_8.zip c:\factory\
explorer .
```

# ํ๊ฒฝ๋ณ์
Cmd์์
```
setx path "%path%;C:\factory\jdk-11.0.17+8\bin;"
```
Cmd ๊ป๋ค ํค๊ธฐ

# sts
https://spring.io/tools
```
cd c:\Users\Administrator\Downloads
move spring-tool-suite-4-4.16.1.RELEASE-e4.25.0-win32.win32.x86_64.self-extracting.jar c:\factory\
java -jar spring ํญ
```

# ๋กฌ๋ณต
https://projectlombok.org/downloads/lombok.jar   
   
```
move lombok.jar c:\factory\
java -jar lombok.jar
```

# Maven
https://dlcdn.apache.org/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.zip   
   
```
move apache-maven-3.8.6-bin.zip c:\factory\
setx path "%path%;C:\factory\apache-maven-3.8.6;"
```
