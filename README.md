# simple-logs-analyzer
SimpleLogsAnalyzer - tool to automatically sort logs for sql injections, xss, access denied requests

<b>Some simple rules to use it:</b>
* To check your logs, simply put required log files in the same folder as tool and run the tool
* Logs must have .log extension and must be unpacked if they were archived
* Tool and logs must be in one folder
* Text files with results will be created in the same folder (sql_payloads.txt, xss_payloads.txt, denied_payloads.txt)

<pre>
<b>File MD5 sum:</b> D72C036B3E8C2049FCF500CC3D915B88
<b>File SHA-256 sum:</b> F324A0666CCA6E6C667AE39C6DCBA150487CA5A349CB1EADE6B96E0E887BEB84
</pre>
<a href="https://www.virustotal.com/en/file/f324a0666cca6e6c667ae39c6dcba150487ca5a349cb1eade6b96e0e887beb84/analysis/1472816301/" rel="nofollow" target=_blank>VirusTotal Results</a> - Shows some strange detections, but I think it is due to packing of python into executable file.
