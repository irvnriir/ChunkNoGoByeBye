# ChunkNoGoByeBye-Xrud

the Xrud branch/version differ from [Commit](https://github.com/LexManos/ChunkNoGoByeBye/commit/ba0877e9a03615c8943cc9f9548903a85196857f)

<details><summary>that --</summary>

 make this [[link]](https://github.com/LexManos/ChunkNoGoByeBye/tree/ba0877e9a03615c8943cc9f9548903a85196857f) Tree/stage
of [ChunkNoGoByeBye](https://github.com/LexManos/ChunkNoGoByeBye/tree/master)

</details>

, only in build simplification, crafting Recipe and this readme .

you can download the packed/built version/mod, including a one with the default Recipe at [Releases](https://github.com/irvnriir/ChunkNoGoByeBye/releases) .

## edit and build

1. you need to install Java (SE) Runtime Environment or Development Kit (Software -DK) .
2. install Gradle .
3. Windows: Create JAVA_HOME and add the Gradle to Windows 's Path (Windows 's Environment Variables) ;.

4. edit if you want .

`build.gradle` has the packag/build-ing settings (like version, dependencies, ..) .  
`settings.gradle` is an optional init. packaging settings file .<sup>[[*](https://docs.gradle.org/current/userguide/build_lifecycle.html)]</sup>  
`gradle.properties` has the compiler technical settings .  
`gradlew` is an Unix packaging script .  
`gradlew.bat` is a Windows packaging script .  
`gradle\` is a required Gradle folder .  
`build\` is a temporals, requisites/dependencies downloads and output folder of the packaging .  
`src\` is the mod's files folder .

all the rest files/folders is an optional features .

4. Windows: 
	* launch `cmd.exe`, type "`<<the path>>\gradlew.bat build --warning-mode all <<enter>>`" ( `D:\files\mod\gradlew.bat` .. ) ,
	* or open the folder with VSCode and click `Terminal \ Run Build Task` . ;

5. your packaged-mod file is at `\build\libs` (the one without "-sources") .