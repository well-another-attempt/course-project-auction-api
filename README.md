### Deploy steps for Nikita

1. [Install correct Java version](https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/windows-7-install.html)
2. [Install maven](https://linuxize.com/post/how-to-install-apache-maven-on-ubuntu-18-04/#installing-apache-maven-on-ubuntu-with-apt)
3. Run the project:
```bash
   mvn spring-boot:run
```
4. Open in the browser
```
http://localhost:8080/h2-ui
```
5. Press the button "Test Connection"