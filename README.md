<H1>GVol</H1>

GVol is a lightweight GUI application built in Java designed to automate the usage of volatility toolkit for the purpose of malware analysis. The application includes various volatility plugins with their predefined options. In addition to that, users can create batch files to run multiple plugins at once to scan a memory image. Furthermore, GVol includes pre-configured batch files to simplify the usage of volatility for malware analysis process.

<H2>Download</H2>
You can get a copy of the latest release from
<br />
https://github.com/eg-cert/GVol/releases
<H2>Building</H2>
Building should be as simple as

```
cd GVol
ant
```
<br />
the target jar file shall be under the dist directory

<H2>Running</H2>
```
java -jar GVol.jar
```


<H2>Configuration</H2>

Download the latest version from releases. You need the java runtime enviroment to run GVol. Run the file GVol.jar.
<br />
The first time you run GVol, you should tell it how to run Volatility. <br />
1- Menu bar > Configuration > Cmd & profiles <br />
2- Enter the command to run volatility in your system like "python vol.py" or the path of the standalone executable if you use it. <br />

For more details about the tool and how to use it, read the user guide.
