# kaptcha - A kaptcha generation engine.

This repo is the copy of http://code.google.com/p/kaptcha/ and published to maven central
```
<dependency>
  <groupId>com.shinetechsoftware</groupId>
  <artifactId>kaptcha</artifactId>
  <version>2.3.4</version>
</dependency>
```

for this reason and the upstream merged PR but not release to maven
```
Vulnerable versions: <= 2.3.2
Patched version: No fix
text/impl/DefaultTextCreator.java, text/impl/ChineseTextProducer.java, and text/impl/FiveLetterFirstNameTextCreator.java in kaptcha 2.3.2 use the Random (rather than SecureRandom) function for generating CAPTCHA values, which makes it easier for remote attackers to bypass intended access restrictions via a brute-force approach.
```

Please see the website for more information about this project.

http://code.google.com/p/kaptcha/

thanks!
