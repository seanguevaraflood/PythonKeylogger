<h1>Python Keylogger Homelab</h1>

<p>Keyloggers are a dangerous type of spyware that logs a user’s input so that a hacker can gain sensitive information, harvest credentials, or monitor an unsuspecting victim.</p>

<p>We will first begin by installing <code>pynput</code>.</p>

<p>Now let’s define our main method and have a listener pass the <code>on_press</code> information to the <code>keyPressed</code> function.</p>

<p>Let’s start the listener and capture its input.</p>

<p>Now let’s write our <code>keyPressed</code> function and print the output string to ourselves. We will use the <code>open</code> method to either create or open a file called <code>keyfile.txt</code> and append to the file using the <code>'a'</code> mode.</p>

<p>We will then use the <code>try</code> block to convert the characters into a file with <code>char = key.char</code> and write it to the file with <code>logKey.write(char)</code>.</p>

<p>We will also add an <code>except</code> block so the program doesn’t crash if it encounters errors.</p>

<p>Great, it works perfectly. This concludes our Python Keylogger Homelab!</p>

<p>In this lab I will install and configure Nessus Essentials to perform credentialed vulnerability scans on Windows 10 Hosts. Implemented Vulnerability Management Function on sandbox networks.</p>
