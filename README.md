# JavaGUI
Template and boiler plate code for a Java GUI Application

# Commands 
./gradlew run - run the application
./gradlew build - build the jar file (jar file located under app/build/libs)

# Intellij configuration argument and java -jar argument
--module-path ${PATH_TO_FX} --add-modules=javafx.controls,javafx.fxml,javafx.swing,javafx.web
java --module-path ${PATH_TO_FX} --add-modules=javafx.controls,javafx.fxml,javafx.swing,javafx.web -jar ./app.jar
Download the fx from the official website

more info on the config, https://stackoverflow.com/questions/53533486/how-to-open-javafx-jar-file-with-jdk-11

# Packaging
To avoid java -jar and all the args, the application needed to be package.
https://steemit.com/java/@walczakit/distributing-javafx-desktop-applications-without-requiring-a-jvm-using-jlink-and-jpackage