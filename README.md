# setup

- 👋 Hi, I’m @ruzun88
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ruzun88/ruzun88 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# gitpod
> 깃파드를 사용하면, 아래의 다른 처리들은 필요 없음   

- https://chrome.google.com/webstore/category/extensions?hl=ko& 에서 gitpod 검색 및 Extension 설치
- github repository로 가서 gitpod 클릭



# cmd
mkdir c:\factory

# 자바
https://adoptium.net/temurin/releases/   
다운로드 후,   
```
cd c:\Users\Administrator\Downloads
move OpenJDK11U-jdk_x64_windows_hotspot_11.0.17_8.zip c:\factory\
explorer .
```

# 환경변수
Cmd에서
```
setx path "%path%;C:\factory\jdk-11.0.17+8\bin;"
```
Cmd 껐다 키기

# sts
https://spring.io/tools
```
cd c:\Users\Administrator\Downloads
move spring-tool-suite-4-4.16.1.RELEASE-e4.25.0-win32.win32.x86_64.self-extracting.jar c:\factory\
java -jar spring 탭
```

# 롬복
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
