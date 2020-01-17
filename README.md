# svg-to-vector-drawable
Use to bulk convert .svg to android format .xml files. These files are referred to as "Vector drawables" in android studio.

To use, stand in the root folder and run:
`java -jar Svg2VectorAndroid-1.1.1.jar <path to .svg folder>`

If changes needs to be done open the java file `SvgFilesProcessor` found in `src/main/java/com/vector/svg2vectorandroid/`.
Go back to the root folder and run `gradle clean`.
To build the new jar fine run `gradle fatJar`.
The file will be generated in `build/libs/`.