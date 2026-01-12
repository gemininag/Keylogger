<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Java Keyboard Event Logger</title>
</head>
<body>

    <h2>Overview</h2>
    <ul>
        <li>Captures global key events using <strong>JNativeHook</strong></li>
        <li>Saves keystrokes to <code>keys.txt</code> and logs activity in <code>all.log</code></li>
        <li>Intended for learning Java event handling and system input monitoring</li>
    </ul>

    <h2>Build &amp; Run</h2>

    <h3>Build Project</h3>
    <pre>
mvn package
    </pre>

    <h3>Run JAR</h3>
    <pre>
java -jar ./target/keylogger-jar-with-dependencies.jar
    </pre>

    <h2>Notes</h2>
    <ul>
        <li>Stop the program after testing</li>
        <li>Use only on machines you own or have permission to test</li>
        <li>Safe, educational demonstration of system monitoring</li>
    </ul>

</body>
</html>
